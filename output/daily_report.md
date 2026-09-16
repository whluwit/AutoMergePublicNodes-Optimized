# AutoNodes 每日报告

生成时间：2026-09-16 16:09:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 89631 |
| 去重后节点数 | 24406 |
| TCP 可达数 | 3000 |
| 真测通过数 | 406 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24406 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 83.7 |
| geo | 1.4 |
| probe | 230.4 |
| real_test | 220.9 |
| tcp | 41.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 26 | 18 | 8 | 69.2% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 143 | 134 | 9 | 93.7% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 11 | 9 | 2 | 81.8% |
| vless | 297 | 222 | 75 | 74.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 16 |
| geo:TimeoutError | 16 |
| 204:ProxyError | 12 |
| geo:ClientOSError | 12 |
| speed:ClientOSError | 12 |
| speed:TimeoutError | 11 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 2 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5757 |
| ConnectionRefusedError | 924 |
| gaierror | 436 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.985 | prefer | 61 | 0.918 | 17973 |
| Au1rxx-base64 | 0.918 | prefer | 259 | 0.853 | 1698 |
| Surfboard-tg-mixed | 0.901 | prefer | 54 | 0.833 | 7470 |
| ermaozi | 0.764 | prefer | 22 | 0.773 | 353 |
| DeltaKronecker-all | 0.73 | prefer | 101 | 0.653 | 6081 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4206 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5115 |
| Epodonios-all | 0.255 | observe | 0 | None | 7938 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9150 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.653 | 66 | 35 | 101 |
| ermaozi | 0.773 | 17 | 5 | 22 |
| Surfboard-tg-mixed | 0.833 | 45 | 9 | 54 |
| Au1rxx-base64 | 0.853 | 221 | 38 | 259 |
| mheidari-all | 0.918 | 56 | 5 | 61 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17973 | yes | 5.46 | 0 |
| SoliSpirit-all | 9150 | yes | 3.54 | 0 |
| Epodonios-all | 7938 | yes | 3.28 | 0 |
| Surfboard-tg-mixed | 7470 | yes | 3.7 | 0 |
| barry-far-vless | 6195 | yes | 1.38 | 0 |
| DeltaKronecker-all | 6081 | yes | 5.6 | 0 |
| Surfboard-tg-vless | 5979 | yes | 3.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 1.16 | 0 |
| mahdibland-V2RayAggregator | 4206 | yes | 1.52 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.48 | 0 |

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
| geo | 28 |
| cn-block | 23 |
| speed | 23 |
| 204 | 22 |
