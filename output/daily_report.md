# AutoNodes 每日报告

生成时间：2026-07-15 02:01:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 76355 |
| 去重后节点数 | 23709 |
| TCP 可达数 | 3000 |
| 真测通过数 | 396 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23709 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 22.2 |
| geo | 1.4 |
| probe | 40.0 |
| real_test | 67.8 |
| tcp | 32.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 146 | 136 | 10 | 93.2% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 208 | 197 | 11 | 94.7% |
| vless | 91 | 20 | 71 | 22.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 45 |
| geo:TimeoutError | 19 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 6 |
| geo:ClientOSError | 5 |
| cn-block:TimeoutError | 4 |
| 204:TimeoutError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4365 |
| ConnectionRefusedError | 664 |
| gaierror | 310 |
| OSError | 208 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 105 | 0.99 | 149 |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.89 | prefer | 77 | 0.818 | 5440 |
| DeltaKronecker-all | 0.839 | prefer | 139 | 0.763 | 6421 |
| mheidari-all | 0.739 | prefer | 130 | 0.662 | 18109 |
| nscl5-all | 0.307 | observe | 1 | 1.0 | 1300 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4019 |
| Epodonios-all | 0.255 | observe | 0 | None | 6322 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6024 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.662 | 86 | 44 | 130 |
| DeltaKronecker-all | 0.763 | 106 | 33 | 139 |
| Surfboard-tg-mixed | 0.818 | 63 | 14 | 77 |
| Au1rxx-base64 | 0.99 | 104 | 1 | 105 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18109 | yes | 3.5 | 0 |
| DeltaKronecker-all | 6421 | yes | 3.76 | 0 |
| Epodonios-all | 6322 | yes | 2.97 | 0 |
| SoliSpirit-all | 6024 | yes | 1.58 | 0 |
| Surfboard-tg-mixed | 5440 | yes | 3.68 | 0 |
| mahdibland-V2RayAggregator | 5187 | yes | 2.08 | 0 |
| barry-far-vless | 4653 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 4135 | yes | 1.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 4019 | yes | 1.06 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.34 | 0 |

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
| speed | 54 |
| geo | 25 |
| cn-block | 11 |
| 204 | 4 |
