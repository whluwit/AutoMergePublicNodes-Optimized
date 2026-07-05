# AutoNodes 每日报告

生成时间：2026-07-05 19:13:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78312 |
| 去重后节点数 | 24052 |
| TCP 可达数 | 3000 |
| 真测通过数 | 241 |
| verified 输出数 | 241 |
| global 输出数 | 254 |
| all 输出数 | 24052 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 23.3 |
| geo | 1.3 |
| probe | 48.8 |
| real_test | 56.5 |
| tcp | 31.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 121 | 99 | 22 | 81.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 119 | 88 | 31 | 73.9% |
| vless | 38 | 10 | 28 | 26.3% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 19 |
| 204:TimeoutError | 16 |
| 204:ClientOSError | 14 |
| cn-block:TimeoutError | 14 |
| geo:TimeoutError | 11 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4412 |
| ConnectionRefusedError | 794 |
| gaierror | 159 |
| OSError | 155 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.842 | prefer | 78 | 0.769 | 16094 |
| Surfboard-tg-mixed | 0.816 | prefer | 89 | 0.742 | 5733 |
| Au1rxx-base64 | 0.778 | prefer | 29 | 0.793 | 102 |
| DeltaKronecker-all | 0.705 | prefer | 86 | 0.628 | 7739 |
| nscl5-all | 0.364 | observe | 2 | 1.0 | 1323 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4662 |
| Epodonios-all | 0.255 | observe | 0 | None | 7047 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6940 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.628 | 54 | 32 | 86 |
| Surfboard-tg-mixed | 0.742 | 66 | 23 | 89 |
| mheidari-all | 0.769 | 60 | 18 | 78 |
| Au1rxx-base64 | 0.793 | 23 | 6 | 29 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16094 | yes | 3.72 | 0 |
| DeltaKronecker-all | 7739 | yes | 3.51 | 0 |
| Epodonios-all | 7047 | yes | 0.86 | 0 |
| SoliSpirit-all | 6940 | yes | 2.28 | 0 |
| Surfboard-tg-mixed | 5733 | yes | 2.41 | 0 |
| mahdibland-V2RayAggregator | 5372 | yes | 0.66 | 0 |
| barry-far-vless | 4982 | yes | 1.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 4662 | yes | 1.61 | 0 |
| Surfboard-tg-vless | 4405 | yes | 2.19 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 32 |
| speed | 20 |
| cn-block | 19 |
| geo | 12 |
