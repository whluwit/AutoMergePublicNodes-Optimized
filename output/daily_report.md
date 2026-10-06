# AutoNodes 每日报告

生成时间：2026-10-06 22:21:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97973 |
| 去重后节点数 | 27040 |
| TCP 可达数 | 3000 |
| 真测通过数 | 437 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27040 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 78.2 |
| geo | 1.3 |
| probe | 230.1 |
| real_test | 143.3 |
| tcp | 45.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 2 | 5 | 28.6% |
| http | 46 | 16 | 30 | 34.8% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 159 | 151 | 8 | 95.0% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 97 | 95 | 2 | 97.9% |
| vless | 184 | 147 | 37 | 79.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 17 |
| 204:ProxyConnectionError | 15 |
| cn-block:TimeoutError | 12 |
| speed:ClientOSError | 9 |
| 204:TimeoutError | 8 |
| geo:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| cn-block:ClientOSError | 4 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5827 |
| ConnectionRefusedError | 1034 |
| gaierror | 550 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 319 | 0.934 | 1841 |
| Surfboard-tg-mixed | 0.945 | prefer | 50 | 0.88 | 7117 |
| mheidari-all | 0.88 | prefer | 93 | 0.806 | 23303 |
| ermaozi | 0.396 | observe | 47 | 0.362 | 708 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7604 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9213 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5711 |
| barry-far-vless | 0.255 | observe | 0 | None | 5954 |

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
| downweight | ermaozi-get_subscribe | 0.216 | 7 | 0.286 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| ermaozi-get_subscribe | 0.286 | 2 | 5 | 7 |
| ermaozi | 0.362 | 17 | 30 | 47 |
| mheidari-all | 0.806 | 75 | 18 | 93 |
| Surfboard-tg-mixed | 0.88 | 44 | 6 | 50 |
| Au1rxx-base64 | 0.934 | 298 | 21 | 319 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23303 | yes | 6.86 | 0 |
| SoliSpirit-all | 9213 | yes | 3.44 | 0 |
| Epodonios-all | 7604 | yes | 3.8 | 0 |
| Surfboard-tg-mixed | 7117 | yes | 4.9 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.26 | 0 |
| barry-far-vless | 5954 | yes | 1.65 | 0 |
| Surfboard-tg-vless | 5711 | yes | 4.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 1.96 | 0 |
| DeltaKronecker-all | 4889 | yes | 5.01 | 0 |
| mahdibland-V2RayAggregator | 4373 | yes | 2.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 43 |
| cn-block | 17 |
| speed | 14 |
| geo | 9 |
