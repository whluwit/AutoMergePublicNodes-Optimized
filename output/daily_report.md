# AutoNodes 每日报告

生成时间：2026-09-21 03:13:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 83863 |
| 去重后节点数 | 23662 |
| TCP 可达数 | 3000 |
| 真测通过数 | 695 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23662 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 79.5 |
| geo | 1.3 |
| probe | 272.5 |
| real_test | 417.4 |
| tcp | 39.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 53 | 36 | 17 | 67.9% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 190 | 186 | 4 | 97.9% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 45 | 27 | 18 | 60.0% |
| vless | 759 | 428 | 331 | 56.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 158 |
| geo:ClientOSError | 64 |
| speed:ClientOSError | 47 |
| speed:TimeoutError | 47 |
| 204:ProxyError | 22 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| 204:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5748 |
| ConnectionRefusedError | 784 |
| gaierror | 211 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | prefer | 353 | 0.918 | 1668 |
| Surfboard-tg-mixed | 0.773 | prefer | 99 | 0.697 | 7202 |
| ermaozi | 0.688 | observe | 44 | 0.682 | 355 |
| DeltaKronecker-all | 0.558 | observe | 452 | 0.478 | 6092 |
| mheidari-all | 0.555 | observe | 99 | 0.475 | 15960 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4315 |
| tg-oneclickvpnkeys | 0.314 | observe | 2 | 1.0 | 74 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| Epodonios-all | 0.255 | observe | 0 | None | 7661 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.24 | 10 | 0.3 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.25 | 1 | 3 | 4 |
| ermaozi-get_subscribe | 0.3 | 3 | 7 | 10 |
| mheidari-all | 0.475 | 47 | 52 | 99 |
| DeltaKronecker-all | 0.478 | 216 | 236 | 452 |
| ermaozi | 0.682 | 30 | 14 | 44 |
| Surfboard-tg-mixed | 0.697 | 69 | 30 | 99 |
| Au1rxx-base64 | 0.918 | 324 | 29 | 353 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15960 | yes | 3.16 | 0 |
| SoliSpirit-all | 8824 | yes | 2.21 | 0 |
| Epodonios-all | 7661 | yes | 2.05 | 0 |
| Surfboard-tg-mixed | 7202 | yes | 2.68 | 0 |
| DeltaKronecker-all | 6092 | yes | 3.25 | 0 |
| barry-far-vless | 6015 | yes | 1.6 | 0 |
| Surfboard-tg-vless | 5800 | yes | 2.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 1.45 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 1.04 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 223 |
| speed | 96 |
| 204 | 33 |
| cn-block | 21 |
