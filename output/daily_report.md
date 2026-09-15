# AutoNodes 每日报告

生成时间：2026-09-15 11:07:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 90100 |
| 去重后节点数 | 25502 |
| TCP 可达数 | 3000 |
| 真测通过数 | 486 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25502 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 70.0 |
| geo | 1.4 |
| probe | 342.0 |
| real_test | 249.7 |
| tcp | 42.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 52 | 35 | 17 | 67.3% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 157 | 144 | 13 | 91.7% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 10 | 4 | 6 | 40.0% |
| vless | 415 | 281 | 134 | 67.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 30 |
| 204:ProxyError | 29 |
| cn-block:TimeoutError | 28 |
| geo:ClientOSError | 22 |
| geo:TimeoutError | 16 |
| cn-block:ClientOSError | 14 |
| speed:TimeoutError | 11 |
| speed:ClientOSError | 9 |
| 204:ClientOSError | 9 |
| cn-block:ProxyError | 4 |
| speed:ProxyError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5941 |
| ConnectionRefusedError | 960 |
| gaierror | 357 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.906 | prefer | 309 | 0.851 | 1440 |
| mheidari-all | 0.83 | prefer | 62 | 0.758 | 21594 |
| ermaozi | 0.684 | observe | 52 | 0.673 | 425 |
| Surfboard-tg-mixed | 0.678 | observe | 125 | 0.6 | 7543 |
| DeltaKronecker-all | 0.669 | observe | 110 | 0.591 | 5932 |
| ermaozi-get_subscribe | 0.273 | observe | 1 | 1.0 | 447 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 8009 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8725 |

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
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.591 | 65 | 45 | 110 |
| Surfboard-tg-mixed | 0.6 | 75 | 50 | 125 |
| ermaozi | 0.673 | 35 | 17 | 52 |
| mheidari-all | 0.758 | 47 | 15 | 62 |
| Au1rxx-base64 | 0.851 | 263 | 46 | 309 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21594 | yes | 3.18 | 0 |
| SoliSpirit-all | 8725 | yes | 3.26 | 0 |
| Epodonios-all | 8009 | yes | 2.79 | 0 |
| Surfboard-tg-mixed | 7543 | yes | 2.58 | 0 |
| barry-far-vless | 6343 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 6114 | yes | 2.14 | 0 |
| DeltaKronecker-all | 5932 | yes | 3.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.99 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 0.79 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.09 | 0 |

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
| 204 | 68 |
| cn-block | 46 |
| geo | 38 |
| speed | 23 |
