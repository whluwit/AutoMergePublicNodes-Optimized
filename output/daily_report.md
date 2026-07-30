# AutoNodes 每日报告

生成时间：2026-07-30 02:04:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 77741 |
| 去重后节点数 | 22691 |
| TCP 可达数 | 3000 |
| 真测通过数 | 841 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22691 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 30.4 |
| geo | 1.5 |
| probe | 79.8 |
| real_test | 256.0 |
| tcp | 32.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 70 | 70 | 0 | 100.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 225 | 207 | 18 | 92.0% |
| socks | 16 | 14 | 2 | 87.5% |
| trojan | 50 | 48 | 2 | 96.0% |
| vless | 1233 | 486 | 747 | 39.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 331 |
| speed:ClientOSError | 160 |
| cn-block:TimeoutError | 100 |
| geo:ClientOSError | 92 |
| speed:TimeoutError | 56 |
| 204:ProxyError | 9 |
| 204:ClientOSError | 7 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4563 |
| ConnectionRefusedError | 735 |
| OSError | 223 |
| gaierror | 203 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 70 | 1.0 | 84 |
| Au1rxx-base64 | 0.983 | prefer | 293 | 0.935 | 1269 |
| Surfboard-tg-mixed | 0.792 | prefer | 17 | 0.824 | 5390 |
| DeltaKronecker-all | 0.476 | observe | 1209 | 0.395 | 5519 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5118 |
| xiaoji235-airport-v2ray-all | 0.282 | observe | 2 | 0.5 | 1861 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6124 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6754 |

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
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.234 | 13 | 0.154 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.154 | 2 | 11 | 13 |
| DeltaKronecker-all | 0.395 | 478 | 731 | 1209 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.824 | 14 | 3 | 17 |
| Au1rxx-base64 | 0.935 | 274 | 19 | 293 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16276 | yes | 4.26 | 0 |
| SoliSpirit-all | 6754 | yes | 3.13 | 0 |
| Epodonios-all | 6124 | yes | 2.05 | 0 |
| DeltaKronecker-all | 5519 | yes | 4.33 | 0 |
| Surfboard-tg-mixed | 5390 | yes | 3.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 5118 | yes | 2.59 | 0 |
| mahdibland-V2RayAggregator | 5076 | yes | 2.27 | 0 |
| barry-far-vless | 4688 | yes | 0.62 | 0 |
| Surfboard-tg-vless | 4279 | yes | 3.36 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.36 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 424 |
| speed | 216 |
| cn-block | 107 |
| 204 | 23 |
