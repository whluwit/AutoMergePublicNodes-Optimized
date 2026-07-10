# AutoNodes 每日报告

生成时间：2026-07-10 02:37:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 76967 |
| 去重后节点数 | 23552 |
| TCP 可达数 | 3000 |
| 真测通过数 | 406 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23552 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 33.1 |
| geo | 1.3 |
| probe | 44.7 |
| real_test | 71.5 |
| tcp | 31.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 104 | 99 | 5 | 95.2% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 174 | 162 | 12 | 93.1% |
| vless | 279 | 101 | 178 | 36.2% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 89 |
| geo:TimeoutError | 65 |
| geo:ClientOSError | 12 |
| speed:TimeoutError | 11 |
| cn-block:TimeoutError | 7 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 2 |
| geo:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4383 |
| ConnectionRefusedError | 678 |
| gaierror | 245 |
| OSError | 176 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.764 | prefer | 305 | 0.685 | 5645 |
| Au1rxx-base64 | 0.76 | prefer | 35 | 0.771 | 79 |
| DeltaKronecker-all | 0.722 | prefer | 202 | 0.644 | 7533 |
| nscl5-all | 0.301 | observe | 1 | 1.0 | 1148 |
| barry-far-Sub1 | 0.274 | observe | 1 | 1.0 | 485 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4306 |
| Epodonios-all | 0.255 | observe | 0 | None | 6482 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6596 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.205 | 22 | 0.091 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.091 | 2 | 20 | 22 |
| DeltaKronecker-all | 0.644 | 130 | 72 | 202 |
| Surfboard-tg-mixed | 0.685 | 209 | 96 | 305 |
| Au1rxx-base64 | 0.771 | 27 | 8 | 35 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| barry-far-Sub1 | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16939 | yes | 3.79 | 0 |
| DeltaKronecker-all | 7533 | yes | 3.81 | 0 |
| SoliSpirit-all | 6596 | yes | 2.49 | 0 |
| Epodonios-all | 6482 | yes | 1.06 | 0 |
| Surfboard-tg-mixed | 5645 | yes | 2.41 | 0 |
| mahdibland-V2RayAggregator | 5403 | yes | 1.79 | 0 |
| barry-far-vless | 4678 | yes | 1.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4306 | yes | 2.14 | 0 |
| Surfboard-tg-vless | 4155 | yes | 2.08 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 1.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 100 |
| geo | 78 |
| cn-block | 13 |
| 204 | 6 |
