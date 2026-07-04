# AutoNodes 每日报告

生成时间：2026-07-04 13:18:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 78476 |
| 去重后节点数 | 23648 |
| TCP 可达数 | 3000 |
| 真测通过数 | 251 |
| verified 输出数 | 251 |
| global 输出数 | 266 |
| all 输出数 | 23648 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 43.3 |
| geo | 1.3 |
| probe | 44.8 |
| real_test | 70.8 |
| tcp | 31.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 83 | 71 | 12 | 85.5% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 154 | 95 | 59 | 61.7% |
| vless | 114 | 39 | 75 | 34.2% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 56 |
| 204:ProxyError | 16 |
| 204:TimeoutError | 15 |
| geo:TimeoutError | 14 |
| cn-block:TimeoutError | 14 |
| 204:ClientOSError | 7 |
| cn-block:ProxyError | 6 |
| geo:ProxyError | 6 |
| speed:TimeoutError | 5 |
| cn-block:ClientOSError | 3 |
| geo:ClientOSError | 3 |
| speed:ProxyError | 2 |
| geo:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4477 |
| ConnectionRefusedError | 681 |
| OSError | 152 |
| gaierror | 77 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.69 | observe | 30 | 0.7 | 68 |
| DeltaKronecker-all | 0.677 | observe | 157 | 0.599 | 7309 |
| Surfboard-tg-mixed | 0.664 | observe | 159 | 0.585 | 6003 |
| nscl5-all | 0.359 | observe | 2 | 1.0 | 1189 |
| mheidari-all | 0.344 | observe | 12 | 0.333 | 16374 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4579 |
| Epodonios-all | 0.255 | observe | 0 | None | 6895 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3967 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7174 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.333 | 4 | 8 | 12 |
| tg-ConfigV2rayNG | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.585 | 93 | 66 | 159 |
| DeltaKronecker-all | 0.599 | 94 | 63 | 157 |
| Au1rxx-base64 | 0.7 | 21 | 9 | 30 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16374 | yes | 3.73 | 0 |
| DeltaKronecker-all | 7309 | yes | 4.01 | 0 |
| SoliSpirit-all | 7174 | yes | 2.68 | 0 |
| Epodonios-all | 6895 | yes | 1.12 | 0 |
| Surfboard-tg-mixed | 6003 | yes | 2.81 | 0 |
| mahdibland-V2RayAggregator | 5333 | yes | 1.79 | 0 |
| barry-far-vless | 5028 | yes | 1.95 | 0 |
| 10ium-ScrapeCategorize-Vless | 4579 | yes | 1.65 | 0 |
| Surfboard-tg-vless | 4552 | yes | 2.97 | 0 |
| MatinGhanbari-all-sub | 3967 | yes | 2.04 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 63 |
| 204 | 38 |
| geo | 24 |
| cn-block | 23 |
