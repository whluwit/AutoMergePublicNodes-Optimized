# AutoNodes 每日报告

生成时间：2026-07-16 02:12:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 75825 |
| 去重后节点数 | 22908 |
| TCP 可达数 | 3000 |
| 真测通过数 | 459 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22908 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 21.0 |
| geo | 1.4 |
| probe | 45.0 |
| real_test | 94.7 |
| tcp | 32.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 144 | 136 | 8 | 94.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 220 | 212 | 8 | 96.4% |
| vless | 292 | 65 | 227 | 22.3% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 89 |
| geo:TimeoutError | 79 |
| speed:TimeoutError | 37 |
| geo:ClientOSError | 10 |
| 204:TimeoutError | 8 |
| cn-block:TimeoutError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:parse | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4452 |
| ConnectionRefusedError | 657 |
| gaierror | 224 |
| OSError | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.983 | prefer | 91 | 0.912 | 5425 |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.963 | prefer | 92 | 0.967 | 149 |
| DeltaKronecker-all | 0.749 | prefer | 152 | 0.671 | 6421 |
| mheidari-all | 0.536 | observe | 318 | 0.456 | 16454 |
| xiaoji235-airport-v2ray-all | 0.382 | observe | 2 | 1.0 | 1757 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| Epodonios-all | 0.255 | observe | 0 | None | 6430 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.134 | downweight | 5 | 0.0 | 0 | 1519 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| 10ium-ScrapeCategorize-Vless | 0.17 | observe | 3 | 0.0 | 0 | 3759 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | nscl5-all | 0.134 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| nscl5-all | 0.0 | 0 | 5 | 5 |
| mheidari-all | 0.456 | 145 | 173 | 318 |
| DeltaKronecker-all | 0.671 | 102 | 50 | 152 |
| Surfboard-tg-mixed | 0.912 | 83 | 8 | 91 |
| Au1rxx-base64 | 0.967 | 89 | 3 | 92 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16454 | yes | 3.37 | 0 |
| SoliSpirit-all | 6740 | yes | 3.44 | 0 |
| Epodonios-all | 6430 | yes | 0.56 | 0 |
| DeltaKronecker-all | 6421 | yes | 3.64 | 0 |
| Surfboard-tg-mixed | 5425 | yes | 2.89 | 0 |
| mahdibland-V2RayAggregator | 5183 | yes | 0.27 | 0 |
| barry-far-vless | 4781 | yes | 2.33 | 0 |
| Surfboard-tg-vless | 4194 | yes | 2.16 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 2.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 3759 | yes | 1.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 126 |
| geo | 92 |
| 204 | 14 |
| cn-block | 12 |
