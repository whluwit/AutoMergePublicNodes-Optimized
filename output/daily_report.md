# AutoNodes 每日报告

生成时间：2026-07-22 02:14:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 81716 |
| 去重后节点数 | 22508 |
| TCP 可达数 | 3000 |
| 真测通过数 | 626 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22508 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 40.9 |
| geo | 1.3 |
| probe | 60.7 |
| real_test | 170.6 |
| tcp | 30.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 150 | 137 | 13 | 91.3% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 386 | 312 | 74 | 80.8% |
| vless | 645 | 135 | 510 | 20.9% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 228 |
| speed:ClientOSError | 165 |
| cn-block:TimeoutError | 66 |
| geo:ClientOSError | 60 |
| speed:TimeoutError | 51 |
| 204:TimeoutError | 12 |
| cn-block:ClientOSError | 10 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 3775 |
| ConnectionRefusedError | 661 |
| gaierror | 371 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.75 | prefer | 211 | 0.735 | 432 |
| Surfboard-tg-mixed | 0.743 | prefer | 289 | 0.664 | 5420 |
| mheidari-all | 0.453 | observe | 598 | 0.373 | 18723 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 4246 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4482 |
| DeltaKronecker-all | 0.273 | observe | 86 | 0.186 | 5415 |
| Epodonios-all | 0.255 | observe | 0 | None | 6487 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3967 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7011 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.186 | 16 | 70 | 86 |
| mheidari-all | 0.373 | 223 | 375 | 598 |
| Surfboard-tg-mixed | 0.664 | 192 | 97 | 289 |
| Au1rxx-base64 | 0.735 | 155 | 56 | 211 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18723 | yes | 3.25 | 0 |
| SoliSpirit-all | 7011 | yes | 2.42 | 0 |
| Epodonios-all | 6487 | yes | 1.31 | 0 |
| Surfboard-tg-mixed | 5420 | yes | 2.07 | 0 |
| DeltaKronecker-all | 5415 | yes | 3.22 | 0 |
| mahdibland-V2RayAggregator | 5204 | yes | 1.4 | 0 |
| barry-far-vless | 4665 | yes | 1.14 | 0 |
| 10ium-ScrapeCategorize-Vless | 4482 | yes | 1.3 | 0 |
| xiaoji235-airport-v2ray-all | 4246 | yes | 1.1 | 0 |
| Surfboard-tg-vless | 4054 | yes | 2.57 | 0 |

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
| geo | 288 |
| speed | 216 |
| cn-block | 78 |
| 204 | 19 |
