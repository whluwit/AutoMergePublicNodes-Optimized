# AutoNodes 每日报告

生成时间：2026-07-20 19:43:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 85844 |
| 去重后节点数 | 24243 |
| TCP 可达数 | 3000 |
| 真测通过数 | 403 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24243 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 36.9 |
| geo | 0.9 |
| probe | 61.4 |
| real_test | 132.8 |
| tcp | 34.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 119 | 100 | 19 | 84.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 306 | 194 | 112 | 63.4% |
| vless | 274 | 68 | 206 | 24.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 121 |
| speed:ClientOSError | 71 |
| cn-block:TimeoutError | 54 |
| 204:TimeoutError | 24 |
| 204:ProxyError | 22 |
| cn-block:ProxyError | 11 |
| cn-block:ClientOSError | 11 |
| geo:ClientOSError | 7 |
| 204:ClientOSError | 7 |
| speed:ProxyError | 6 |
| geo:ProxyError | 3 |
| speed:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4767 |
| ConnectionRefusedError | 701 |
| gaierror | 321 |
| OSError | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.835 | prefer | 230 | 0.809 | 719 |
| Surfboard-tg-mixed | 0.515 | observe | 175 | 0.434 | 5521 |
| mheidari-all | 0.515 | observe | 159 | 0.434 | 19990 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5035 |
| DeltaKronecker-all | 0.33 | observe | 138 | 0.246 | 5962 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4714 |
| Epodonios-all | 0.255 | observe | 0 | None | 6648 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.246 | 34 | 104 | 138 |
| mheidari-all | 0.434 | 69 | 90 | 159 |
| Surfboard-tg-mixed | 0.434 | 76 | 99 | 175 |
| Au1rxx-base64 | 0.809 | 186 | 44 | 230 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19990 | yes | 3.6 | 0 |
| SoliSpirit-all | 7049 | yes | 2.79 | 0 |
| Epodonios-all | 6648 | yes | 1.87 | 0 |
| DeltaKronecker-all | 5962 | yes | 3.6 | 0 |
| Surfboard-tg-mixed | 5521 | yes | 2.44 | 0 |
| mahdibland-V2RayAggregator | 5173 | yes | 1.69 | 0 |
| xiaoji235-airport-v2ray-all | 5035 | yes | 1.35 | 0 |
| barry-far-vless | 4959 | yes | 0.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 4714 | yes | 1.12 | 0 |
| Surfboard-tg-vless | 4263 | yes | 2.56 | 0 |

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
| geo | 131 |
| speed | 79 |
| cn-block | 76 |
| 204 | 53 |
