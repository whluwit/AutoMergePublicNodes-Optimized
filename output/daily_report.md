# AutoNodes 每日报告

生成时间：2026-10-10 04:18:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 98044 |
| 去重后节点数 | 27733 |
| TCP 可达数 | 3000 |
| 真测通过数 | 553 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27733 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 88.2 |
| geo | 1.5 |
| probe | 344.2 |
| real_test | 563.6 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 42 | 34 | 8 | 81.0% |
| hysteria2 | 25 | 25 | 0 | 100.0% |
| shadowsocks | 173 | 162 | 11 | 93.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 133 | 127 | 6 | 95.5% |
| vless | 474 | 200 | 274 | 42.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 131 |
| speed:TimeoutError | 67 |
| geo:ClientOSError | 35 |
| speed:ClientOSError | 19 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 12 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6591 |
| ConnectionRefusedError | 1022 |
| gaierror | 373 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | prefer | 359 | 0.928 | 1803 |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.695 | observe | 193 | 0.617 | 7155 |
| ermaozi-get_subscribe | 0.656 | observe | 25 | 0.64 | 653 |
| mheidari-all | 0.34 | observe | 240 | 0.258 | 23395 |
| 10ium-ScrapeCategorize-Vless | 0.287 | observe | 2 | 0.5 | 4984 |
| Epodonios-all | 0.255 | observe | 0 | None | 7634 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9711 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5643 |

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
| downweight | DeltaKronecker-all | 0.183 | 13 | 0.077 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.077 | 1 | 12 | 13 |
| mheidari-all | 0.258 | 62 | 178 | 240 |
| 10ium-ScrapeCategorize-Vless | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.617 | 119 | 74 | 193 |
| ermaozi-get_subscribe | 0.64 | 16 | 9 | 25 |
| Au1rxx-base64 | 0.928 | 333 | 26 | 359 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23395 | yes | 7.08 | 0 |
| SoliSpirit-all | 9711 | yes | 4.88 | 0 |
| Epodonios-all | 7634 | yes | 4.15 | 0 |
| Surfboard-tg-mixed | 7155 | yes | 5.04 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.26 | 0 |
| barry-far-vless | 5793 | yes | 2.38 | 0 |
| Surfboard-tg-vless | 5643 | yes | 4.74 | 0 |
| DeltaKronecker-all | 5154 | yes | 5.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 4984 | yes | 3.04 | 0 |
| mahdibland-V2RayAggregator | 4346 | yes | 3.77 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 168 |
| speed | 86 |
| 204 | 24 |
| cn-block | 24 |
