# AutoNodes 每日报告

生成时间：2026-06-23 14:44:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 77162 |
| 去重后节点数 | 22028 |
| TCP 可达数 | 3000 |
| 真测通过数 | 517 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22028 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 40.5 |
| geo | 1.5 |
| probe | 65.5 |
| real_test | 177.8 |
| tcp | 29.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 50 | 0 | 100.0% |
| hysteria2 | 1 | 1 | 0 | 100.0% |
| shadowsocks | 115 | 99 | 16 | 86.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 78 | 42 | 36 | 53.8% |
| vless | 768 | 321 | 447 | 41.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 255 |
| geo:ClientOSError | 102 |
| 204:TimeoutError | 40 |
| cn-block:TimeoutError | 35 |
| 204:ProxyError | 21 |
| speed:TimeoutError | 11 |
| 204:ClientOSError | 9 |
| geo:TimeoutError | 9 |
| cn-block:ProxyError | 7 |
| cn-block:ClientOSError | 5 |
| speed:ProxyError | 2 |
| geo:ProxyError | 2 |
| speed:ClientPayloadError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4220 |
| ConnectionRefusedError | 602 |
| gaierror | 129 |
| OSError | 105 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | prefer | 50 | 1.0 | 73 |
| Au1rxx-base64 | 0.802 | prefer | 72 | 0.806 | 124 |
| mheidari-all | 0.747 | prefer | 28 | 0.679 | 15591 |
| Surfboard-tg-mixed | 0.7 | observe | 219 | 0.621 | 5438 |
| DeltaKronecker-all | 0.474 | observe | 642 | 0.394 | 6437 |
| Epodonios-all | 0.255 | observe | 0 | None | 8099 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7501 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4204 |
| barry-far-vless | 0.255 | observe | 0 | None | 5009 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| 10ium-ScrapeCategorize-Vless | 0.17 | observe | 3 | 0.0 | 0 | 4576 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.394 | 253 | 389 | 642 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.621 | 136 | 83 | 219 |
| mheidari-all | 0.679 | 19 | 9 | 28 |
| Au1rxx-base64 | 0.806 | 58 | 14 | 72 |
| snakem982 | 1.0 | 50 | 0 | 50 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15591 | yes | 3.25 | 0 |
| Epodonios-all | 8099 | yes | 2.37 | 0 |
| SoliSpirit-all | 7501 | yes | 2.29 | 0 |
| DeltaKronecker-all | 6437 | yes | 3.62 | 0 |
| Surfboard-tg-mixed | 5438 | yes | 2.51 | 0 |
| barry-far-vless | 5009 | yes | 0.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 4576 | yes | 0.67 | 0 |
| mahdibland-V2RayAggregator | 4477 | yes | 1.49 | 0 |
| Surfboard-tg-vless | 4204 | yes | 3.39 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.18 | 0 |

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
| speed | 270 |
| geo | 113 |
| 204 | 70 |
| cn-block | 47 |
