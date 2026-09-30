# AutoNodes 每日报告

生成时间：2026-09-30 17:38:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96189 |
| 去重后节点数 | 27002 |
| TCP 可达数 | 3000 |
| 真测通过数 | 354 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27002 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 91.3 |
| geo | 1.5 |
| probe | 240.2 |
| real_test | 161.2 |
| tcp | 46.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 28 | 14 | 14 | 50.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 169 | 150 | 19 | 88.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 7 | 4 | 3 | 57.1% |
| vless | 233 | 170 | 63 | 73.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 29 |
| 204:TimeoutError | 23 |
| cn-block:TimeoutError | 12 |
| 204:ProxyConnectionError | 11 |
| 204:ProxyError | 11 |
| geo:TimeoutError | 6 |
| cn-block:ClientOSError | 4 |
| speed:TimeoutError | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6451 |
| ConnectionRefusedError | 993 |
| gaierror | 329 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.889 | prefer | 279 | 0.821 | 1754 |
| mheidari-all | 0.869 | prefer | 93 | 0.796 | 22479 |
| Surfboard-tg-mixed | 0.813 | prefer | 43 | 0.744 | 6952 |
| zhangkai | 0.567 | observe | 18 | 0.611 | 144 |
| DeltaKronecker-all | 0.418 | observe | 10 | 0.5 | 5434 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4183 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7462 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9367 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.19 | 9 | 0.222 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.222 | 2 | 7 | 9 |
| DeltaKronecker-all | 0.5 | 5 | 5 | 10 |
| zhangkai | 0.611 | 11 | 7 | 18 |
| Surfboard-tg-mixed | 0.744 | 32 | 11 | 43 |
| mheidari-all | 0.796 | 74 | 19 | 93 |
| Au1rxx-base64 | 0.821 | 229 | 50 | 279 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22479 | yes | 5.83 | 0 |
| SoliSpirit-all | 9367 | yes | 1.82 | 0 |
| Epodonios-all | 7462 | yes | 4.19 | 0 |
| Surfboard-tg-mixed | 6952 | yes | 4.43 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.23 | 0 |
| barry-far-vless | 5879 | yes | 1.43 | 0 |
| Surfboard-tg-vless | 5632 | yes | 3.86 | 0 |
| DeltaKronecker-all | 5434 | yes | 6.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 0.44 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 0.45 | 0 |

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
| 204 | 45 |
| speed | 31 |
| cn-block | 17 |
| geo | 8 |
