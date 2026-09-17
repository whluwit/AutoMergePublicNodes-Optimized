# AutoNodes 每日报告

生成时间：2026-09-17 03:18:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 89232 |
| 去重后节点数 | 24474 |
| TCP 可达数 | 3000 |
| 真测通过数 | 520 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24474 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 150.9 |
| geo | 1.4 |
| probe | 271.8 |
| real_test | 374.2 |
| tcp | 41.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 36 | 28 | 8 | 77.8% |
| hysteria2 | 24 | 20 | 4 | 83.3% |
| shadowsocks | 186 | 170 | 16 | 91.4% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 40 | 30 | 10 | 75.0% |
| vless | 491 | 271 | 220 | 55.2% |
| vmess | 3 | 0 | 3 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 64 |
| speed:TimeoutError | 55 |
| geo:ClientOSError | 47 |
| speed:ClientOSError | 22 |
| 204:ProxyError | 21 |
| cn-block:TimeoutError | 21 |
| cn-block:ClientOSError | 12 |
| 204:ProxyConnectionError | 10 |
| 204:TimeoutError | 7 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5794 |
| ConnectionRefusedError | 908 |
| gaierror | 353 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | prefer | 295 | 0.888 | 1703 |
| ermaozi | 0.809 | prefer | 27 | 0.815 | 396 |
| Surfboard-tg-mixed | 0.762 | prefer | 209 | 0.684 | 7464 |
| mheidari-all | 0.496 | observe | 152 | 0.414 | 17792 |
| DeltaKronecker-all | 0.366 | observe | 82 | 0.28 | 6081 |
| ermaozi-get_subscribe | 0.344 | observe | 11 | 0.455 | 431 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 140 |
| Epodonios-all | 0.255 | observe | 0 | None | 7930 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8850 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.28 | 23 | 59 | 82 |
| mheidari-all | 0.414 | 63 | 89 | 152 |
| ermaozi-get_subscribe | 0.455 | 5 | 6 | 11 |
| Surfboard-tg-mixed | 0.684 | 143 | 66 | 209 |
| ermaozi | 0.815 | 22 | 5 | 27 |
| Au1rxx-base64 | 0.888 | 262 | 33 | 295 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17792 | yes | 4.56 | 0 |
| SoliSpirit-all | 8850 | yes | 5.1 | 0 |
| Epodonios-all | 7930 | yes | 6.26 | 0 |
| Surfboard-tg-mixed | 7464 | yes | 4.77 | 0 |
| barry-far-vless | 6194 | yes | 0.74 | 0 |
| DeltaKronecker-all | 6081 | yes | 4.91 | 0 |
| Surfboard-tg-vless | 5964 | yes | 3.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 3.53 | 0 |
| mahdibland-V2RayAggregator | 4234 | yes | 2.81 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 111 |
| speed | 78 |
| 204 | 40 |
| cn-block | 36 |
