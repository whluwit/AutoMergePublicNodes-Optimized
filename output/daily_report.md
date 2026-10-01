# AutoNodes 每日报告

生成时间：2026-10-01 12:29:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 98623 |
| 去重后节点数 | 27377 |
| TCP 可达数 | 3000 |
| 真测通过数 | 412 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27377 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 79.5 |
| geo | 1.4 |
| probe | 303.5 |
| real_test | 212.7 |
| tcp | 45.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 174 | 149 | 25 | 85.6% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 32 | 23 | 9 | 71.9% |
| vless | 328 | 195 | 133 | 59.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 75 |
| 204:TimeoutError | 30 |
| cn-block:TimeoutError | 17 |
| geo:TimeoutError | 12 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 6 |
| geo:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6186 |
| ConnectionRefusedError | 1015 |
| gaierror | 373 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.899 | prefer | 22 | 0.909 | 588 |
| Au1rxx-base64 | 0.85 | prefer | 306 | 0.781 | 1767 |
| mheidari-all | 0.83 | prefer | 66 | 0.758 | 23162 |
| Surfboard-tg-mixed | 0.772 | prefer | 115 | 0.696 | 7144 |
| DeltaKronecker-all | 0.386 | observe | 70 | 0.3 | 5603 |
| tg-oneclickvpnkeys | 0.314 | observe | 2 | 1.0 | 66 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5324 |
| Epodonios-all | 0.255 | observe | 0 | None | 7625 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9489 |

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
| DeltaKronecker-all | 0.3 | 21 | 49 | 70 |
| Surfboard-tg-mixed | 0.696 | 80 | 35 | 115 |
| mheidari-all | 0.758 | 50 | 16 | 66 |
| Au1rxx-base64 | 0.781 | 239 | 67 | 306 |
| ermaozi | 0.909 | 20 | 2 | 22 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23162 | yes | 4.81 | 0 |
| SoliSpirit-all | 9489 | yes | 2.55 | 0 |
| Epodonios-all | 7625 | yes | 2.6 | 0 |
| Surfboard-tg-mixed | 7144 | yes | 3.36 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.54 | 0 |
| barry-far-vless | 6050 | yes | 1.29 | 0 |
| Surfboard-tg-vless | 5788 | yes | 3.14 | 0 |
| DeltaKronecker-all | 5603 | yes | 4.23 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 1.45 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 2.32 | 0 |

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
| speed | 85 |
| 204 | 38 |
| cn-block | 28 |
| geo | 19 |
