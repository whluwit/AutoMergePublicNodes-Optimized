# AutoNodes 每日报告

生成时间：2026-07-23 02:26:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 81619 |
| 去重后节点数 | 22921 |
| TCP 可达数 | 3000 |
| 真测通过数 | 642 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22921 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 21.7 |
| geo | 1.2 |
| probe | 69.8 |
| real_test | 171.8 |
| tcp | 31.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 13 | 12 | 1 | 92.3% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 484 | 456 | 28 | 94.2% |
| vless | 516 | 130 | 386 | 25.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 188 |
| speed:ClientOSError | 103 |
| speed:TimeoutError | 44 |
| geo:ClientOSError | 34 |
| cn-block:TimeoutError | 21 |
| 204:ProxyError | 16 |
| 204:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4019 |
| ConnectionRefusedError | 715 |
| gaierror | 394 |
| OSError | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.994 | prefer | 68 | 0.926 | 5286 |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| DeltaKronecker-all | 0.749 | prefer | 170 | 0.671 | 5212 |
| mheidari-all | 0.626 | observe | 777 | 0.546 | 19024 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 4399 |
| Au1rxx-base64 | 0.329 | observe | 2 | 1.0 | 432 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4613 |
| Epodonios-all | 0.255 | observe | 0 | None | 6359 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3965 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.546 | 424 | 353 | 777 |
| DeltaKronecker-all | 0.671 | 114 | 56 | 170 |
| Surfboard-tg-mixed | 0.926 | 63 | 5 | 68 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19024 | yes | 4.03 | 0 |
| SoliSpirit-all | 6916 | yes | 1.9 | 0 |
| Epodonios-all | 6359 | yes | 1.94 | 0 |
| Surfboard-tg-mixed | 5286 | yes | 2.28 | 0 |
| DeltaKronecker-all | 5212 | yes | 3.76 | 0 |
| mahdibland-V2RayAggregator | 4954 | yes | 1.76 | 0 |
| 10ium-ScrapeCategorize-Vless | 4613 | yes | 1.31 | 0 |
| barry-far-vless | 4602 | yes | 1.1 | 0 |
| xiaoji235-airport-v2ray-all | 4399 | yes | 1.49 | 0 |
| Surfboard-tg-vless | 4008 | yes | 2.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 222 |
| speed | 149 |
| 204 | 23 |
| cn-block | 22 |
