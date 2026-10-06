# AutoNodes 每日报告

生成时间：2026-10-06 04:43:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 98055 |
| 去重后节点数 | 27353 |
| TCP 可达数 | 3000 |
| 真测通过数 | 542 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27353 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 81.3 |
| geo | 1.5 |
| probe | 267.9 |
| real_test | 340.3 |
| tcp | 45.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 59 | 36 | 23 | 61.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 168 | 157 | 11 | 93.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 123 | 111 | 12 | 90.2% |
| vless | 444 | 221 | 223 | 49.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 107 |
| speed:TimeoutError | 46 |
| 204:ProxyError | 29 |
| geo:ClientOSError | 27 |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 16 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 9 |
| 204:ProxyConnectionError | 7 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5897 |
| ConnectionRefusedError | 1037 |
| gaierror | 450 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | prefer | 371 | 0.908 | 1814 |
| Surfboard-tg-mixed | 0.843 | prefer | 133 | 0.767 | 7145 |
| ermaozi | 0.628 | observe | 58 | 0.603 | 691 |
| DeltaKronecker-all | 0.372 | observe | 9 | 0.444 | 5300 |
| mheidari-all | 0.342 | observe | 235 | 0.26 | 23039 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 76 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5111 |
| Epodonios-all | 0.255 | observe | 0 | None | 7631 |

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
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| tg-OutlineReleasedKey | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.26 | 61 | 174 | 235 |
| DeltaKronecker-all | 0.444 | 4 | 5 | 9 |
| ermaozi | 0.603 | 35 | 23 | 58 |
| Surfboard-tg-mixed | 0.767 | 102 | 31 | 133 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23039 | yes | 6.57 | 0 |
| SoliSpirit-all | 9144 | yes | 3.89 | 0 |
| Epodonios-all | 7631 | yes | 4.96 | 0 |
| Surfboard-tg-mixed | 7145 | yes | 4.76 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.53 | 0 |
| barry-far-vless | 5876 | yes | 3.1 | 0 |
| Surfboard-tg-vless | 5642 | yes | 4.21 | 0 |
| DeltaKronecker-all | 5300 | yes | 6.18 | 0 |
| 10ium-ScrapeCategorize-Vless | 5111 | yes | 2.63 | 0 |
| mahdibland-V2RayAggregator | 4375 | yes | 3.54 | 0 |

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
| geo | 134 |
| speed | 57 |
| 204 | 55 |
| cn-block | 28 |
