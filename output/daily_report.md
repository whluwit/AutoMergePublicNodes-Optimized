# AutoNodes 每日报告

生成时间：2026-08-20 12:43:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 94200 |
| 去重后节点数 | 25172 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1034 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25172 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 34.3 |
| geo | 0.6 |
| probe | 66.7 |
| real_test | 190.8 |
| tcp | 39.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 73 | 69 | 4 | 94.5% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 553 | 548 | 5 | 99.1% |
| vless | 407 | 284 | 123 | 69.8% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 48 |
| 204:TimeoutError | 21 |
| geo:TimeoutError | 21 |
| speed:TimeoutError | 11 |
| cn-block:TimeoutError | 9 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| 204:ProxyError | 4 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4874 |
| ConnectionRefusedError | 967 |
| gaierror | 605 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 565 | 0.979 | 1789 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| mheidari-all | 0.847 | prefer | 458 | 0.769 | 21209 |
| Surfboard-tg-mixed | 0.819 | prefer | 21 | 0.762 | 6433 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| Epodonios-all | 0.255 | observe | 0 | None | 7150 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3991 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7279 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5109 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| DeltaKronecker-all | 0.136 | downweight | 10 | 0.0 | 0 | 6781 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.136 | 10 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 10 | 10 |
| Surfboard-tg-mixed | 0.762 | 16 | 5 | 21 |
| mheidari-all | 0.769 | 352 | 106 | 458 |
| Au1rxx-base64 | 0.979 | 553 | 12 | 565 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21209 | yes | 3.63 | 0 |
| SoliSpirit-all | 7279 | yes | 3.2 | 0 |
| Epodonios-all | 7150 | yes | 3.2 | 0 |
| DeltaKronecker-all | 6781 | yes | 3.98 | 0 |
| Surfboard-tg-mixed | 6433 | yes | 2.54 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.13 | 0 |
| barry-far-vless | 5434 | yes | 1.3 | 0 |
| Surfboard-tg-vless | 5109 | yes | 2.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 1.66 | 0 |
| mahdibland-V2RayAggregator | 4586 | yes | 0.12 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 71 |
| 204 | 30 |
| speed | 18 |
| cn-block | 17 |
