# AutoNodes 每日报告

生成时间：2026-07-31 13:57:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78379 |
| 去重后节点数 | 22732 |
| TCP 可达数 | 3000 |
| 真测通过数 | 403 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22732 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 19.6 |
| geo | 1.3 |
| probe | 53.0 |
| real_test | 105.4 |
| tcp | 32.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 80 | 80 | 0 | 100.0% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 135 | 117 | 18 | 86.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 20 | 19 | 1 | 95.0% |
| vless | 285 | 171 | 114 | 60.0% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 31 |
| geo:TimeoutError | 30 |
| 204:ProxyError | 21 |
| speed:TimeoutError | 12 |
| cn-block:TimeoutError | 12 |
| speed:ClientOSError | 12 |
| geo:ClientOSError | 10 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4581 |
| ConnectionRefusedError | 766 |
| OSError | 221 |
| gaierror | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 80 | 1.0 | 110 |
| Au1rxx-base64 | 0.865 | prefer | 272 | 0.809 | 1455 |
| mheidari-all | 0.658 | observe | 62 | 0.581 | 16815 |
| Surfboard-tg-mixed | 0.609 | observe | 100 | 0.53 | 5303 |
| DeltaKronecker-all | 0.573 | observe | 15 | 0.6 | 5144 |
| ninja-vless | 0.344 | observe | 6 | 0.5 | 1791 |
| xiaoji235-airport-v2ray-all | 0.282 | observe | 2 | 0.5 | 1861 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 48 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5507 |
| Epodonios-all | 0.255 | observe | 0 | None | 5989 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| ninja-vless | 0.5 | 3 | 3 | 6 |
| Surfboard-tg-mixed | 0.53 | 53 | 47 | 100 |
| mheidari-all | 0.581 | 36 | 26 | 62 |
| DeltaKronecker-all | 0.6 | 9 | 6 | 15 |
| Au1rxx-base64 | 0.809 | 220 | 52 | 272 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 80 | 0 | 80 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16815 | yes | 4.33 | 0 |
| SoliSpirit-all | 6742 | yes | 3.0 | 0 |
| Epodonios-all | 5989 | yes | 1.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 5507 | yes | 1.91 | 0 |
| Surfboard-tg-mixed | 5303 | yes | 2.69 | 0 |
| DeltaKronecker-all | 5144 | yes | 3.56 | 0 |
| mahdibland-V2RayAggregator | 5074 | yes | 2.26 | 0 |
| barry-far-vless | 4528 | yes | 1.42 | 0 |
| Surfboard-tg-vless | 4162 | yes | 2.55 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 1.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 55 |
| geo | 40 |
| speed | 25 |
| cn-block | 16 |
