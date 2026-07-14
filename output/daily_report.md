# AutoNodes 每日报告

生成时间：2026-07-14 07:58:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78965 |
| 去重后节点数 | 23661 |
| TCP 可达数 | 3000 |
| 真测通过数 | 250 |
| verified 输出数 | 250 |
| global 输出数 | 254 |
| all 输出数 | 23661 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 23.6 |
| geo | 1.4 |
| probe | 44.5 |
| real_test | 72.8 |
| tcp | 30.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 81 | 60 | 21 | 74.1% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 176 | 139 | 37 | 79.0% |
| vless | 76 | 6 | 70 | 7.9% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 63 |
| speed:ClientOSError | 18 |
| 204:TimeoutError | 11 |
| 204:ClientOSError | 10 |
| geo:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 4 |
| speed:ProxyError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4155 |
| ConnectionRefusedError | 634 |
| gaierror | 298 |
| OSError | 196 |
| UnicodeError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| DeltaKronecker-all | 0.737 | prefer | 138 | 0.659 | 7942 |
| mheidari-all | 0.697 | observe | 92 | 0.62 | 18408 |
| Surfboard-tg-mixed | 0.653 | observe | 108 | 0.574 | 5561 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 3836 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Au1rxx-base64 | 0.26 | observe | 1 | 1.0 | 114 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4019 |
| Epodonios-all | 0.255 | observe | 0 | None | 6471 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-Ahmedhamoomi_Servers | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-BESTFORBEST66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CryptoGuardVPN | 0.025 | observe | 0 | None | 1 | 0 |
| tg-DarkVPNpro | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.574 | 62 | 46 | 108 |
| mheidari-all | 0.62 | 57 | 35 | 92 |
| DeltaKronecker-all | 0.659 | 91 | 47 | 138 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18408 | yes | 3.76 | 0 |
| DeltaKronecker-all | 7942 | yes | 3.29 | 0 |
| Epodonios-all | 6471 | yes | 0.53 | 0 |
| SoliSpirit-all | 6407 | yes | 1.65 | 0 |
| Surfboard-tg-mixed | 5561 | yes | 2.27 | 0 |
| mahdibland-V2RayAggregator | 5405 | yes | 1.72 | 0 |
| barry-far-vless | 4827 | yes | 0.91 | 0 |
| Surfboard-tg-vless | 4279 | yes | 2.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 4019 | yes | 1.1 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.35 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.079 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 71 |
| 204 | 26 |
| speed | 26 |
| cn-block | 5 |
