# AutoNodes 每日报告

生成时间：2026-07-13 14:27:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77657 |
| 去重后节点数 | 23879 |
| TCP 可达数 | 3000 |
| 真测通过数 | 226 |
| verified 输出数 | 226 |
| global 输出数 | 239 |
| all 输出数 | 23879 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 34.4 |
| geo | 1.4 |
| probe | 43.9 |
| real_test | 78.5 |
| tcp | 32.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 87 | 76 | 11 | 87.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 119 | 86 | 33 | 72.3% |
| vless | 74 | 19 | 55 | 25.7% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 42 |
| speed:ClientOSError | 12 |
| 204:TimeoutError | 8 |
| cn-block:TimeoutError | 8 |
| 204:ProxyError | 7 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 2 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4456 |
| ConnectionRefusedError | 660 |
| gaierror | 263 |
| OSError | 192 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.778 | prefer | 51 | 0.706 | 16239 |
| Surfboard-tg-mixed | 0.725 | prefer | 119 | 0.647 | 5596 |
| DeltaKronecker-all | 0.709 | prefer | 114 | 0.632 | 7926 |
| nscl5-all | 0.372 | observe | 2 | 1.0 | 1526 |
| xiaoji235-airport-v2ray-all | 0.321 | observe | 1 | 1.0 | 1647 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Au1rxx-base64 | 0.259 | observe | 1 | 1.0 | 109 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3897 |
| Epodonios-all | 0.255 | observe | 0 | None | 6473 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.632 | 72 | 42 | 114 |
| Surfboard-tg-mixed | 0.647 | 77 | 42 | 119 |
| mheidari-all | 0.706 | 36 | 15 | 51 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16239 | yes | 3.13 | 0 |
| DeltaKronecker-all | 7926 | yes | 2.63 | 0 |
| SoliSpirit-all | 6904 | yes | 1.81 | 0 |
| Epodonios-all | 6473 | yes | 0.23 | 0 |
| Surfboard-tg-mixed | 5596 | yes | 2.14 | 0 |
| mahdibland-V2RayAggregator | 5412 | yes | 0.89 | 0 |
| barry-far-vless | 4964 | yes | 1.48 | 0 |
| Surfboard-tg-vless | 4341 | yes | 1.88 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 3897 | yes | 1.96 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 45 |
| 204 | 19 |
| speed | 19 |
| cn-block | 17 |
