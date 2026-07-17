# AutoNodes 每日报告

生成时间：2026-07-17 13:22:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 79175 |
| 去重后节点数 | 24872 |
| TCP 可达数 | 3000 |
| 真测通过数 | 366 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24872 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 32.7 |
| geo | 0.8 |
| probe | 56.3 |
| real_test | 114.8 |
| tcp | 32.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 1 | 1 | 50.0% |
| shadowsocks | 118 | 87 | 31 | 73.7% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 262 | 232 | 30 | 88.5% |
| vless | 125 | 5 | 120 | 4.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 65 |
| speed:ClientOSError | 61 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 7 |
| geo:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| speed:TimeoutError | 3 |
| 204:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4383 |
| ConnectionRefusedError | 674 |
| gaierror | 258 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.866 | prefer | 105 | 0.867 | 150 |
| Surfboard-tg-mixed | 0.682 | observe | 101 | 0.604 | 5276 |
| DeltaKronecker-all | 0.666 | observe | 288 | 0.587 | 8967 |
| mheidari-all | 0.467 | observe | 16 | 0.438 | 16536 |
| nscl5-all | 0.328 | observe | 1 | 1.0 | 1821 |
| xiaoji235-airport-v2ray-all | 0.322 | observe | 1 | 1.0 | 1680 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4428 |
| Epodonios-all | 0.255 | observe | 0 | None | 6455 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.111 | observe | 2 | 0.0 | 0 | 179 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.438 | 7 | 9 | 16 |
| DeltaKronecker-all | 0.587 | 169 | 119 | 288 |
| Surfboard-tg-mixed | 0.604 | 61 | 40 | 101 |
| Au1rxx-base64 | 0.867 | 91 | 14 | 105 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16536 | yes | 3.4 | 0 |
| DeltaKronecker-all | 8967 | yes | 3.85 | 0 |
| SoliSpirit-all | 6764 | yes | 2.2 | 0 |
| Epodonios-all | 6455 | yes | 1.78 | 0 |
| Surfboard-tg-mixed | 5276 | yes | 2.05 | 0 |
| mahdibland-V2RayAggregator | 5208 | yes | 1.6 | 0 |
| barry-far-vless | 4742 | yes | 1.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4428 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 4097 | yes | 2.2 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.04 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 72 |
| speed | 65 |
| 204 | 28 |
| cn-block | 20 |
