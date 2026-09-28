# AutoNodes 每日报告

生成时间：2026-09-28 03:32:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 95076 |
| 去重后节点数 | 26767 |
| TCP 可达数 | 3000 |
| 真测通过数 | 568 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26767 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| generate | 87.6 |
| geo | 1.5 |
| probe | 337.4 |
| real_test | 532.8 |
| tcp | 43.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 31 | 18 | 63.3% |
| hysteria2 | 10 | 10 | 0 | 100.0% |
| shadowsocks | 202 | 189 | 13 | 93.6% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 24 | 6 | 18 | 25.0% |
| vless | 799 | 332 | 467 | 41.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 196 |
| speed:TimeoutError | 98 |
| geo:ClientOSError | 78 |
| speed:ClientOSError | 76 |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 17 |
| 204:ProxyError | 11 |
| 204:ProxyConnectionError | 9 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5997 |
| ConnectionRefusedError | 948 |
| gaierror | 398 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.923 | prefer | 339 | 0.867 | 1437 |
| Surfboard-tg-mixed | 0.823 | prefer | 72 | 0.75 | 7018 |
| ermaozi | 0.696 | observe | 42 | 0.69 | 347 |
| mheidari-all | 0.388 | observe | 615 | 0.307 | 22305 |
| Epodonios-all | 0.255 | observe | 0 | None | 7506 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8964 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5592 |
| barry-far-vless | 0.255 | observe | 0 | None | 5817 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4185 |

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
| downweight | DeltaKronecker-all | 0.144 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ermaozi-get_subscribe | 0.207 | 7 | 0.286 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 7 | 7 |
| ermaozi-get_subscribe | 0.286 | 2 | 5 | 7 |
| mheidari-all | 0.307 | 189 | 426 | 615 |
| ermaozi | 0.69 | 29 | 13 | 42 |
| Surfboard-tg-mixed | 0.75 | 54 | 18 | 72 |
| Au1rxx-base64 | 0.867 | 294 | 45 | 339 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22305 | yes | 5.62 | 0 |
| SoliSpirit-all | 8964 | yes | 3.39 | 0 |
| Epodonios-all | 7506 | yes | 3.48 | 0 |
| Surfboard-tg-mixed | 7018 | yes | 3.79 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.14 | 0 |
| barry-far-vless | 5817 | yes | 1.42 | 0 |
| Surfboard-tg-vless | 5592 | yes | 3.19 | 0 |
| DeltaKronecker-all | 5466 | yes | 5.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.21 | 0 |
| mahdibland-V2RayAggregator | 4185 | yes | 0.14 | 0 |

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
| geo | 275 |
| speed | 175 |
| 204 | 40 |
| cn-block | 28 |
