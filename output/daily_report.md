# AutoNodes 每日报告

生成时间：2026-09-08 16:04:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 90275 |
| 去重后节点数 | 25000 |
| TCP 可达数 | 3000 |
| 真测通过数 | 476 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25000 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 94.5 |
| geo | 1.3 |
| probe | 278.8 |
| real_test | 269.0 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 41 | 27 | 14 | 65.9% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 139 | 124 | 15 | 89.2% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 19 | 14 | 5 | 73.7% |
| vless | 416 | 291 | 125 | 70.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 40 |
| cn-block:ClientOSError | 32 |
| 204:ProxyError | 24 |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 15 |
| speed:ClientOSError | 9 |
| 204:ClientOSError | 6 |
| geo:TimeoutError | 6 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5176 |
| ConnectionRefusedError | 983 |
| gaierror | 537 |
| OSError | 251 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | prefer | 279 | 0.932 | 1658 |
| Surfboard-tg-mixed | 0.779 | prefer | 144 | 0.701 | 7484 |
| ermaozi | 0.692 | observe | 35 | 0.686 | 409 |
| mheidari-all | 0.589 | observe | 173 | 0.509 | 21582 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 212 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 6097 |
| Epodonios-all | 0.255 | observe | 0 | None | 7932 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8488 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.221 | 6 | 0.333 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.333 | 2 | 4 | 6 |
| mheidari-all | 0.509 | 88 | 85 | 173 |
| ermaozi | 0.686 | 24 | 11 | 35 |
| Surfboard-tg-mixed | 0.701 | 101 | 43 | 144 |
| Au1rxx-base64 | 0.932 | 260 | 19 | 279 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21582 | yes | 5.54 | 0 |
| SoliSpirit-all | 8488 | yes | 4.21 | 0 |
| Epodonios-all | 7932 | yes | 0.95 | 0 |
| Surfboard-tg-mixed | 7484 | yes | 4.56 | 0 |
| barry-far-vless | 6501 | yes | 2.32 | 0 |
| Surfboard-tg-vless | 6283 | yes | 4.31 | 0 |
| DeltaKronecker-all | 6097 | yes | 5.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 2.58 | 0 |
| mahdibland-V2RayAggregator | 4209 | yes | 3.36 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 55 |
| cn-block | 49 |
| geo | 47 |
| speed | 13 |
