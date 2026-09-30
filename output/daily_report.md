# AutoNodes 每日报告

生成时间：2026-09-30 03:57:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96898 |
| 去重后节点数 | 27022 |
| TCP 可达数 | 3000 |
| 真测通过数 | 444 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27022 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 85.1 |
| geo | 1.5 |
| probe | 340.3 |
| real_test | 506.6 |
| tcp | 45.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 35 | 26 | 9 | 74.3% |
| hysteria2 | 24 | 22 | 2 | 91.7% |
| shadowsocks | 178 | 157 | 21 | 88.2% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 1 | 1 | 0 | 100.0% |
| vless | 666 | 232 | 434 | 34.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 182 |
| speed:TimeoutError | 87 |
| speed:ClientOSError | 74 |
| geo:ClientOSError | 58 |
| 204:TimeoutError | 22 |
| 204:ProxyError | 15 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 7 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6560 |
| ConnectionRefusedError | 998 |
| gaierror | 355 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.861 | prefer | 294 | 0.793 | 1753 |
| ermaozi | 0.728 | prefer | 33 | 0.727 | 335 |
| Surfboard-tg-mixed | 0.699 | observe | 137 | 0.62 | 7024 |
| ermaozi-get_subscribe | 0.414 | observe | 4 | 1.0 | 353 |
| DeltaKronecker-all | 0.337 | observe | 7 | 0.429 | 5528 |
| tg-oneclickvpnkeys | 0.314 | observe | 2 | 1.0 | 62 |
| mheidari-all | 0.295 | observe | 430 | 0.214 | 22586 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5314 |
| Epodonios-all | 0.255 | observe | 0 | None | 7591 |

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
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.214 | 92 | 338 | 430 |
| DeltaKronecker-all | 0.429 | 3 | 4 | 7 |
| Surfboard-tg-mixed | 0.62 | 85 | 52 | 137 |
| ermaozi | 0.727 | 24 | 9 | 33 |
| Au1rxx-base64 | 0.793 | 233 | 61 | 294 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| ermaozi-get_subscribe | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22586 | yes | 6.39 | 0 |
| SoliSpirit-all | 9347 | yes | 1.49 | 0 |
| Epodonios-all | 7591 | yes | 5.8 | 0 |
| Surfboard-tg-mixed | 7024 | yes | 5.08 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.09 | 0 |
| barry-far-vless | 5895 | yes | 1.15 | 0 |
| Surfboard-tg-vless | 5656 | yes | 4.8 | 0 |
| DeltaKronecker-all | 5528 | yes | 3.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 5314 | yes | 0.9 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 2.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 240 |
| speed | 162 |
| 204 | 43 |
| cn-block | 22 |
