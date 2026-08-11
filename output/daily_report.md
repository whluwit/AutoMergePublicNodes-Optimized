# AutoNodes 每日报告

生成时间：2026-08-11 19:00:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 81050 |
| 去重后节点数 | 23063 |
| TCP 可达数 | 3000 |
| 真测通过数 | 552 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23063 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 28.2 |
| geo | 1.4 |
| probe | 55.9 |
| real_test | 123.1 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 125 | 125 | 0 | 100.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 151 | 140 | 11 | 92.7% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 118 | 112 | 6 | 94.9% |
| vless | 273 | 153 | 120 | 56.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 43 |
| 204:TimeoutError | 27 |
| speed:TimeoutError | 18 |
| geo:ClientOSError | 16 |
| cn-block:TimeoutError | 12 |
| speed:ClientOSError | 11 |
| geo:TimeoutError | 9 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4508 |
| ConnectionRefusedError | 784 |
| gaierror | 358 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.998 | prefer | 125 | 1.0 | 159 |
| Au1rxx-base64 | 0.947 | prefer | 370 | 0.889 | 1503 |
| DeltaKronecker-all | 0.564 | observe | 184 | 0.484 | 5522 |
| Surfboard-tg-mixed | 0.489 | observe | 9 | 0.667 | 6123 |
| mheidari-all | 0.438 | observe | 3 | 1.0 | 16649 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5419 |
| Epodonios-all | 0.255 | observe | 0 | None | 6762 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7634 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5008 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.484 | 89 | 95 | 184 |
| Surfboard-tg-mixed | 0.667 | 6 | 3 | 9 |
| Au1rxx-base64 | 0.889 | 329 | 41 | 370 |
| mheidari-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 125 | 0 | 125 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16649 | yes | 4.17 | 0 |
| SoliSpirit-all | 7634 | yes | 2.1 | 0 |
| Epodonios-all | 6762 | yes | 1.9 | 0 |
| Surfboard-tg-mixed | 6123 | yes | 2.69 | 0 |
| DeltaKronecker-all | 5522 | yes | 4.16 | 0 |
| 10ium-ScrapeCategorize-Vless | 5419 | yes | 1.54 | 0 |
| barry-far-vless | 5313 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 2.76 | 0 |
| Surfboard-tg-vless | 5008 | yes | 3.03 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.79 | 0 |

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
| 204 | 71 |
| speed | 29 |
| geo | 26 |
| cn-block | 15 |
