# AutoNodes 每日报告

生成时间：2026-08-10 13:00:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 87155 |
| 去重后节点数 | 24814 |
| TCP 可达数 | 3000 |
| 真测通过数 | 497 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24814 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 35.8 |
| geo | 1.3 |
| probe | 49.5 |
| real_test | 104.8 |
| tcp | 35.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 18 | 14 | 4 | 77.8% |
| shadowsocks | 142 | 126 | 16 | 88.7% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 143 | 135 | 8 | 94.4% |
| vless | 251 | 195 | 56 | 77.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 18 |
| speed:TimeoutError | 11 |
| geo:ClientOSError | 10 |
| 204:ProxyError | 10 |
| geo:TimeoutError | 8 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4184 |
| ConnectionRefusedError | 869 |
| gaierror | 396 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | prefer | 463 | 0.909 | 1696 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| DeltaKronecker-all | 0.673 | observe | 25 | 0.6 | 5881 |
| Surfboard-tg-mixed | 0.636 | observe | 52 | 0.558 | 6528 |
| mheidari-all | 0.425 | observe | 15 | 0.4 | 20526 |
| tg-oneclickvpnkeys | 0.405 | observe | 4 | 1.0 | 122 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7165 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| SoliSpirit-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.4 | 6 | 9 | 15 |
| Surfboard-tg-mixed | 0.558 | 29 | 23 | 52 |
| DeltaKronecker-all | 0.6 | 15 | 10 | 25 |
| Au1rxx-base64 | 0.909 | 421 | 42 | 463 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20526 | yes | 4.79 | 0 |
| SoliSpirit-all | 7903 | yes | 3.72 | 0 |
| Epodonios-all | 7165 | yes | 2.92 | 0 |
| Surfboard-tg-mixed | 6528 | yes | 3.4 | 0 |
| DeltaKronecker-all | 5881 | yes | 5.13 | 0 |
| barry-far-vless | 5695 | yes | 2.25 | 0 |
| Surfboard-tg-vless | 5435 | yes | 3.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 2.81 | 0 |
| mahdibland-V2RayAggregator | 5191 | yes | 2.7 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 31 |
| cn-block | 20 |
| geo | 18 |
| speed | 16 |
