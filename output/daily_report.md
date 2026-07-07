# AutoNodes 每日报告

生成时间：2026-07-07 19:52:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84837 |
| 去重后节点数 | 24901 |
| TCP 可达数 | 3000 |
| 真测通过数 | 216 |
| verified 输出数 | 216 |
| global 输出数 | 227 |
| all 输出数 | 24901 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 36.8 |
| geo | 1.5 |
| probe | 42.8 |
| real_test | 57.5 |
| tcp | 32.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 5 | 4 | 1 | 80.0% |
| shadowsocks | 116 | 85 | 31 | 73.3% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 114 | 77 | 37 | 67.5% |
| vless | 52 | 3 | 49 | 5.8% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 43 |
| 204:TimeoutError | 17 |
| speed:ClientOSError | 13 |
| 204:ClientOSError | 11 |
| geo:TimeoutError | 11 |
| cn-block:ProxyError | 8 |
| cn-block:TimeoutError | 5 |
| cn-block:ClientOSError | 5 |
| geo:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4640 |
| ConnectionRefusedError | 832 |
| OSError | 167 |
| gaierror | 128 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.9 | prefer | 46 | 0.913 | 104 |
| mheidari-all | 0.784 | prefer | 69 | 0.71 | 18207 |
| Surfboard-tg-mixed | 0.655 | observe | 85 | 0.576 | 6066 |
| DeltaKronecker-all | 0.476 | observe | 94 | 0.394 | 8472 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3626 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 170 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4700 |
| Epodonios-all | 0.255 | observe | 0 | None | 7120 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3980 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.394 | 37 | 57 | 94 |
| Surfboard-tg-mixed | 0.576 | 49 | 36 | 85 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| mheidari-all | 0.71 | 49 | 20 | 69 |
| Au1rxx-base64 | 0.913 | 42 | 4 | 46 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18207 | yes | 3.74 | 0 |
| DeltaKronecker-all | 8472 | yes | 4.0 | 0 |
| Epodonios-all | 7120 | yes | 1.93 | 0 |
| SoliSpirit-all | 7035 | yes | 3.43 | 0 |
| Surfboard-tg-mixed | 6066 | yes | 2.89 | 0 |
| mahdibland-V2RayAggregator | 5339 | yes | 1.58 | 0 |
| barry-far-vless | 5281 | yes | 1.71 | 0 |
| 10ium-ScrapeCategorize-Vless | 4700 | yes | 1.57 | 0 |
| Surfboard-tg-vless | 4596 | yes | 2.68 | 0 |
| MatinGhanbari-all-sub | 3980 | yes | 1.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.058 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 71 |
| cn-block | 18 |
| geo | 16 |
| speed | 14 |
