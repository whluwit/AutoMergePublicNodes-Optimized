# AutoNodes 每日报告

生成时间：2026-07-24 08:23:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83095 |
| 去重后节点数 | 22604 |
| TCP 可达数 | 3000 |
| 真测通过数 | 748 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22604 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 41.5 |
| geo | 1.4 |
| probe | 63.4 |
| real_test | 181.4 |
| tcp | 32.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 35 | 1 | 97.2% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 12 | 9 | 3 | 75.0% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 597 | 564 | 33 | 94.5% |
| vless | 483 | 135 | 348 | 28.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 181 |
| geo:ClientOSError | 50 |
| speed:ClientOSError | 45 |
| cn-block:TimeoutError | 35 |
| 204:ProxyError | 28 |
| speed:TimeoutError | 17 |
| 204:TimeoutError | 13 |
| cn-block:ClientOSError | 9 |
| cn-block:ProxyError | 5 |
| 204:ClientOSError | 2 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4154 |
| ConnectionRefusedError | 679 |
| gaierror | 446 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.95 | prefer | 428 | 0.871 | 19618 |
| zhangkai | 0.95 | prefer | 36 | 0.972 | 61 |
| Surfboard-tg-mixed | 0.708 | prefer | 232 | 0.629 | 5335 |
| DeltaKronecker-all | 0.52 | observe | 423 | 0.44 | 5559 |
| Au1rxx-base64 | 0.467 | observe | 10 | 0.7 | 432 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3847 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4588 |
| Epodonios-all | 0.255 | observe | 0 | None | 6546 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6796 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.44 | 186 | 237 | 423 |
| Surfboard-tg-mixed | 0.629 | 146 | 86 | 232 |
| Au1rxx-base64 | 0.7 | 7 | 3 | 10 |
| mheidari-all | 0.871 | 373 | 55 | 428 |
| zhangkai | 0.972 | 35 | 1 | 36 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19618 | yes | 4.74 | 0 |
| SoliSpirit-all | 6796 | yes | 1.96 | 0 |
| Epodonios-all | 6546 | yes | 2.02 | 0 |
| DeltaKronecker-all | 5559 | yes | 3.57 | 0 |
| Surfboard-tg-mixed | 5335 | yes | 2.41 | 0 |
| mahdibland-V2RayAggregator | 5027 | yes | 1.84 | 0 |
| barry-far-vless | 4836 | yes | 1.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4588 | yes | 1.54 | 0 |
| Surfboard-tg-vless | 4186 | yes | 2.72 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.63 | 0 |

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
| geo | 232 |
| speed | 64 |
| cn-block | 49 |
| 204 | 43 |
