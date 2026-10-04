# AutoNodes 每日报告

生成时间：2026-10-04 20:57:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 99293 |
| 去重后节点数 | 27429 |
| TCP 可达数 | 3000 |
| 真测通过数 | 386 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27429 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 75.2 |
| geo | 1.5 |
| probe | 200.4 |
| real_test | 163.5 |
| tcp | 47.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 5 | 1 | 83.3% |
| http | 26 | 6 | 20 | 23.1% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 143 | 123 | 20 | 86.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 56 | 50 | 6 | 89.3% |
| vless | 216 | 183 | 33 | 84.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyConnectionError | 19 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 11 |
| geo:TimeoutError | 8 |
| speed:TimeoutError | 5 |
| geo:ClientOSError | 4 |
| speed:ClientOSError | 4 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6566 |
| ConnectionRefusedError | 1049 |
| gaierror | 367 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | prefer | 311 | 0.916 | 1858 |
| mheidari-all | 0.864 | prefer | 86 | 0.791 | 23222 |
| Surfboard-tg-mixed | 0.721 | prefer | 37 | 0.649 | 7257 |
| ermaozi-get_subscribe | 0.341 | observe | 4 | 0.75 | 518 |
| ermaozi | 0.295 | observe | 24 | 0.25 | 653 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5173 |
| Epodonios-all | 0.255 | observe | 0 | None | 7751 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9655 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5820 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| ermaozi | 0.25 | 6 | 18 | 24 |
| Surfboard-tg-mixed | 0.649 | 24 | 13 | 37 |
| ermaozi-get_subscribe | 0.75 | 3 | 1 | 4 |
| mheidari-all | 0.791 | 68 | 18 | 86 |
| Au1rxx-base64 | 0.916 | 285 | 26 | 311 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23222 | yes | 6.62 | 0 |
| SoliSpirit-all | 9655 | yes | 3.23 | 0 |
| Epodonios-all | 7751 | yes | 3.87 | 0 |
| Surfboard-tg-mixed | 7257 | yes | 5.87 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.33 | 0 |
| barry-far-vless | 6058 | yes | 1.1 | 0 |
| Surfboard-tg-vless | 5820 | yes | 4.38 | 0 |
| DeltaKronecker-all | 5267 | yes | 5.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 5173 | yes | 5.41 | 0 |
| mahdibland-V2RayAggregator | 4365 | yes | 3.15 | 0 |

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
| 204 | 36 |
| cn-block | 23 |
| geo | 13 |
| speed | 10 |
