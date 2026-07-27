# AutoNodes 每日报告

生成时间：2026-07-27 02:35:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83767 |
| 去重后节点数 | 22035 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1022 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22035 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 24.5 |
| geo | 1.4 |
| probe | 69.7 |
| real_test | 210.3 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 6 | 0 | 100.0% |
| http | 78 | 78 | 0 | 100.0% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 156 | 141 | 15 | 90.4% |
| socks | 15 | 12 | 3 | 80.0% |
| trojan | 621 | 604 | 17 | 97.3% |
| vless | 522 | 170 | 352 | 32.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 160 |
| speed:ClientOSError | 85 |
| speed:TimeoutError | 58 |
| geo:ClientOSError | 38 |
| 204:ProxyError | 16 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 5 |
| 204:TimeoutError | 5 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4128 |
| ConnectionRefusedError | 728 |
| gaierror | 308 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 525 | 0.947 | 1478 |
| zhangkai | 0.991 | prefer | 78 | 1.0 | 86 |
| Surfboard-tg-mixed | 0.825 | prefer | 53 | 0.755 | 5558 |
| DeltaKronecker-all | 0.815 | prefer | 160 | 0.738 | 4320 |
| mheidari-all | 0.569 | observe | 575 | 0.489 | 19312 |
| tg-oneclickvpnkeys | 0.483 | observe | 6 | 1.0 | 149 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 3959 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6493 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3969 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.14 | downweight | 6 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.14 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 6 | 6 |
| mheidari-all | 0.489 | 281 | 294 | 575 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.738 | 118 | 42 | 160 |
| Surfboard-tg-mixed | 0.755 | 40 | 13 | 53 |
| Au1rxx-base64 | 0.947 | 497 | 28 | 525 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19312 | yes | 5.01 | 0 |
| Epodonios-all | 6493 | yes | 1.92 | 0 |
| SoliSpirit-all | 6295 | yes | 2.77 | 0 |
| Surfboard-tg-mixed | 5558 | yes | 2.99 | 0 |
| mahdibland-V2RayAggregator | 5003 | yes | 2.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 1.49 | 0 |
| barry-far-vless | 4841 | yes | 1.66 | 0 |
| Surfboard-tg-vless | 4334 | yes | 3.56 | 0 |
| DeltaKronecker-all | 4320 | yes | 5.18 | 0 |
| MatinGhanbari-all-sub | 3969 | yes | 2.47 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 198 |
| speed | 144 |
| 204 | 26 |
| cn-block | 20 |
