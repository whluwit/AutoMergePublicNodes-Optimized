# AutoNodes 每日报告

生成时间：2026-07-13 19:22:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 77324 |
| 去重后节点数 | 23912 |
| TCP 可达数 | 3000 |
| 真测通过数 | 150 |
| verified 输出数 | 150 |
| global 输出数 | 160 |
| all 输出数 | 23912 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 34.5 |
| geo | 1.5 |
| probe | 45.1 |
| real_test | 52.5 |
| tcp | 32.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 75 | 50 | 25 | 66.7% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 70 | 53 | 17 | 75.7% |
| vless | 43 | 5 | 38 | 11.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 21 |
| speed:ClientOSError | 16 |
| 204:TimeoutError | 12 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 6 |
| speed:TimeoutError | 4 |
| geo:ClientOSError | 3 |
| 204:ProxyError | 2 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4522 |
| ConnectionRefusedError | 664 |
| gaierror | 261 |
| OSError | 191 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.722 | prefer | 79 | 0.646 | 5561 |
| DeltaKronecker-all | 0.627 | observe | 62 | 0.548 | 7926 |
| mheidari-all | 0.617 | observe | 52 | 0.538 | 16297 |
| Au1rxx-base64 | 0.259 | observe | 1 | 1.0 | 91 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3897 |
| Epodonios-all | 0.255 | observe | 0 | None | 6496 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6673 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4279 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.538 | 28 | 24 | 52 |
| DeltaKronecker-all | 0.548 | 34 | 28 | 62 |
| Surfboard-tg-mixed | 0.646 | 51 | 28 | 79 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16297 | yes | 3.91 | 0 |
| DeltaKronecker-all | 7926 | yes | 4.17 | 0 |
| SoliSpirit-all | 6673 | yes | 2.53 | 0 |
| Epodonios-all | 6496 | yes | 2.07 | 0 |
| Surfboard-tg-mixed | 5561 | yes | 2.73 | 0 |
| mahdibland-V2RayAggregator | 5454 | yes | 1.6 | 0 |
| barry-far-vless | 4810 | yes | 2.27 | 0 |
| Surfboard-tg-vless | 4279 | yes | 2.44 | 0 |
| MatinGhanbari-all-sub | 3976 | yes | 1.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 3897 | yes | 1.6 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 24 |
| speed | 20 |
| 204 | 20 |
| cn-block | 18 |
