# AutoNodes 每日报告

生成时间：2026-10-03 15:46:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 99539 |
| 去重后节点数 | 27327 |
| TCP 可达数 | 3000 |
| 真测通过数 | 354 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27327 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 75.1 |
| geo | 1.0 |
| probe | 274.6 |
| real_test | 166.0 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 24 | 15 | 9 | 62.5% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 132 | 108 | 24 | 81.8% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 34 | 33 | 1 | 97.1% |
| vless | 231 | 184 | 47 | 79.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 21 |
| 204:ProxyConnectionError | 16 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 8 |
| speed:TimeoutError | 6 |
| geo:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| speed:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6545 |
| ConnectionRefusedError | 1108 |
| gaierror | 446 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.934 | prefer | 39 | 0.872 | 7404 |
| Au1rxx-base64 | 0.906 | prefer | 288 | 0.837 | 1778 |
| mheidari-all | 0.839 | prefer | 81 | 0.765 | 23342 |
| ermaozi | 0.619 | observe | 25 | 0.6 | 656 |
| ermaozi-get_subscribe | 0.274 | observe | 1 | 1.0 | 478 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 5207 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5192 |
| Epodonios-all | 0.255 | observe | 0 | None | 7883 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9374 |

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
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| ermaozi | 0.6 | 15 | 10 | 25 |
| mheidari-all | 0.765 | 62 | 19 | 81 |
| Au1rxx-base64 | 0.837 | 241 | 47 | 288 |
| Surfboard-tg-mixed | 0.872 | 34 | 5 | 39 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23342 | yes | 6.51 | 0 |
| SoliSpirit-all | 9374 | yes | 2.23 | 0 |
| Epodonios-all | 7883 | yes | 3.69 | 0 |
| Surfboard-tg-mixed | 7404 | yes | 5.86 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.92 | 0 |
| barry-far-vless | 6273 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 6035 | yes | 4.04 | 0 |
| DeltaKronecker-all | 5207 | yes | 5.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 0.99 | 0 |
| mahdibland-V2RayAggregator | 4335 | yes | 3.77 | 0 |

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
| 204 | 40 |
| cn-block | 24 |
| geo | 11 |
| speed | 10 |
