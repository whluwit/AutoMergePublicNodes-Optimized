# AutoNodes 每日报告

生成时间：2026-10-01 03:59:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 98025 |
| 去重后节点数 | 27299 |
| TCP 可达数 | 3000 |
| 真测通过数 | 437 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27299 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 75.2 |
| geo | 1.5 |
| probe | 264.0 |
| real_test | 343.2 |
| tcp | 46.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 14 | 6 | 8 | 42.9% |
| hysteria2 | 25 | 21 | 4 | 84.0% |
| shadowsocks | 166 | 149 | 17 | 89.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 49 | 34 | 15 | 69.4% |
| vless | 505 | 225 | 280 | 44.6% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 108 |
| speed:ClientOSError | 61 |
| speed:TimeoutError | 55 |
| geo:ClientOSError | 30 |
| 204:ProxyConnectionError | 17 |
| cn-block:TimeoutError | 16 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 9 |
| 204:TimeoutError | 9 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6505 |
| ConnectionRefusedError | 1007 |
| gaierror | 398 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.881 | prefer | 287 | 0.812 | 1783 |
| Surfboard-tg-mixed | 0.719 | prefer | 189 | 0.64 | 7136 |
| DeltaKronecker-all | 0.515 | observe | 16 | 0.5 | 5434 |
| ermaozi | 0.376 | observe | 14 | 0.429 | 588 |
| mheidari-all | 0.352 | observe | 255 | 0.271 | 22835 |
| Epodonios-all | 0.255 | observe | 0 | None | 7637 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9410 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5815 |
| barry-far-vless | 0.255 | observe | 0 | None | 6001 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.271 | 69 | 186 | 255 |
| ermaozi | 0.429 | 6 | 8 | 14 |
| DeltaKronecker-all | 0.5 | 8 | 8 | 16 |
| Surfboard-tg-mixed | 0.64 | 121 | 68 | 189 |
| Au1rxx-base64 | 0.812 | 233 | 54 | 287 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22835 | yes | 5.76 | 0 |
| SoliSpirit-all | 9410 | yes | 4.25 | 0 |
| Epodonios-all | 7637 | yes | 1.05 | 0 |
| Surfboard-tg-mixed | 7136 | yes | 4.77 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.87 | 0 |
| barry-far-vless | 6001 | yes | 0.84 | 0 |
| Surfboard-tg-vless | 5815 | yes | 3.75 | 0 |
| DeltaKronecker-all | 5434 | yes | 6.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 3.31 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 0.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 140 |
| speed | 117 |
| 204 | 44 |
| cn-block | 27 |
