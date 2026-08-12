# AutoNodes 每日报告

生成时间：2026-08-12 07:22:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 88199 |
| 去重后节点数 | 23601 |
| TCP 可达数 | 3000 |
| 真测通过数 | 587 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23601 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 18.9 |
| generate | 49.0 |
| geo | 1.4 |
| probe | 59.0 |
| real_test | 136.8 |
| tcp | 35.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 127 | 1 | 99.2% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 164 | 148 | 16 | 90.2% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 122 | 109 | 13 | 89.3% |
| vless | 341 | 182 | 159 | 53.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 42 |
| geo:ClientOSError | 38 |
| speed:TimeoutError | 38 |
| speed:ClientOSError | 20 |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 13 |
| 204:TimeoutError | 11 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4815 |
| ConnectionRefusedError | 806 |
| gaierror | 280 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 128 | 0.992 | 159 |
| Au1rxx-base64 | 0.898 | prefer | 429 | 0.834 | 1632 |
| Surfboard-tg-mixed | 0.693 | observe | 109 | 0.615 | 5943 |
| DeltaKronecker-all | 0.497 | observe | 34 | 0.412 | 4975 |
| mheidari-all | 0.343 | observe | 74 | 0.257 | 20330 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 4568 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5328 |
| Epodonios-all | 0.255 | observe | 0 | None | 6602 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |
| tg-AzadNet | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.257 | 19 | 55 | 74 |
| DeltaKronecker-all | 0.412 | 14 | 20 | 34 |
| Surfboard-tg-mixed | 0.615 | 67 | 42 | 109 |
| Au1rxx-base64 | 0.834 | 358 | 71 | 429 |
| zhangkai | 0.992 | 127 | 1 | 128 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20330 | yes | 5.46 | 0 |
| SoliSpirit-all | 7652 | yes | 3.99 | 0 |
| Epodonios-all | 6602 | yes | 2.82 | 0 |
| Surfboard-tg-mixed | 5943 | yes | 3.44 | 0 |
| 10ium-ScrapeCategorize-Vless | 5328 | yes | 1.48 | 0 |
| barry-far-vless | 5202 | yes | 1.19 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 2.91 | 0 |
| DeltaKronecker-all | 4975 | yes | 5.59 | 0 |
| Surfboard-tg-vless | 4919 | yes | 3.23 | 0 |
| xiaoji235-airport-v2ray-all | 4568 | yes | 2.34 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 80 |
| speed | 58 |
| 204 | 34 |
| cn-block | 20 |
