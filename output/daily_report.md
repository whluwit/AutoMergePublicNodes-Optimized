# AutoNodes 每日报告

生成时间：2026-10-04 16:29:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 99560 |
| 去重后节点数 | 27313 |
| TCP 可达数 | 3000 |
| 真测通过数 | 375 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27313 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 86.2 |
| geo | 1.2 |
| probe | 205.3 |
| real_test | 174.0 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 4 | 2 | 66.7% |
| http | 25 | 11 | 14 | 44.0% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 125 | 112 | 13 | 89.6% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 65 | 63 | 2 | 96.9% |
| vless | 221 | 173 | 48 | 78.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 18 |
| 204:ProxyConnectionError | 15 |
| 204:TimeoutError | 15 |
| speed:TimeoutError | 9 |
| geo:TimeoutError | 9 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| speed:ClientOSError | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6635 |
| ConnectionRefusedError | 1059 |
| gaierror | 362 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.949 | prefer | 295 | 0.878 | 1831 |
| mheidari-all | 0.895 | prefer | 52 | 0.827 | 23366 |
| Surfboard-tg-mixed | 0.846 | prefer | 75 | 0.773 | 7225 |
| ermaozi | 0.471 | observe | 25 | 0.44 | 653 |
| DeltaKronecker-all | 0.349 | observe | 3 | 0.667 | 5267 |
| ermaozi-get_subscribe | 0.261 | observe | 4 | 0.5 | 518 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5173 |
| Epodonios-all | 0.255 | observe | 0 | None | 7759 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9833 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.44 | 11 | 14 | 25 |
| ermaozi-get_subscribe | 0.5 | 2 | 2 | 4 |
| DeltaKronecker-all | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.773 | 58 | 17 | 75 |
| mheidari-all | 0.827 | 43 | 9 | 52 |
| Au1rxx-base64 | 0.878 | 259 | 36 | 295 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23366 | yes | 6.43 | 0 |
| SoliSpirit-all | 9833 | yes | 4.63 | 0 |
| Epodonios-all | 7759 | yes | 4.0 | 0 |
| Surfboard-tg-mixed | 7225 | yes | 4.97 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.49 | 0 |
| barry-far-vless | 6063 | yes | 2.34 | 0 |
| Surfboard-tg-vless | 5815 | yes | 4.68 | 0 |
| DeltaKronecker-all | 5267 | yes | 7.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 5173 | yes | 2.12 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 3.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 37 |
| cn-block | 22 |
| speed | 11 |
| geo | 11 |
