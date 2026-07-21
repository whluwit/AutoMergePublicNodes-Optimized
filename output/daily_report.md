# AutoNodes 每日报告

生成时间：2026-07-21 19:18:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 82316 |
| 去重后节点数 | 22946 |
| TCP 可达数 | 3000 |
| 真测通过数 | 520 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22946 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 45.3 |
| geo | 1.3 |
| probe | 65.8 |
| real_test | 142.3 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 130 | 97 | 33 | 74.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 346 | 309 | 37 | 89.3% |
| vless | 334 | 71 | 263 | 21.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 137 |
| geo:TimeoutError | 89 |
| cn-block:TimeoutError | 40 |
| 204:TimeoutError | 36 |
| geo:ClientOSError | 9 |
| speed:TimeoutError | 9 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4238 |
| ConnectionRefusedError | 681 |
| gaierror | 283 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.857 | prefer | 92 | 0.783 | 5389 |
| Au1rxx-base64 | 0.785 | prefer | 196 | 0.77 | 432 |
| mheidari-all | 0.599 | observe | 497 | 0.519 | 19482 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 4304 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4482 |
| Epodonios-all | 0.255 | observe | 0 | None | 6464 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6710 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| DeltaKronecker-all | 0.112 | downweight | 29 | 0.0 | 0 | 5415 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.112 | 29 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 29 | 29 |
| mheidari-all | 0.519 | 258 | 239 | 497 |
| Au1rxx-base64 | 0.77 | 151 | 45 | 196 |
| Surfboard-tg-mixed | 0.783 | 72 | 20 | 92 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19482 | yes | 3.24 | 0 |
| SoliSpirit-all | 6710 | yes | 2.26 | 0 |
| Epodonios-all | 6464 | yes | 2.74 | 0 |
| DeltaKronecker-all | 5415 | yes | 2.92 | 0 |
| Surfboard-tg-mixed | 5389 | yes | 2.44 | 0 |
| mahdibland-V2RayAggregator | 5204 | yes | 0.2 | 0 |
| barry-far-vless | 4788 | yes | 0.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 4482 | yes | 0.82 | 0 |
| xiaoji235-airport-v2ray-all | 4304 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 4172 | yes | 1.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 146 |
| geo | 99 |
| 204 | 46 |
| cn-block | 43 |
