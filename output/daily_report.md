# AutoNodes 每日报告

生成时间：2026-08-08 18:33:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83395 |
| 去重后节点数 | 23589 |
| TCP 可达数 | 3000 |
| 真测通过数 | 426 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23589 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| generate | 39.4 |
| geo | 1.3 |
| probe | 49.4 |
| real_test | 98.9 |
| tcp | 35.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 23 | 21 | 2 | 91.3% |
| shadowsocks | 147 | 136 | 11 | 92.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 135 | 128 | 7 | 94.8% |
| vless | 231 | 118 | 113 | 51.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 37 |
| 204:TimeoutError | 23 |
| geo:ClientOSError | 19 |
| cn-block:TimeoutError | 14 |
| speed:TimeoutError | 13 |
| geo:TimeoutError | 7 |
| speed:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4960 |
| ConnectionRefusedError | 820 |
| gaierror | 311 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 345 | 0.948 | 1540 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.489 | observe | 9 | 0.667 | 6588 |
| mheidari-all | 0.48 | observe | 4 | 1.0 | 17642 |
| DeltaKronecker-all | 0.463 | observe | 181 | 0.381 | 5347 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5450 |
| Epodonios-all | 0.255 | observe | 0 | None | 7201 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7604 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5351 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.381 | 69 | 112 | 181 |
| Surfboard-tg-mixed | 0.667 | 6 | 3 | 9 |
| Au1rxx-base64 | 0.948 | 327 | 18 | 345 |
| mheidari-all | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17642 | yes | 2.84 | 0 |
| SoliSpirit-all | 7604 | yes | 2.18 | 0 |
| Epodonios-all | 7201 | yes | 2.97 | 0 |
| Surfboard-tg-mixed | 6588 | yes | 2.32 | 0 |
| barry-far-vless | 5666 | yes | 0.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5450 | yes | 1.18 | 0 |
| Surfboard-tg-vless | 5351 | yes | 1.87 | 0 |
| DeltaKronecker-all | 5347 | yes | 2.39 | 0 |
| mahdibland-V2RayAggregator | 5127 | yes | 1.58 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.01 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 65 |
| geo | 28 |
| cn-block | 22 |
| speed | 20 |
