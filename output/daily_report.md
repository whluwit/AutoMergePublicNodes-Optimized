# AutoNodes 每日报告

生成时间：2026-09-23 21:09:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 97109 |
| 去重后节点数 | 26649 |
| TCP 可达数 | 3000 |
| 真测通过数 | 391 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26649 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 87.2 |
| geo | 1.5 |
| probe | 207.4 |
| real_test | 201.6 |
| tcp | 42.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 35 | 25 | 10 | 71.4% |
| hysteria2 | 13 | 10 | 3 | 76.9% |
| shadowsocks | 160 | 147 | 13 | 91.9% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 21 | 14 | 7 | 66.7% |
| vless | 237 | 191 | 46 | 80.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 13 |
| geo:TimeoutError | 6 |
| speed:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| 204:ClientOSError | 1 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5644 |
| ConnectionRefusedError | 973 |
| gaierror | 435 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | prefer | 248 | 0.915 | 1636 |
| mheidari-all | 0.937 | prefer | 75 | 0.867 | 22531 |
| ermaozi | 0.793 | prefer | 30 | 0.8 | 291 |
| Surfboard-tg-mixed | 0.732 | prefer | 110 | 0.655 | 7072 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4332 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 6471 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5131 |
| Epodonios-all | 0.255 | observe | 0 | None | 7534 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9136 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.148 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.167 | 1 | 5 | 6 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.655 | 72 | 38 | 110 |
| ermaozi | 0.8 | 24 | 6 | 30 |
| mheidari-all | 0.867 | 65 | 10 | 75 |
| Au1rxx-base64 | 0.915 | 227 | 21 | 248 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22531 | yes | 5.62 | 0 |
| SoliSpirit-all | 9136 | yes | 1.94 | 0 |
| Epodonios-all | 7534 | yes | 3.31 | 0 |
| Surfboard-tg-mixed | 7072 | yes | 4.02 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.25 | 0 |
| DeltaKronecker-all | 6471 | yes | 5.17 | 0 |
| barry-far-vless | 5930 | yes | 1.22 | 0 |
| Surfboard-tg-vless | 5711 | yes | 3.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 1.46 | 0 |
| mahdibland-V2RayAggregator | 4332 | yes | 3.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 39 |
| cn-block | 26 |
| speed | 9 |
| geo | 8 |
