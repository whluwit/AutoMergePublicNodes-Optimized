# AutoNodes 每日报告

生成时间：2026-07-11 18:59:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 75124 |
| 去重后节点数 | 24063 |
| TCP 可达数 | 3000 |
| 真测通过数 | 292 |
| verified 输出数 | 292 |
| global 输出数 | 300 |
| all 输出数 | 24063 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.8 |
| generate | 42.5 |
| geo | 1.4 |
| probe | 59.3 |
| real_test | 122.9 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 1 | 1 | 0 | 100.0% |
| shadowsocks | 106 | 83 | 23 | 78.3% |
| socks | 14 | 10 | 4 | 71.4% |
| trojan | 95 | 53 | 42 | 55.8% |
| vless | 314 | 103 | 211 | 32.8% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 131 |
| 204:ProxyError | 32 |
| geo:TimeoutError | 28 |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 13 |
| geo:ClientOSError | 11 |
| cn-block:ClientOSError | 10 |
| speed:TimeoutError | 9 |
| 204:ClientOSError | 8 |
| cn-block:ProxyError | 6 |
| speed:ProxyError | 4 |
| geo:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4398 |
| ConnectionRefusedError | 657 |
| gaierror | 259 |
| OSError | 190 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.703 | prefer | 61 | 0.705 | 117 |
| Surfboard-tg-mixed | 0.587 | observe | 207 | 0.507 | 5204 |
| mheidari-all | 0.533 | observe | 190 | 0.453 | 16311 |
| DeltaKronecker-all | 0.366 | observe | 75 | 0.28 | 7969 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3953 |
| Epodonios-all | 0.255 | observe | 0 | None | 6185 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6322 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3946 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.28 | 21 | 54 | 75 |
| mheidari-all | 0.453 | 86 | 104 | 190 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.507 | 105 | 102 | 207 |
| Au1rxx-base64 | 0.705 | 43 | 18 | 61 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16311 | yes | 2.72 | 0 |
| DeltaKronecker-all | 7969 | yes | 2.8 | 0 |
| SoliSpirit-all | 6322 | yes | 1.32 | 0 |
| Epodonios-all | 6185 | yes | 1.52 | 0 |
| mahdibland-V2RayAggregator | 5416 | yes | 1.27 | 0 |
| Surfboard-tg-mixed | 5204 | yes | 1.93 | 0 |
| barry-far-vless | 4540 | yes | 0.72 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 3953 | yes | 1.03 | 0 |
| Surfboard-tg-vless | 3946 | yes | 1.38 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 144 |
| 204 | 65 |
| geo | 42 |
| cn-block | 29 |
