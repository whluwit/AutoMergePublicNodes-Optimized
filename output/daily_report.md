# AutoNodes 每日报告

生成时间：2026-07-18 19:03:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 88176 |
| 去重后节点数 | 23077 |
| TCP 可达数 | 3000 |
| 真测通过数 | 810 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23077 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 40.9 |
| geo | 1.2 |
| probe | 72.2 |
| real_test | 229.3 |
| tcp | 32.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 37 | 37 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 144 | 110 | 34 | 76.4% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 610 | 561 | 49 | 92.0% |
| vless | 471 | 96 | 375 | 20.4% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 212 |
| speed:ClientOSError | 84 |
| cn-block:TimeoutError | 53 |
| geo:ClientOSError | 46 |
| 204:TimeoutError | 30 |
| speed:TimeoutError | 12 |
| 204:ClientOSError | 8 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4191 |
| ConnectionRefusedError | 694 |
| gaierror | 323 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.817 | prefer | 120 | 0.817 | 150 |
| Surfboard-tg-mixed | 0.797 | prefer | 164 | 0.72 | 5713 |
| mheidari-all | 0.713 | prefer | 867 | 0.633 | 19946 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 4321 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 198 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4371 |
| Epodonios-all | 0.255 | observe | 0 | None | 6898 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7086 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| DeltaKronecker-all | 0.143 | downweight | 78 | 0.051 | 0 | 9946 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.143 | 78 | 0.051 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.051 | 4 | 74 | 78 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.633 | 549 | 318 | 867 |
| Surfboard-tg-mixed | 0.72 | 118 | 46 | 164 |
| Au1rxx-base64 | 0.817 | 98 | 22 | 120 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19946 | yes | 3.63 | 0 |
| DeltaKronecker-all | 9946 | yes | 3.42 | 0 |
| SoliSpirit-all | 7086 | yes | 3.17 | 0 |
| Epodonios-all | 6898 | yes | 1.47 | 0 |
| Surfboard-tg-mixed | 5713 | yes | 2.33 | 0 |
| mahdibland-V2RayAggregator | 5340 | yes | 1.26 | 0 |
| barry-far-vless | 4962 | yes | 1.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4371 | yes | 1.53 | 0 |
| Surfboard-tg-vless | 4332 | yes | 1.81 | 0 |
| xiaoji235-airport-v2ray-all | 4321 | yes | 1.89 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 261 |
| speed | 98 |
| cn-block | 62 |
| 204 | 41 |
