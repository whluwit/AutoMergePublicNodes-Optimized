# AutoNodes 每日报告

生成时间：2026-07-22 08:26:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 82033 |
| 去重后节点数 | 22660 |
| TCP 可达数 | 3000 |
| 真测通过数 | 652 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22660 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 40.5 |
| geo | 1.4 |
| probe | 68.3 |
| real_test | 174.4 |
| tcp | 31.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 35 | 35 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 140 | 116 | 24 | 82.9% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 545 | 426 | 119 | 78.2% |
| vless | 246 | 68 | 178 | 27.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 108 |
| geo:TimeoutError | 107 |
| speed:ClientOSError | 43 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 13 |
| 204:TimeoutError | 11 |
| cn-block:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4179 |
| ConnectionRefusedError | 674 |
| gaierror | 306 |
| OSError | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.975 | prefer | 35 | 1.0 | 61 |
| mheidari-all | 0.869 | prefer | 348 | 0.79 | 19493 |
| Surfboard-tg-mixed | 0.668 | observe | 231 | 0.589 | 5331 |
| DeltaKronecker-all | 0.645 | observe | 152 | 0.566 | 5212 |
| Au1rxx-base64 | 0.586 | observe | 202 | 0.569 | 432 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 4246 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4613 |
| Epodonios-all | 0.255 | observe | 0 | None | 6417 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.566 | 86 | 66 | 152 |
| Au1rxx-base64 | 0.569 | 115 | 87 | 202 |
| Surfboard-tg-mixed | 0.589 | 136 | 95 | 231 |
| mheidari-all | 0.79 | 275 | 73 | 348 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 35 | 0 | 35 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19493 | yes | 3.89 | 0 |
| SoliSpirit-all | 6813 | yes | 3.65 | 0 |
| Epodonios-all | 6417 | yes | 3.32 | 0 |
| Surfboard-tg-mixed | 5331 | yes | 2.66 | 0 |
| DeltaKronecker-all | 5212 | yes | 4.4 | 0 |
| mahdibland-V2RayAggregator | 5204 | yes | 2.0 | 0 |
| 10ium-ScrapeCategorize-Vless | 4613 | yes | 1.7 | 0 |
| barry-far-vless | 4606 | yes | 1.77 | 0 |
| xiaoji235-airport-v2ray-all | 4246 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 4001 | yes | 2.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 122 |
| cn-block | 120 |
| speed | 50 |
| 204 | 30 |
