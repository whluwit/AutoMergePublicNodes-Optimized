# AutoNodes 每日报告

生成时间：2026-09-21 17:53:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 84761 |
| 去重后节点数 | 23478 |
| TCP 可达数 | 3000 |
| 真测通过数 | 442 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23478 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 83.3 |
| geo | 1.4 |
| probe | 194.3 |
| real_test | 217.3 |
| tcp | 38.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 9 | 27 | 25.0% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 163 | 156 | 7 | 95.7% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 3 | 3 | 0 | 100.0% |
| vless | 403 | 259 | 144 | 64.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 40 |
| geo:ClientOSError | 35 |
| 204:ProxyError | 22 |
| speed:TimeoutError | 19 |
| speed:ClientOSError | 18 |
| cn-block:ClientOSError | 14 |
| cn-block:TimeoutError | 12 |
| 204:TimeoutError | 11 |
| 204:ProxyConnectionError | 8 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5531 |
| ConnectionRefusedError | 813 |
| gaierror | 262 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.957 | prefer | 268 | 0.892 | 1701 |
| mheidari-all | 0.769 | prefer | 72 | 0.694 | 16282 |
| Surfboard-tg-mixed | 0.721 | prefer | 179 | 0.642 | 7246 |
| DeltaKronecker-all | 0.548 | observe | 60 | 0.467 | 6181 |
| ermaozi | 0.399 | observe | 24 | 0.375 | 350 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| Epodonios-all | 0.255 | observe | 0 | None | 7695 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8945 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5845 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.07 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.148 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 6 | 6 |
| ermaozi-get_subscribe | 0.0 | 0 | 11 | 11 |
| ermaozi | 0.375 | 9 | 15 | 24 |
| DeltaKronecker-all | 0.467 | 28 | 32 | 60 |
| Surfboard-tg-mixed | 0.642 | 115 | 64 | 179 |
| mheidari-all | 0.694 | 50 | 22 | 72 |
| Au1rxx-base64 | 0.892 | 239 | 29 | 268 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16282 | yes | 4.76 | 0 |
| SoliSpirit-all | 8945 | yes | 2.43 | 0 |
| Epodonios-all | 7695 | yes | 5.11 | 0 |
| Surfboard-tg-mixed | 7246 | yes | 4.35 | 0 |
| DeltaKronecker-all | 6181 | yes | 3.4 | 0 |
| barry-far-vless | 6062 | yes | 0.79 | 0 |
| Surfboard-tg-vless | 5845 | yes | 5.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 0.58 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 3.24 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.87 | 0 |

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
| geo | 75 |
| 204 | 41 |
| speed | 37 |
| cn-block | 28 |
