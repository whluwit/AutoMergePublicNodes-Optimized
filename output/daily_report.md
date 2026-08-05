# AutoNodes 每日报告

生成时间：2026-08-05 02:06:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 86646 |
| 去重后节点数 | 24381 |
| TCP 可达数 | 3000 |
| 真测通过数 | 562 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24381 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.1 |
| generate | 27.4 |
| geo | 1.4 |
| probe | 50.8 |
| real_test | 117.5 |
| tcp | 36.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 51 | 50 | 1 | 98.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 156 | 146 | 10 | 93.6% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 182 | 157 | 25 | 86.3% |
| vless | 380 | 185 | 195 | 48.7% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 120 |
| cn-block:TimeoutError | 31 |
| speed:ClientOSError | 28 |
| speed:TimeoutError | 19 |
| geo:ClientOSError | 17 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 7 |
| 204:TimeoutError | 6 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4815 |
| ConnectionRefusedError | 842 |
| gaierror | 278 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 411 | 0.959 | 1436 |
| zhangkai | 0.965 | prefer | 51 | 0.98 | 72 |
| Surfboard-tg-mixed | 0.62 | observe | 174 | 0.54 | 5655 |
| mheidari-all | 0.309 | observe | 46 | 0.217 | 20244 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5251 |
| Epodonios-all | 0.255 | observe | 0 | None | 6252 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7229 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4478 |
| barry-far-vless | 0.255 | observe | 0 | None | 4815 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.209 | 114 | 0.123 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.123 | 14 | 100 | 114 |
| mheidari-all | 0.217 | 10 | 36 | 46 |
| Surfboard-tg-mixed | 0.54 | 94 | 80 | 174 |
| Au1rxx-base64 | 0.959 | 394 | 17 | 411 |
| zhangkai | 0.98 | 50 | 1 | 51 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20244 | yes | 4.86 | 0 |
| SoliSpirit-all | 7229 | yes | 4.65 | 0 |
| Epodonios-all | 6252 | yes | 1.98 | 0 |
| DeltaKronecker-all | 5788 | yes | 5.31 | 0 |
| Surfboard-tg-mixed | 5655 | yes | 3.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 5251 | yes | 2.54 | 0 |
| mahdibland-V2RayAggregator | 5141 | yes | 2.87 | 0 |
| barry-far-vless | 4815 | yes | 1.66 | 0 |
| xiaoji235-airport-v2ray-all | 4655 | yes | 2.48 | 0 |
| Surfboard-tg-vless | 4478 | yes | 3.06 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 137 |
| speed | 47 |
| cn-block | 32 |
| 204 | 20 |
