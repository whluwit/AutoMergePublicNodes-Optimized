# AutoNodes 每日报告

生成时间：2026-08-14 12:59:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 81470 |
| 去重后节点数 | 23179 |
| TCP 可达数 | 3000 |
| 真测通过数 | 852 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23179 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 29.3 |
| geo | 0.8 |
| probe | 55.4 |
| real_test | 148.6 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 131 | 121 | 10 | 92.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 373 | 372 | 1 | 99.7% |
| vless | 281 | 215 | 66 | 76.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 13 |
| geo:TimeoutError | 13 |
| 204:TimeoutError | 12 |
| cn-block:TimeoutError | 12 |
| 204:ProxyError | 8 |
| speed:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4260 |
| ConnectionRefusedError | 788 |
| gaierror | 426 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 642 | 0.95 | 1959 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.811 | prefer | 106 | 0.736 | 5845 |
| DeltaKronecker-all | 0.72 | prefer | 48 | 0.646 | 5969 |
| mheidari-all | 0.519 | observe | 5 | 1.0 | 17030 |
| nscl5-all | 0.278 | observe | 2 | 0.5 | 1768 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5157 |
| Epodonios-all | 0.255 | observe | 0 | None | 6515 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7472 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.646 | 31 | 17 | 48 |
| Surfboard-tg-mixed | 0.736 | 78 | 28 | 106 |
| Au1rxx-base64 | 0.95 | 610 | 32 | 642 |
| mheidari-all | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17030 | yes | 3.25 | 0 |
| SoliSpirit-all | 7472 | yes | 2.87 | 0 |
| Epodonios-all | 6515 | yes | 3.45 | 0 |
| DeltaKronecker-all | 5969 | yes | 3.64 | 0 |
| Surfboard-tg-mixed | 5845 | yes | 2.89 | 0 |
| mahdibland-V2RayAggregator | 5332 | yes | 1.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 5157 | yes | 1.82 | 0 |
| barry-far-vless | 4931 | yes | 1.93 | 0 |
| Surfboard-tg-vless | 4594 | yes | 2.42 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.21 | 0 |

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
| geo | 26 |
| 204 | 23 |
| cn-block | 18 |
| speed | 12 |
