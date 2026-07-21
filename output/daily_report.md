# AutoNodes 每日报告

生成时间：2026-07-21 13:33:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82213 |
| 去重后节点数 | 22870 |
| TCP 可达数 | 3000 |
| 真测通过数 | 491 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22870 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 51.7 |
| geo | 1.4 |
| probe | 61.6 |
| real_test | 160.2 |
| tcp | 31.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 149 | 120 | 29 | 80.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 380 | 267 | 113 | 70.3% |
| vless | 403 | 63 | 340 | 15.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 179 |
| speed:ClientOSError | 107 |
| cn-block:TimeoutError | 92 |
| 204:TimeoutError | 30 |
| geo:ClientOSError | 27 |
| 204:ProxyError | 16 |
| 204:ClientOSError | 9 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 6 |
| geo:ProxyError | 4 |
| speed:ProxyError | 4 |
| speed:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42224: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4288 |
| ConnectionRefusedError | 665 |
| gaierror | 273 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.74 | prefer | 213 | 0.662 | 19167 |
| Au1rxx-base64 | 0.725 | prefer | 179 | 0.715 | 310 |
| Surfboard-tg-mixed | 0.614 | observe | 217 | 0.535 | 5464 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 4304 |
| DeltaKronecker-all | 0.291 | observe | 325 | 0.209 | 5415 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4482 |
| Epodonios-all | 0.255 | observe | 0 | None | 6557 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6824 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.209 | 68 | 257 | 325 |
| Surfboard-tg-mixed | 0.535 | 116 | 101 | 217 |
| mheidari-all | 0.662 | 141 | 72 | 213 |
| Au1rxx-base64 | 0.715 | 128 | 51 | 179 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19167 | yes | 4.08 | 0 |
| SoliSpirit-all | 6824 | yes | 2.08 | 0 |
| Epodonios-all | 6557 | yes | 0.24 | 0 |
| Surfboard-tg-mixed | 5464 | yes | 2.12 | 0 |
| DeltaKronecker-all | 5415 | yes | 3.04 | 0 |
| mahdibland-V2RayAggregator | 5247 | yes | 1.71 | 0 |
| barry-far-vless | 4844 | yes | 0.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 4482 | yes | 0.96 | 0 |
| xiaoji235-airport-v2ray-all | 4304 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 4207 | yes | 2.31 | 0 |

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
| geo | 210 |
| speed | 113 |
| cn-block | 105 |
| 204 | 55 |
| sing-box exited 1 | 1 |
