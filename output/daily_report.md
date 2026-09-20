# AutoNodes 每日报告

生成时间：2026-09-20 03:15:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 87229 |
| 去重后节点数 | 25359 |
| TCP 可达数 | 3000 |
| 真测通过数 | 573 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25359 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 83.0 |
| geo | 1.4 |
| probe | 272.1 |
| real_test | 368.9 |
| tcp | 42.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 60 | 45 | 15 | 75.0% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 182 | 172 | 10 | 94.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 78 | 45 | 33 | 57.7% |
| vless | 548 | 299 | 249 | 54.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 114 |
| speed:TimeoutError | 55 |
| geo:ClientOSError | 52 |
| speed:ClientOSError | 24 |
| 204:ProxyError | 19 |
| 204:TimeoutError | 13 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 12 |
| 204:ProxyConnectionError | 2 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5889 |
| ConnectionRefusedError | 899 |
| gaierror | 372 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.938 | prefer | 309 | 0.877 | 1576 |
| ermaozi | 0.76 | prefer | 53 | 0.755 | 365 |
| Surfboard-tg-mixed | 0.697 | observe | 262 | 0.618 | 7138 |
| mheidari-all | 0.474 | observe | 135 | 0.393 | 15978 |
| DeltaKronecker-all | 0.46 | observe | 106 | 0.377 | 6421 |
| ermaozi-get_subscribe | 0.337 | observe | 7 | 0.571 | 394 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| xiaoji235-airport-v2ray-all | 0.272 | observe | 7 | 0.286 | 3625 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5174 |
| Epodonios-all | 0.255 | observe | 0 | None | 7601 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.286 | 2 | 5 | 7 |
| DeltaKronecker-all | 0.377 | 40 | 66 | 106 |
| mheidari-all | 0.393 | 53 | 82 | 135 |
| ermaozi-get_subscribe | 0.571 | 4 | 3 | 7 |
| Surfboard-tg-mixed | 0.618 | 162 | 100 | 262 |
| ermaozi | 0.755 | 40 | 13 | 53 |
| Au1rxx-base64 | 0.877 | 271 | 38 | 309 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15978 | yes | 4.22 | 0 |
| SoliSpirit-all | 8846 | yes | 5.38 | 0 |
| Epodonios-all | 7601 | yes | 3.03 | 0 |
| Surfboard-tg-mixed | 7138 | yes | 5.44 | 0 |
| DeltaKronecker-all | 6421 | yes | 4.13 | 0 |
| barry-far-vless | 5908 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 5693 | yes | 5.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 0.68 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 2.66 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.75 | 0 |

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
| geo | 168 |
| speed | 80 |
| 204 | 35 |
| cn-block | 26 |
