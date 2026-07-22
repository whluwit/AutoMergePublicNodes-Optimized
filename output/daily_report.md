# AutoNodes 每日报告

生成时间：2026-07-22 19:11:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82193 |
| 去重后节点数 | 22546 |
| TCP 可达数 | 3000 |
| 真测通过数 | 454 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22546 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 44.9 |
| geo | 1.1 |
| probe | 55.4 |
| real_test | 106.1 |
| tcp | 31.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 35 | 35 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 17 | 10 | 7 | 58.8% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 356 | 320 | 36 | 89.9% |
| vless | 251 | 84 | 167 | 33.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 74 |
| speed:ClientOSError | 72 |
| cn-block:TimeoutError | 24 |
| 204:TimeoutError | 19 |
| geo:ClientOSError | 11 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 2 |
| speed:TimeoutError | 2 |
| 204:ServerDisconnectedError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 3963 |
| ConnectionRefusedError | 722 |
| gaierror | 388 |
| OSError | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.975 | prefer | 35 | 1.0 | 61 |
| mheidari-all | 0.815 | prefer | 349 | 0.736 | 19265 |
| DeltaKronecker-all | 0.703 | prefer | 67 | 0.627 | 5212 |
| Surfboard-tg-mixed | 0.634 | observe | 211 | 0.555 | 5383 |
| Au1rxx-base64 | 0.329 | observe | 2 | 1.0 | 432 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 4246 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4613 |
| Epodonios-all | 0.255 | observe | 0 | None | 6453 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6975 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.555 | 117 | 94 | 211 |
| DeltaKronecker-all | 0.627 | 42 | 25 | 67 |
| mheidari-all | 0.736 | 257 | 92 | 349 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 35 | 0 | 35 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19265 | yes | 3.58 | 0 |
| SoliSpirit-all | 6975 | yes | 3.7 | 0 |
| Epodonios-all | 6455 | yes | 3.77 | 0 |
| Surfboard-tg-mixed | 5383 | yes | 2.3 | 0 |
| DeltaKronecker-all | 5212 | yes | 4.19 | 0 |
| mahdibland-V2RayAggregator | 4954 | yes | 2.39 | 0 |
| barry-far-vless | 4830 | yes | 1.38 | 0 |
| 10ium-ScrapeCategorize-Vless | 4613 | yes | 1.65 | 0 |
| xiaoji235-airport-v2ray-all | 4246 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 4231 | yes | 2.59 | 0 |

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
| geo | 86 |
| speed | 75 |
| cn-block | 30 |
| 204 | 23 |
