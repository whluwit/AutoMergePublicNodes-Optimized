# AutoNodes 每日报告

生成时间：2026-07-12 19:02:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 77603 |
| 去重后节点数 | 24151 |
| TCP 可达数 | 3000 |
| 真测通过数 | 158 |
| verified 输出数 | 158 |
| global 输出数 | 176 |
| all 输出数 | 24151 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 44.7 |
| geo | 1.3 |
| probe | 52.2 |
| real_test | 65.4 |
| tcp | 32.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 1 | 1 | 0 | 100.0% |
| shadowsocks | 75 | 56 | 19 | 74.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 114 | 47 | 67 | 41.2% |
| vless | 41 | 11 | 30 | 26.8% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 29 |
| speed:ClientOSError | 22 |
| 204:ProxyError | 14 |
| cn-block:ClientOSError | 11 |
| geo:TimeoutError | 10 |
| 204:ClientOSError | 7 |
| cn-block:TimeoutError | 7 |
| cn-block:ProxyError | 6 |
| geo:ClientOSError | 4 |
| speed:ProxyError | 3 |
| geo:ProxyError | 2 |
| speed:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4373 |
| ConnectionRefusedError | 663 |
| gaierror | 286 |
| OSError | 202 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.705 | prefer | 94 | 0.628 | 5591 |
| mheidari-all | 0.629 | observe | 49 | 0.551 | 16307 |
| DeltaKronecker-all | 0.448 | observe | 93 | 0.366 | 8141 |
| xiaoji235-airport-v2ray-all | 0.315 | observe | 1 | 1.0 | 1508 |
| Au1rxx-base64 | 0.26 | observe | 1 | 1.0 | 124 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4003 |
| Epodonios-all | 0.255 | observe | 0 | None | 6622 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6588 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.366 | 34 | 59 | 93 |
| mheidari-all | 0.551 | 27 | 22 | 49 |
| Surfboard-tg-mixed | 0.628 | 59 | 35 | 94 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16307 | yes | 2.91 | 0 |
| DeltaKronecker-all | 8141 | yes | 3.7 | 0 |
| Epodonios-all | 6622 | yes | 0.26 | 0 |
| SoliSpirit-all | 6588 | yes | 2.47 | 0 |
| Surfboard-tg-mixed | 5591 | yes | 2.12 | 0 |
| mahdibland-V2RayAggregator | 5438 | yes | 0.38 | 0 |
| barry-far-vless | 4906 | yes | 1.86 | 0 |
| Surfboard-tg-vless | 4292 | yes | 2.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 4003 | yes | 1.31 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.69 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 50 |
| speed | 27 |
| cn-block | 24 |
| geo | 16 |
