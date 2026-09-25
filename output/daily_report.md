# AutoNodes 每日报告

生成时间：2026-09-25 03:19:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 98026 |
| 去重后节点数 | 26569 |
| TCP 可达数 | 3000 |
| 真测通过数 | 476 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26569 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 30.7 |
| geo | 1.5 |
| probe | 290.5 |
| real_test | 354.6 |
| tcp | 43.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 31 | 20 | 11 | 64.5% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 190 | 182 | 8 | 95.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 57 | 36 | 21 | 63.2% |
| vless | 462 | 215 | 247 | 46.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 116 |
| speed:TimeoutError | 48 |
| geo:ClientOSError | 36 |
| speed:ClientOSError | 31 |
| 204:ProxyError | 17 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 11 |
| cn-block:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6043 |
| ConnectionRefusedError | 972 |
| gaierror | 401 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | prefer | 296 | 0.905 | 1702 |
| Surfboard-tg-mixed | 0.782 | prefer | 189 | 0.704 | 7399 |
| ermaozi | 0.643 | observe | 25 | 0.64 | 338 |
| ermaozi-get_subscribe | 0.38 | observe | 5 | 0.8 | 359 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| mheidari-all | 0.298 | observe | 241 | 0.216 | 22554 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 65 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5307 |
| Epodonios-all | 0.255 | observe | 0 | None | 7876 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.216 | 52 | 189 | 241 |
| ermaozi | 0.64 | 16 | 9 | 25 |
| Surfboard-tg-mixed | 0.704 | 133 | 56 | 189 |
| ermaozi-get_subscribe | 0.8 | 4 | 1 | 5 |
| Au1rxx-base64 | 0.905 | 268 | 28 | 296 |
| ninja-vless | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22554 | yes | 4.47 | 0 |
| SoliSpirit-all | 9222 | yes | 1.7 | 0 |
| Epodonios-all | 7876 | yes | 2.48 | 0 |
| Surfboard-tg-mixed | 7399 | yes | 2.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.27 | 0 |
| barry-far-vless | 6091 | yes | 1.4 | 0 |
| Surfboard-tg-vless | 5862 | yes | 2.62 | 0 |
| DeltaKronecker-all | 5845 | yes | 4.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 1.87 | 0 |
| mahdibland-V2RayAggregator | 4405 | yes | 2.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 152 |
| speed | 79 |
| 204 | 30 |
| cn-block | 28 |
