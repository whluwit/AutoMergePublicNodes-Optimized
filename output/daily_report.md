# AutoNodes 每日报告

生成时间：2026-07-14 19:15:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 81104 |
| 去重后节点数 | 24292 |
| TCP 可达数 | 3000 |
| 真测通过数 | 238 |
| verified 输出数 | 238 |
| global 输出数 | 247 |
| all 输出数 | 24292 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| generate | 34.2 |
| geo | 1.3 |
| probe | 43.3 |
| real_test | 79.1 |
| tcp | 32.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 5 | 5 | 0 | 100.0% |
| shadowsocks | 62 | 49 | 13 | 79.0% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 99 | 80 | 19 | 80.8% |
| vless | 181 | 62 | 119 | 34.3% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 51 |
| speed:ClientOSError | 44 |
| 204:TimeoutError | 15 |
| geo:ClientOSError | 13 |
| speed:TimeoutError | 8 |
| cn-block:TimeoutError | 8 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4596 |
| ConnectionRefusedError | 666 |
| gaierror | 255 |
| OSError | 202 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.756 | prefer | 69 | 0.681 | 18003 |
| DeltaKronecker-all | 0.736 | prefer | 59 | 0.661 | 7942 |
| Au1rxx-base64 | 0.59 | observe | 9 | 1.0 | 150 |
| Surfboard-tg-mixed | 0.575 | observe | 216 | 0.495 | 5662 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4019 |
| Epodonios-all | 0.255 | observe | 0 | None | 6538 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3965 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6320 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4339 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.495 | 107 | 109 | 216 |
| DeltaKronecker-all | 0.661 | 39 | 20 | 59 |
| mheidari-all | 0.681 | 47 | 22 | 69 |
| Au1rxx-base64 | 1.0 | 9 | 0 | 9 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18003 | yes | 2.85 | 0 |
| DeltaKronecker-all | 7942 | yes | 3.11 | 0 |
| Epodonios-all | 6538 | yes | 1.45 | 0 |
| SoliSpirit-all | 6320 | yes | 1.65 | 0 |
| Surfboard-tg-mixed | 5662 | yes | 2.25 | 0 |
| mahdibland-V2RayAggregator | 5187 | yes | 1.19 | 0 |
| barry-far-vless | 4852 | yes | 0.89 | 0 |
| Surfboard-tg-vless | 4339 | yes | 1.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 4019 | yes | 0.76 | 0 |
| MatinGhanbari-all-sub | 3965 | yes | 1.03 | 0 |

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
| geo | 64 |
| speed | 54 |
| 204 | 21 |
| cn-block | 13 |
