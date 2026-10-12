# AutoNodes 每日报告

生成时间：2026-10-12 14:29:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 100401 |
| 去重后节点数 | 27831 |
| TCP 可达数 | 3000 |
| 真测通过数 | 485 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27831 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 94.5 |
| geo | 1.5 |
| probe | 347.1 |
| real_test | 386.2 |
| tcp | 46.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 1 | 3 | 25.0% |
| http | 53 | 25 | 28 | 47.2% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 154 | 124 | 30 | 80.5% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 170 | 153 | 17 | 90.0% |
| vless | 221 | 165 | 56 | 74.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 29 |
| cn-block:TimeoutError | 28 |
| 204:TimeoutError | 26 |
| geo:ClientOSError | 12 |
| cn-block:ClientOSError | 10 |
| speed:TimeoutError | 8 |
| 204:ClientOSError | 7 |
| speed:ClientOSError | 7 |
| geo:TimeoutError | 5 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6473 |
| ConnectionRefusedError | 1058 |
| gaierror | 363 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | prefer | 355 | 0.91 | 1816 |
| mheidari-all | 0.847 | prefer | 58 | 0.776 | 24027 |
| DeltaKronecker-all | 0.747 | prefer | 40 | 0.675 | 5701 |
| Surfboard-tg-mixed | 0.66 | observe | 110 | 0.582 | 7166 |
| ermaozi | 0.491 | observe | 54 | 0.463 | 675 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5028 |
| Epodonios-all | 0.255 | observe | 0 | None | 7671 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9940 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5781 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| ermaozi | 0.463 | 25 | 29 | 54 |
| Surfboard-tg-mixed | 0.582 | 64 | 46 | 110 |
| DeltaKronecker-all | 0.675 | 27 | 13 | 40 |
| mheidari-all | 0.776 | 45 | 13 | 58 |
| Au1rxx-base64 | 0.91 | 323 | 32 | 355 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24027 | yes | 6.02 | 0 |
| SoliSpirit-all | 9940 | yes | 3.47 | 0 |
| Epodonios-all | 7671 | yes | 6.31 | 0 |
| Surfboard-tg-mixed | 7166 | yes | 6.55 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.72 | 0 |
| barry-far-vless | 6031 | yes | 0.74 | 0 |
| Surfboard-tg-vless | 5781 | yes | 4.12 | 0 |
| DeltaKronecker-all | 5701 | yes | 6.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 5028 | yes | 1.0 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 3.68 | 0 |

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
| 204 | 66 |
| cn-block | 40 |
| geo | 17 |
| speed | 16 |
