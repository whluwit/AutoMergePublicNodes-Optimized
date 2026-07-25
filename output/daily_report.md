# AutoNodes 每日报告

生成时间：2026-07-25 13:20:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78949 |
| 去重后节点数 | 22521 |
| TCP 可达数 | 3000 |
| 真测通过数 | 739 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22521 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 47.9 |
| geo | 1.3 |
| probe | 66.1 |
| real_test | 177.8 |
| tcp | 31.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 76 | 75 | 1 | 98.7% |
| hysteria2 | 8 | 7 | 1 | 87.5% |
| shadowsocks | 135 | 116 | 19 | 85.9% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 613 | 478 | 135 | 78.0% |
| vless | 174 | 62 | 112 | 35.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 52 |
| geo:TimeoutError | 51 |
| 204:ProxyError | 41 |
| speed:ClientOSError | 41 |
| 204:TimeoutError | 34 |
| cn-block:ClientOSError | 10 |
| cn-block:ProxyError | 9 |
| geo:ProxyError | 8 |
| geo:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| speed:ProxyError | 5 |
| 204:ClientOSError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:31485: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4200 |
| ConnectionRefusedError | 695 |
| gaierror | 285 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.979 | prefer | 76 | 0.987 | 119 |
| Au1rxx-base64 | 0.914 | prefer | 295 | 0.885 | 803 |
| mheidari-all | 0.81 | prefer | 391 | 0.731 | 17158 |
| Surfboard-tg-mixed | 0.663 | observe | 58 | 0.586 | 5379 |
| DeltaKronecker-all | 0.521 | observe | 184 | 0.44 | 5838 |
| Epodonios-all | 0.335 | observe | 1 | 1.0 | 6540 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 180 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6338 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4058 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.44 | 81 | 103 | 184 |
| Surfboard-tg-mixed | 0.586 | 34 | 24 | 58 |
| mheidari-all | 0.731 | 286 | 105 | 391 |
| Au1rxx-base64 | 0.885 | 261 | 34 | 295 |
| zhangkai | 0.987 | 75 | 1 | 76 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Epodonios-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17158 | yes | 3.84 | 0 |
| Epodonios-all | 6540 | yes | 3.41 | 0 |
| SoliSpirit-all | 6338 | yes | 3.75 | 0 |
| DeltaKronecker-all | 5838 | yes | 4.07 | 0 |
| Surfboard-tg-mixed | 5379 | yes | 2.3 | 0 |
| mahdibland-V2RayAggregator | 5009 | yes | 1.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 4879 | yes | 1.79 | 0 |
| barry-far-vless | 4746 | yes | 1.57 | 0 |
| Surfboard-tg-vless | 4058 | yes | 3.1 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 2.17 | 0 |

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
| 204 | 78 |
| cn-block | 71 |
| geo | 66 |
| speed | 53 |
| sing-box exited 1 | 1 |
