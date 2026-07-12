# AutoNodes 每日报告

生成时间：2026-07-12 13:12:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 77487 |
| 去重后节点数 | 24240 |
| TCP 可达数 | 3000 |
| 真测通过数 | 268 |
| verified 输出数 | 268 |
| global 输出数 | 285 |
| all 输出数 | 24240 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 32.8 |
| geo | 1.3 |
| probe | 42.2 |
| real_test | 68.1 |
| tcp | 32.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 1 | 1 | 0 | 100.0% |
| shadowsocks | 87 | 73 | 14 | 83.9% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 219 | 145 | 74 | 66.2% |
| vless | 51 | 6 | 45 | 11.8% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 30 |
| 204:ProxyError | 23 |
| cn-block:ProxyError | 15 |
| cn-block:ClientOSError | 13 |
| geo:ClientOSError | 10 |
| speed:ProxyError | 10 |
| geo:TimeoutError | 10 |
| 204:ClientOSError | 8 |
| 204:TimeoutError | 8 |
| cn-block:TimeoutError | 3 |
| geo:ProxyError | 3 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4564 |
| ConnectionRefusedError | 658 |
| gaierror | 232 |
| OSError | 202 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.81 | prefer | 109 | 0.734 | 5473 |
| DeltaKronecker-all | 0.68 | observe | 173 | 0.601 | 8141 |
| mheidari-all | 0.641 | observe | 80 | 0.562 | 16365 |
| xiaoji235-airport-v2ray-all | 0.315 | observe | 1 | 1.0 | 1508 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Au1rxx-base64 | 0.259 | observe | 1 | 1.0 | 99 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4003 |
| Epodonios-all | 0.255 | observe | 0 | None | 6473 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.562 | 45 | 35 | 80 |
| DeltaKronecker-all | 0.601 | 104 | 69 | 173 |
| Surfboard-tg-mixed | 0.734 | 80 | 29 | 109 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16365 | yes | 3.57 | 0 |
| DeltaKronecker-all | 8141 | yes | 2.75 | 0 |
| SoliSpirit-all | 6883 | yes | 1.99 | 0 |
| Epodonios-all | 6473 | yes | 1.56 | 0 |
| Surfboard-tg-mixed | 5473 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 5416 | yes | 1.64 | 0 |
| barry-far-vless | 4831 | yes | 1.18 | 0 |
| Surfboard-tg-vless | 4231 | yes | 1.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 4003 | yes | 1.31 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 40 |
| 204 | 39 |
| cn-block | 31 |
| geo | 24 |
