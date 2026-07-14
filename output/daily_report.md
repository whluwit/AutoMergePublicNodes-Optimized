# AutoNodes 每日报告

生成时间：2026-07-14 13:26:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 80436 |
| 去重后节点数 | 23814 |
| TCP 可达数 | 3000 |
| 真测通过数 | 218 |
| verified 输出数 | 218 |
| global 输出数 | 226 |
| all 输出数 | 23814 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 38.9 |
| geo | 1.3 |
| probe | 46.7 |
| real_test | 77.2 |
| tcp | 32.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 91 | 72 | 19 | 79.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 138 | 100 | 38 | 72.5% |
| vless | 46 | 1 | 45 | 2.2% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 39 |
| speed:ClientOSError | 15 |
| 204:TimeoutError | 13 |
| 204:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| cn-block:TimeoutError | 6 |
| geo:ClientOSError | 4 |
| speed:ProxyError | 3 |
| geo:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4393 |
| ConnectionRefusedError | 675 |
| gaierror | 235 |
| OSError | 201 |
| UnicodeError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.839 | prefer | 81 | 0.765 | 5561 |
| mheidari-all | 0.787 | prefer | 97 | 0.711 | 17504 |
| DeltaKronecker-all | 0.547 | observe | 103 | 0.466 | 7942 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 3836 |
| Au1rxx-base64 | 0.259 | observe | 1 | 1.0 | 97 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4019 |
| Epodonios-all | 0.255 | observe | 0 | None | 6477 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6376 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_mtm | 0.13 | observe | 1 | 0.0 | 0 | 68 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-proxy_mtm | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.466 | 48 | 55 | 103 |
| mheidari-all | 0.711 | 69 | 28 | 97 |
| Surfboard-tg-mixed | 0.765 | 62 | 19 | 81 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17504 | yes | 4.07 | 0 |
| DeltaKronecker-all | 7942 | yes | 3.21 | 0 |
| Epodonios-all | 6477 | yes | 1.47 | 0 |
| SoliSpirit-all | 6376 | yes | 2.33 | 0 |
| Surfboard-tg-mixed | 5561 | yes | 2.27 | 0 |
| mahdibland-V2RayAggregator | 5405 | yes | 1.56 | 0 |
| barry-far-vless | 4832 | yes | 1.33 | 0 |
| Surfboard-tg-vless | 4279 | yes | 2.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4019 | yes | 1.34 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.022 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 46 |
| speed | 25 |
| 204 | 23 |
| cn-block | 10 |
