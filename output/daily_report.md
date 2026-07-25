# AutoNodes 每日报告

生成时间：2026-07-25 19:06:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 80407 |
| 去重后节点数 | 22481 |
| TCP 可达数 | 3000 |
| 真测通过数 | 678 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22481 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 27.6 |
| geo | 1.3 |
| probe | 67.6 |
| real_test | 168.8 |
| tcp | 31.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 77 | 76 | 1 | 98.7% |
| hysteria2 | 8 | 7 | 1 | 87.5% |
| shadowsocks | 121 | 88 | 33 | 72.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 475 | 420 | 55 | 88.4% |
| vless | 205 | 86 | 119 | 42.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 66 |
| 204:TimeoutError | 44 |
| speed:ClientOSError | 35 |
| cn-block:TimeoutError | 33 |
| speed:TimeoutError | 8 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 7 |
| 204:ProxyError | 5 |
| geo:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4087 |
| ConnectionRefusedError | 703 |
| gaierror | 329 |
| OSError | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.979 | prefer | 77 | 0.987 | 119 |
| Au1rxx-base64 | 0.894 | prefer | 409 | 0.853 | 1064 |
| Surfboard-tg-mixed | 0.825 | prefer | 53 | 0.755 | 5471 |
| mheidari-all | 0.747 | prefer | 262 | 0.668 | 17275 |
| DeltaKronecker-all | 0.517 | observe | 85 | 0.435 | 5838 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4879 |
| Epodonios-all | 0.255 | observe | 0 | None | 6622 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6579 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 183 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.435 | 37 | 48 | 85 |
| mheidari-all | 0.668 | 175 | 87 | 262 |
| Surfboard-tg-mixed | 0.755 | 40 | 13 | 53 |
| Au1rxx-base64 | 0.853 | 349 | 60 | 409 |
| zhangkai | 0.987 | 76 | 1 | 77 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17275 | yes | 4.07 | 0 |
| Epodonios-all | 6622 | yes | 2.23 | 0 |
| SoliSpirit-all | 6579 | yes | 2.29 | 0 |
| DeltaKronecker-all | 5838 | yes | 4.65 | 0 |
| Surfboard-tg-mixed | 5471 | yes | 2.97 | 0 |
| mahdibland-V2RayAggregator | 4980 | yes | 2.61 | 0 |
| barry-far-vless | 4959 | yes | 1.13 | 0 |
| 10ium-ScrapeCategorize-Vless | 4879 | yes | 1.38 | 0 |
| Surfboard-tg-vless | 4269 | yes | 2.43 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.47 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 69 |
| 204 | 56 |
| speed | 44 |
| cn-block | 42 |
