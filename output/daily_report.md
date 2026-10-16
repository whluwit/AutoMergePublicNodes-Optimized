# AutoNodes 每日报告

生成时间：2026-10-16 10:45:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99210 |
| 去重后节点数 | 27570 |
| TCP 可达数 | 3000 |
| 真测通过数 | 369 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27570 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 107.2 |
| geo | 1.5 |
| probe | 292.8 |
| real_test | 278.1 |
| tcp | 48.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 3 | 2 | 60.0% |
| http | 93 | 48 | 45 | 51.6% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 74 | 63 | 11 | 85.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 47 | 31 | 16 | 66.0% |
| vless | 299 | 208 | 91 | 69.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 46 |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 21 |
| speed:TimeoutError | 20 |
| geo:TimeoutError | 12 |
| speed:ClientOSError | 11 |
| 204:ClientOSError | 8 |
| geo:ClientOSError | 8 |
| cn-block:ClientOSError | 7 |
| 204:ProxyConnectionError | 5 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| cn-block:status | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6838 |
| ConnectionRefusedError | 1047 |
| OSError | 240 |
| gaierror | 240 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.849 | prefer | 397 | 0.771 | 1990 |
| ermaozi | 0.538 | observe | 92 | 0.511 | 693 |
| mheidari-all | 0.397 | observe | 12 | 0.417 | 23871 |
| Surfboard-tg-mixed | 0.344 | observe | 12 | 0.333 | 7054 |
| DeltaKronecker-all | 0.314 | observe | 18 | 0.222 | 4946 |
| ermaozi-get_subscribe | 0.291 | observe | 3 | 0.667 | 574 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 79 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7568 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.222 | 4 | 14 | 18 |
| Surfboard-tg-mixed | 0.333 | 4 | 8 | 12 |
| mheidari-all | 0.417 | 5 | 7 | 12 |
| ermaozi | 0.511 | 47 | 45 | 92 |
| ermaozi-get_subscribe | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.771 | 306 | 91 | 397 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23871 | yes | 6.18 | 0 |
| SoliSpirit-all | 10065 | yes | 6.34 | 0 |
| Epodonios-all | 7568 | yes | 6.38 | 0 |
| Surfboard-tg-mixed | 7054 | yes | 4.5 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.29 | 0 |
| barry-far-vless | 5827 | yes | 2.16 | 0 |
| Surfboard-tg-vless | 5573 | yes | 4.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 4.51 | 0 |
| DeltaKronecker-all | 4946 | yes | 7.14 | 0 |
| mahdibland-V2RayAggregator | 4265 | yes | 3.84 | 0 |

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
| 204 | 83 |
| speed | 33 |
| cn-block | 32 |
| geo | 20 |
