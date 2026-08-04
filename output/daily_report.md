# AutoNodes 每日报告

生成时间：2026-08-04 08:34:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 85537 |
| 去重后节点数 | 24236 |
| TCP 可达数 | 3000 |
| 真测通过数 | 574 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24236 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 24.0 |
| geo | 1.3 |
| probe | 59.8 |
| real_test | 131.9 |
| tcp | 36.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 67 | 0 | 100.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 141 | 119 | 22 | 84.4% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 136 | 118 | 18 | 86.8% |
| vless | 446 | 249 | 197 | 55.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 105 |
| speed:TimeoutError | 38 |
| 204:TimeoutError | 22 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 13 |
| 204:ClientOSError | 12 |
| 204:ProxyError | 11 |
| speed:ClientOSError | 11 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4634 |
| ConnectionRefusedError | 796 |
| gaierror | 311 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 67 | 1.0 | 92 |
| Au1rxx-base64 | 0.836 | prefer | 600 | 0.77 | 1672 |
| mheidari-all | 0.465 | observe | 24 | 0.375 | 20242 |
| DeltaKronecker-all | 0.436 | observe | 43 | 0.349 | 5788 |
| Surfboard-tg-mixed | 0.336 | observe | 76 | 0.25 | 5211 |
| SoliSpirit-all | 0.335 | observe | 1 | 1.0 | 6811 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5251 |
| Epodonios-all | 0.255 | observe | 0 | None | 5819 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.25 | 19 | 57 | 76 |
| DeltaKronecker-all | 0.349 | 15 | 28 | 43 |
| mheidari-all | 0.375 | 9 | 15 | 24 |
| Au1rxx-base64 | 0.77 | 462 | 138 | 600 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| SoliSpirit-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 67 | 0 | 67 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20242 | yes | 3.35 | 0 |
| SoliSpirit-all | 6811 | yes | 3.38 | 0 |
| Epodonios-all | 5819 | yes | 3.52 | 0 |
| DeltaKronecker-all | 5788 | yes | 3.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 5251 | yes | 1.2 | 0 |
| Surfboard-tg-mixed | 5211 | yes | 2.32 | 0 |
| xiaoji235-airport-v2ray-all | 5127 | yes | 1.58 | 0 |
| mahdibland-V2RayAggregator | 5110 | yes | 2.0 | 0 |
| barry-far-vless | 4536 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 4191 | yes | 2.2 | 0 |

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
| geo | 126 |
| speed | 49 |
| 204 | 45 |
| cn-block | 20 |
