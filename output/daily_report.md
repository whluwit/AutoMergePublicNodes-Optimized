# AutoNodes 每日报告

生成时间：2026-07-29 02:12:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 76519 |
| 去重后节点数 | 21563 |
| TCP 可达数 | 3000 |
| 真测通过数 | 670 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21563 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 29.8 |
| geo | 1.4 |
| probe | 55.1 |
| real_test | 143.5 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 64 | 64 | 0 | 100.0% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 212 | 192 | 20 | 90.6% |
| socks | 7 | 6 | 1 | 85.7% |
| trojan | 109 | 92 | 17 | 84.4% |
| vless | 471 | 301 | 170 | 63.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 74 |
| cn-block:TimeoutError | 35 |
| geo:ClientOSError | 30 |
| speed:TimeoutError | 27 |
| speed:ClientOSError | 23 |
| 204:TimeoutError | 9 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| 204:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4138 |
| ConnectionRefusedError | 731 |
| gaierror | 313 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 64 | 1.0 | 173 |
| Au1rxx-base64 | 0.972 | prefer | 305 | 0.928 | 1167 |
| DeltaKronecker-all | 0.803 | prefer | 262 | 0.725 | 4038 |
| Surfboard-tg-mixed | 0.687 | observe | 176 | 0.608 | 5746 |
| mheidari-all | 0.474 | observe | 64 | 0.391 | 17232 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6752 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6316 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4508 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.391 | 25 | 39 | 64 |
| Surfboard-tg-mixed | 0.608 | 107 | 69 | 176 |
| DeltaKronecker-all | 0.725 | 190 | 72 | 262 |
| Au1rxx-base64 | 0.928 | 283 | 22 | 305 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 64 | 0 | 64 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17232 | yes | 4.47 | 0 |
| Epodonios-all | 6752 | yes | 2.67 | 0 |
| SoliSpirit-all | 6316 | yes | 2.4 | 0 |
| Surfboard-tg-mixed | 5746 | yes | 3.59 | 0 |
| mahdibland-V2RayAggregator | 5059 | yes | 1.62 | 0 |
| barry-far-vless | 5026 | yes | 1.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 4972 | yes | 1.63 | 0 |
| Surfboard-tg-vless | 4508 | yes | 3.41 | 0 |
| DeltaKronecker-all | 4038 | yes | 4.62 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 2.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 105 |
| speed | 50 |
| cn-block | 39 |
| 204 | 14 |
