# AutoNodes 每日报告

生成时间：2026-08-18 12:41:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 91875 |
| 去重后节点数 | 24148 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1197 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24148 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| generate | 47.2 |
| geo | 1.4 |
| probe | 70.0 |
| real_test | 201.4 |
| tcp | 37.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 126 | 126 | 0 | 100.0% |
| hysteria2 | 23 | 20 | 3 | 87.0% |
| shadowsocks | 152 | 142 | 10 | 93.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 724 | 713 | 11 | 98.5% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 276 | 195 | 81 | 70.7% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 23 |
| geo:TimeoutError | 17 |
| geo:ClientOSError | 11 |
| speed:TimeoutError | 8 |
| speed:ClientOSError | 7 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4651 |
| ConnectionRefusedError | 967 |
| gaierror | 360 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 356 | 0.955 | 21086 |
| zhangkai | 0.999 | prefer | 126 | 1.0 | 159 |
| Au1rxx-base64 | 0.988 | prefer | 662 | 0.918 | 1759 |
| Surfboard-tg-mixed | 0.849 | prefer | 154 | 0.773 | 6169 |
| DeltaKronecker-all | 0.373 | observe | 5 | 0.6 | 5725 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 2992 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5068 |
| Epodonios-all | 0.255 | observe | 0 | None | 6795 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6898 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.773 | 119 | 35 | 154 |
| Au1rxx-base64 | 0.918 | 608 | 54 | 662 |
| mheidari-all | 0.955 | 340 | 16 | 356 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 126 | 0 | 126 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21086 | yes | 5.73 | 0 |
| SoliSpirit-all | 6898 | yes | 2.31 | 0 |
| Epodonios-all | 6795 | yes | 3.27 | 0 |
| xiaoji235-airport-v2ray-all | 6329 | yes | 1.77 | 0 |
| Surfboard-tg-mixed | 6169 | yes | 3.82 | 0 |
| DeltaKronecker-all | 5725 | yes | 4.2 | 0 |
| barry-far-vless | 5206 | yes | 1.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 5068 | yes | 2.03 | 0 |
| Surfboard-tg-vless | 4912 | yes | 3.59 | 0 |
| mahdibland-V2RayAggregator | 4045 | yes | 2.93 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| tuic | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 32 |
| 204 | 31 |
| geo | 29 |
| speed | 16 |
