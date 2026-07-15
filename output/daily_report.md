# AutoNodes 每日报告

生成时间：2026-07-15 13:30:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 76188 |
| 去重后节点数 | 22922 |
| TCP 可达数 | 3000 |
| 真测通过数 | 258 |
| verified 输出数 | 258 |
| global 输出数 | 266 |
| all 输出数 | 22922 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.8 |
| generate | 43.7 |
| geo | 1.3 |
| probe | 43.9 |
| real_test | 72.3 |
| tcp | 32.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 120 | 102 | 18 | 85.0% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 128 | 102 | 26 | 79.7% |
| vless | 104 | 10 | 94 | 9.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 49 |
| speed:ClientOSError | 44 |
| 204:TimeoutError | 15 |
| cn-block:ClientOSError | 6 |
| geo:ClientOSError | 5 |
| cn-block:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| 204:ProxyError | 4 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4660 |
| ConnectionRefusedError | 650 |
| OSError | 209 |
| gaierror | 173 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.823 | prefer | 102 | 0.824 | 149 |
| DeltaKronecker-all | 0.684 | observe | 99 | 0.606 | 6421 |
| Surfboard-tg-mixed | 0.634 | observe | 72 | 0.556 | 5463 |
| mheidari-all | 0.512 | observe | 86 | 0.43 | 16012 |
| nscl5-all | 0.26 | observe | 2 | 0.5 | 1300 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3759 |
| Epodonios-all | 0.255 | observe | 0 | None | 6619 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7237 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.43 | 37 | 49 | 86 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.556 | 40 | 32 | 72 |
| DeltaKronecker-all | 0.606 | 60 | 39 | 99 |
| Au1rxx-base64 | 0.824 | 84 | 18 | 102 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16012 | yes | 1.82 | 0 |
| SoliSpirit-all | 7237 | yes | 1.9 | 0 |
| Epodonios-all | 6619 | yes | 1.95 | 0 |
| DeltaKronecker-all | 6421 | yes | 2.17 | 0 |
| Surfboard-tg-mixed | 5463 | yes | 1.27 | 0 |
| mahdibland-V2RayAggregator | 5187 | yes | 0.31 | 0 |
| barry-far-vless | 4895 | yes | 0.54 | 0 |
| Surfboard-tg-vless | 4283 | yes | 1.17 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 0.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 3759 | yes | 0.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.096 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 55 |
| speed | 49 |
| 204 | 23 |
| cn-block | 14 |
