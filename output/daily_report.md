# AutoNodes 每日报告

生成时间：2026-07-16 19:07:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79647 |
| 去重后节点数 | 24641 |
| TCP 可达数 | 3000 |
| 真测通过数 | 382 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24641 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 37.2 |
| geo | 1.5 |
| probe | 48.8 |
| real_test | 103.4 |
| tcp | 33.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 106 | 93 | 13 | 87.7% |
| socks | 9 | 5 | 4 | 55.6% |
| trojan | 260 | 232 | 28 | 89.2% |
| vless | 123 | 11 | 112 | 8.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 61 |
| speed:ClientOSError | 50 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 10 |
| 204:ProxyError | 4 |
| speed:TimeoutError | 4 |
| geo:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4441 |
| ConnectionRefusedError | 678 |
| gaierror | 298 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.915 | prefer | 108 | 0.917 | 149 |
| DeltaKronecker-all | 0.799 | prefer | 226 | 0.721 | 8462 |
| Surfboard-tg-mixed | 0.58 | observe | 156 | 0.5 | 5554 |
| xiaoji235-airport-v2ray-all | 0.325 | observe | 1 | 1.0 | 1757 |
| mheidari-all | 0.324 | observe | 8 | 0.375 | 16694 |
| nscl5-all | 0.316 | observe | 1 | 1.0 | 1519 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4470 |
| Epodonios-all | 0.255 | observe | 0 | None | 6586 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.375 | 3 | 5 | 8 |
| Surfboard-tg-mixed | 0.5 | 78 | 78 | 156 |
| DeltaKronecker-all | 0.721 | 163 | 63 | 226 |
| Au1rxx-base64 | 0.917 | 99 | 9 | 108 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16694 | yes | 3.26 | 0 |
| DeltaKronecker-all | 8462 | yes | 3.54 | 0 |
| SoliSpirit-all | 6877 | yes | 2.03 | 0 |
| Epodonios-all | 6586 | yes | 1.75 | 0 |
| Surfboard-tg-mixed | 5554 | yes | 1.59 | 0 |
| mahdibland-V2RayAggregator | 5260 | yes | 0.77 | 0 |
| barry-far-vless | 4954 | yes | 2.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 4470 | yes | 1.81 | 0 |
| Surfboard-tg-vless | 4319 | yes | 2.19 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 2.1 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.089 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 65 |
| speed | 54 |
| 204 | 25 |
| cn-block | 13 |
