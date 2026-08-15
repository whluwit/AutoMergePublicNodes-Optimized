# AutoNodes 每日报告

生成时间：2026-08-15 01:03:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 75539 |
| 去重后节点数 | 20579 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1087 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 20579 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 24.7 |
| geo | 1.0 |
| probe | 64.1 |
| real_test | 205.9 |
| tcp | 33.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 165 | 153 | 12 | 92.7% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 447 | 446 | 1 | 99.8% |
| vless | 484 | 332 | 152 | 68.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 44 |
| geo:ClientOSError | 34 |
| speed:TimeoutError | 27 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 15 |
| cn-block:ClientOSError | 11 |
| speed:ClientOSError | 10 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4390 |
| ConnectionRefusedError | 806 |
| gaierror | 301 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 659 | 0.973 | 1705 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| DeltaKronecker-all | 0.834 | prefer | 254 | 0.756 | 3485 |
| Surfboard-tg-mixed | 0.731 | prefer | 184 | 0.652 | 5731 |
| nscl5-all | 0.305 | observe | 10 | 0.3 | 2081 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 160 |
| Epodonios-all | 0.255 | observe | 0 | None | 6388 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7440 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| 10ium-ScrapeCategorize-Vless | 0.16 | observe | 4 | 0.0 | 0 | 5157 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.243 | 11 | 0.182 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.182 | 2 | 9 | 11 |
| nscl5-all | 0.3 | 3 | 7 | 10 |
| Surfboard-tg-mixed | 0.652 | 120 | 64 | 184 |
| DeltaKronecker-all | 0.756 | 192 | 62 | 254 |
| Au1rxx-base64 | 0.973 | 641 | 18 | 659 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15517 | yes | 4.24 | 0 |
| SoliSpirit-all | 7440 | yes | 3.92 | 0 |
| Epodonios-all | 6388 | yes | 4.43 | 0 |
| Surfboard-tg-mixed | 5731 | yes | 3.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 5157 | yes | 2.76 | 0 |
| barry-far-vless | 4816 | yes | 2.25 | 0 |
| Surfboard-tg-vless | 4486 | yes | 3.06 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.33 | 0 |
| mahdibland-V2RayAggregator | 3992 | yes | 1.52 | 0 |
| DeltaKronecker-all | 3485 | yes | 3.56 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 79 |
| speed | 37 |
| cn-block | 28 |
| 204 | 24 |
