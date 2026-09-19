# AutoNodes 每日报告

生成时间：2026-09-19 15:24:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 88358 |
| 去重后节点数 | 25224 |
| TCP 可达数 | 3000 |
| 真测通过数 | 449 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25224 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 85.0 |
| geo | 1.4 |
| probe | 240.0 |
| real_test | 217.7 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 14 | 11 | 3 | 78.6% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 151 | 139 | 12 | 92.1% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 28 | 16 | 12 | 57.1% |
| vless | 394 | 265 | 129 | 67.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 36 |
| cn-block:ClientOSError | 31 |
| geo:TimeoutError | 23 |
| speed:ClientOSError | 17 |
| 204:ProxyError | 16 |
| cn-block:TimeoutError | 14 |
| 204:TimeoutError | 11 |
| speed:TimeoutError | 9 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5793 |
| ConnectionRefusedError | 892 |
| gaierror | 451 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.939 | prefer | 314 | 0.879 | 1568 |
| mheidari-all | 0.698 | observe | 121 | 0.62 | 19364 |
| Surfboard-tg-mixed | 0.634 | observe | 146 | 0.555 | 7296 |
| ermaozi | 0.591 | observe | 12 | 0.833 | 250 |
| DeltaKronecker-all | 0.418 | observe | 10 | 0.5 | 6421 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5174 |
| Epodonios-all | 0.255 | observe | 0 | None | 7933 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9336 |

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
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.5 | 5 | 5 | 10 |
| Surfboard-tg-mixed | 0.555 | 81 | 65 | 146 |
| mheidari-all | 0.62 | 75 | 46 | 121 |
| ermaozi | 0.833 | 10 | 2 | 12 |
| Au1rxx-base64 | 0.879 | 276 | 38 | 314 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19364 | yes | 5.48 | 0 |
| SoliSpirit-all | 9336 | yes | 3.56 | 0 |
| Epodonios-all | 7933 | yes | 3.19 | 0 |
| Surfboard-tg-mixed | 7296 | yes | 4.23 | 0 |
| DeltaKronecker-all | 6421 | yes | 4.82 | 0 |
| barry-far-vless | 6222 | yes | 2.56 | 0 |
| Surfboard-tg-vless | 5900 | yes | 3.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 4.79 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 1.11 | 0 |
| MatinGhanbari-all-sub | 3995 | yes | 2.65 | 0 |

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
| geo | 60 |
| cn-block | 46 |
| 204 | 27 |
| speed | 26 |
