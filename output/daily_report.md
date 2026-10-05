# AutoNodes 每日报告

生成时间：2026-10-05 03:58:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 98799 |
| 去重后节点数 | 27511 |
| TCP 可达数 | 3000 |
| 真测通过数 | 567 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27511 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 75.7 |
| geo | 1.5 |
| probe | 287.1 |
| real_test | 484.4 |
| tcp | 46.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 3 | 4 | 42.9% |
| http | 59 | 35 | 24 | 59.3% |
| hysteria2 | 22 | 19 | 3 | 86.4% |
| shadowsocks | 114 | 105 | 9 | 92.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 107 | 91 | 16 | 85.0% |
| vless | 669 | 313 | 356 | 46.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 172 |
| speed:TimeoutError | 96 |
| 204:ProxyError | 42 |
| geo:ClientOSError | 40 |
| speed:ClientOSError | 23 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| 204:ProxyConnectionError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5763 |
| ConnectionRefusedError | 1039 |
| gaierror | 524 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.967 | prefer | 377 | 0.894 | 1876 |
| ermaozi | 0.618 | observe | 59 | 0.593 | 694 |
| Surfboard-tg-mixed | 0.53 | observe | 10 | 0.7 | 7178 |
| DeltaKronecker-all | 0.43 | observe | 9 | 0.556 | 5267 |
| mheidari-all | 0.429 | observe | 516 | 0.349 | 23195 |
| 10ium-ScrapeCategorize-Vless | 0.391 | observe | 2 | 1.0 | 5173 |
| Epodonios-all | 0.255 | observe | 0 | None | 7673 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9252 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5736 |

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
| downweight | ermaozi-get_subscribe | 0.17 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.349 | 180 | 336 | 516 |
| DeltaKronecker-all | 0.556 | 5 | 4 | 9 |
| ermaozi | 0.593 | 35 | 24 | 59 |
| Surfboard-tg-mixed | 0.7 | 7 | 3 | 10 |
| Au1rxx-base64 | 0.894 | 337 | 40 | 377 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23195 | yes | 7.18 | 0 |
| SoliSpirit-all | 9252 | yes | 5.46 | 0 |
| Epodonios-all | 7673 | yes | 4.07 | 0 |
| Surfboard-tg-mixed | 7178 | yes | 4.67 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.71 | 0 |
| barry-far-vless | 6057 | yes | 3.5 | 0 |
| Surfboard-tg-vless | 5736 | yes | 4.94 | 0 |
| DeltaKronecker-all | 5267 | yes | 6.38 | 0 |
| 10ium-ScrapeCategorize-Vless | 5173 | yes | 4.26 | 0 |
| mahdibland-V2RayAggregator | 4365 | yes | 3.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 213 |
| speed | 119 |
| 204 | 58 |
| cn-block | 24 |
