# AutoNodes 每日报告

生成时间：2026-07-29 19:11:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79443 |
| 去重后节点数 | 22697 |
| TCP 可达数 | 3000 |
| 真测通过数 | 497 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22697 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 42.2 |
| geo | 1.4 |
| probe | 57.1 |
| real_test | 135.2 |
| tcp | 32.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 70 | 70 | 0 | 100.0% |
| hysteria2 | 13 | 9 | 4 | 69.2% |
| shadowsocks | 188 | 151 | 37 | 80.3% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 47 | 39 | 8 | 83.0% |
| vless | 366 | 226 | 140 | 61.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 50 |
| 204:TimeoutError | 30 |
| cn-block:TimeoutError | 30 |
| speed:TimeoutError | 27 |
| geo:ClientOSError | 17 |
| 204:ProxyError | 12 |
| 204:ClientOSError | 11 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4560 |
| ConnectionRefusedError | 732 |
| OSError | 222 |
| gaierror | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 70 | 1.0 | 84 |
| Au1rxx-base64 | 0.826 | prefer | 276 | 0.772 | 1415 |
| DeltaKronecker-all | 0.747 | prefer | 214 | 0.668 | 5519 |
| Surfboard-tg-mixed | 0.64 | observe | 123 | 0.561 | 5754 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| mheidari-all | 0.287 | observe | 2 | 0.5 | 16105 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5118 |
| Epodonios-all | 0.255 | observe | 0 | None | 6491 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6737 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.561 | 69 | 54 | 123 |
| DeltaKronecker-all | 0.668 | 143 | 71 | 214 |
| Au1rxx-base64 | 0.772 | 213 | 63 | 276 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 70 | 0 | 70 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16105 | yes | 4.99 | 0 |
| SoliSpirit-all | 6737 | yes | 3.1 | 0 |
| Epodonios-all | 6491 | yes | 2.76 | 0 |
| Surfboard-tg-mixed | 5754 | yes | 4.57 | 0 |
| DeltaKronecker-all | 5519 | yes | 4.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 5118 | yes | 2.07 | 0 |
| mahdibland-V2RayAggregator | 5076 | yes | 2.36 | 0 |
| barry-far-vless | 4922 | yes | 1.82 | 0 |
| Surfboard-tg-vless | 4513 | yes | 3.6 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 1.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 67 |
| 204 | 53 |
| cn-block | 36 |
| speed | 34 |
