# AutoNodes 每日报告

生成时间：2026-07-15 19:07:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 76350 |
| 去重后节点数 | 23029 |
| TCP 可达数 | 3000 |
| 真测通过数 | 321 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23029 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 26.0 |
| geo | 1.3 |
| probe | 50.2 |
| real_test | 88.4 |
| tcp | 32.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 108 | 91 | 17 | 84.3% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 208 | 169 | 39 | 81.2% |
| vless | 102 | 18 | 84 | 17.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 66 |
| 204:TimeoutError | 16 |
| speed:ClientOSError | 14 |
| cn-block:TimeoutError | 12 |
| 204:ClientOSError | 8 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 6 |
| geo:ClientOSError | 5 |
| 204:ProxyError | 5 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4474 |
| ConnectionRefusedError | 658 |
| gaierror | 279 |
| OSError | 209 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.966 | prefer | 138 | 0.891 | 16638 |
| Au1rxx-base64 | 0.722 | prefer | 97 | 0.722 | 132 |
| Surfboard-tg-mixed | 0.703 | prefer | 67 | 0.627 | 5510 |
| DeltaKronecker-all | 0.495 | observe | 121 | 0.413 | 6421 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3759 |
| Epodonios-all | 0.255 | observe | 0 | None | 6514 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6916 |
| barry-far-vless | 0.255 | observe | 0 | None | 4862 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.413 | 50 | 71 | 121 |
| Surfboard-tg-mixed | 0.627 | 42 | 25 | 67 |
| Au1rxx-base64 | 0.722 | 70 | 27 | 97 |
| mheidari-all | 0.891 | 123 | 15 | 138 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16638 | yes | 3.19 | 0 |
| SoliSpirit-all | 6916 | yes | 2.21 | 0 |
| Epodonios-all | 6514 | yes | 3.65 | 0 |
| DeltaKronecker-all | 6421 | yes | 3.26 | 0 |
| Surfboard-tg-mixed | 5510 | yes | 2.27 | 0 |
| mahdibland-V2RayAggregator | 5183 | yes | 1.66 | 0 |
| barry-far-vless | 4862 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 4277 | yes | 2.63 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 3759 | yes | 0.69 | 0 |

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
| geo | 71 |
| 204 | 29 |
| cn-block | 22 |
| speed | 21 |
