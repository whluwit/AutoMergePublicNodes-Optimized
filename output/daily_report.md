# AutoNodes 每日报告

生成时间：2026-09-13 15:41:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 95123 |
| 去重后节点数 | 25317 |
| TCP 可达数 | 3000 |
| 真测通过数 | 413 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25317 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 79.7 |
| geo | 1.4 |
| probe | 272.9 |
| real_test | 237.7 |
| tcp | 42.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 39 | 22 | 17 | 56.4% |
| hysteria2 | 23 | 17 | 6 | 73.9% |
| shadowsocks | 164 | 150 | 14 | 91.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 23 | 20 | 3 | 87.0% |
| vless | 377 | 202 | 175 | 53.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 61 |
| cn-block:ClientOSError | 46 |
| speed:ClientOSError | 24 |
| 204:ProxyError | 23 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 16 |
| speed:TimeoutError | 12 |
| geo:TimeoutError | 8 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5805 |
| ConnectionRefusedError | 982 |
| gaierror | 514 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.891 | prefer | 304 | 0.826 | 1678 |
| Surfboard-tg-mixed | 0.775 | prefer | 80 | 0.7 | 7605 |
| ermaozi | 0.654 | observe | 34 | 0.647 | 382 |
| mheidari-all | 0.489 | observe | 201 | 0.408 | 20611 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5301 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 5892 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| Epodonios-all | 0.255 | observe | 0 | None | 7899 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9265 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.089 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 5 | 5 |
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.408 | 82 | 119 | 201 |
| ermaozi | 0.647 | 22 | 12 | 34 |
| Surfboard-tg-mixed | 0.7 | 56 | 24 | 80 |
| Au1rxx-base64 | 0.826 | 251 | 53 | 304 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20611 | yes | 4.14 | 0 |
| SoliSpirit-all | 9265 | yes | 3.18 | 0 |
| Epodonios-all | 7899 | yes | 3.73 | 0 |
| Surfboard-tg-mixed | 7605 | yes | 2.68 | 0 |
| barry-far-vless | 6452 | yes | 2.32 | 0 |
| Surfboard-tg-vless | 6236 | yes | 3.29 | 0 |
| DeltaKronecker-all | 5892 | yes | 4.47 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 1.95 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.29 | 0 |
| mahdibland-V2RayAggregator | 4221 | yes | 1.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 70 |
| cn-block | 63 |
| 204 | 46 |
| speed | 37 |
