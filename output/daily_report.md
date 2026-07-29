# AutoNodes 每日报告

生成时间：2026-07-29 14:03:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78674 |
| 去重后节点数 | 22641 |
| TCP 可达数 | 3000 |
| 真测通过数 | 494 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22641 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 29.5 |
| geo | 1.4 |
| probe | 57.7 |
| real_test | 142.8 |
| tcp | 32.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 70 | 70 | 0 | 100.0% |
| hysteria2 | 15 | 12 | 3 | 80.0% |
| shadowsocks | 186 | 153 | 33 | 82.3% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 48 | 38 | 10 | 79.2% |
| vless | 381 | 221 | 160 | 58.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 73 |
| speed:TimeoutError | 36 |
| cn-block:TimeoutError | 33 |
| 204:TimeoutError | 22 |
| geo:ClientOSError | 16 |
| 204:ProxyError | 9 |
| speed:ClientOSError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4351 |
| ConnectionRefusedError | 738 |
| gaierror | 302 |
| OSError | 223 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 70 | 1.0 | 84 |
| Au1rxx-base64 | 0.874 | prefer | 277 | 0.823 | 1337 |
| Surfboard-tg-mixed | 0.642 | observe | 142 | 0.563 | 5713 |
| DeltaKronecker-all | 0.618 | observe | 193 | 0.539 | 5519 |
| ninja-vless | 0.521 | observe | 7 | 0.857 | 1791 |
| mheidari-all | 0.372 | observe | 9 | 0.444 | 16071 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 180 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5118 |
| Epodonios-all | 0.255 | observe | 0 | None | 6469 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.444 | 4 | 5 | 9 |
| DeltaKronecker-all | 0.539 | 104 | 89 | 193 |
| Surfboard-tg-mixed | 0.563 | 80 | 62 | 142 |
| Au1rxx-base64 | 0.823 | 228 | 49 | 277 |
| ninja-vless | 0.857 | 6 | 1 | 7 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 70 | 0 | 70 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16071 | yes | 3.45 | 0 |
| Epodonios-all | 6469 | yes | 1.66 | 0 |
| SoliSpirit-all | 6220 | yes | 2.58 | 0 |
| Surfboard-tg-mixed | 5713 | yes | 2.86 | 0 |
| DeltaKronecker-all | 5519 | yes | 3.13 | 0 |
| 10ium-ScrapeCategorize-Vless | 5118 | yes | 1.08 | 0 |
| mahdibland-V2RayAggregator | 5089 | yes | 1.94 | 0 |
| barry-far-vless | 4964 | yes | 0.89 | 0 |
| Surfboard-tg-vless | 4553 | yes | 2.72 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.41 | 0 |

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
| geo | 91 |
| speed | 44 |
| cn-block | 38 |
| 204 | 36 |
