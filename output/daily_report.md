# AutoNodes 每日报告

生成时间：2026-06-29 19:55:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 75437 |
| 去重后节点数 | 22984 |
| TCP 可达数 | 3000 |
| 真测通过数 | 434 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22984 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| generate | 43.4 |
| geo | 1.4 |
| probe | 59.9 |
| real_test | 127.9 |
| tcp | 30.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 113 | 85 | 28 | 75.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 118 | 53 | 65 | 44.9% |
| vless | 352 | 252 | 100 | 71.6% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 93 |
| 204:ProxyError | 20 |
| 204:TimeoutError | 17 |
| 204:ClientOSError | 12 |
| cn-block:TimeoutError | 12 |
| geo:ClientOSError | 9 |
| cn-block:ProxyError | 7 |
| geo:TimeoutError | 7 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| geo:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4292 |
| ConnectionRefusedError | 639 |
| gaierror | 210 |
| OSError | 131 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.798 | prefer | 260 | 0.719 | 15724 |
| Au1rxx-base64 | 0.753 | prefer | 34 | 0.765 | 79 |
| Surfboard-tg-mixed | 0.745 | prefer | 231 | 0.667 | 5497 |
| DeltaKronecker-all | 0.535 | observe | 64 | 0.453 | 7004 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 170 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4653 |
| Epodonios-all | 0.255 | observe | 0 | None | 6449 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3980 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RayRootFree | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| 10ium-HighSpeed | 0.161 | observe | 1 | 0.0 | 0 | 839 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.453 | 29 | 35 | 64 |
| Surfboard-tg-mixed | 0.667 | 154 | 77 | 231 |
| mheidari-all | 0.719 | 187 | 73 | 260 |
| Au1rxx-base64 | 0.765 | 26 | 8 | 34 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15724 | yes | 2.65 | 0 |
| DeltaKronecker-all | 7004 | yes | 3.28 | 0 |
| SoliSpirit-all | 6727 | yes | 1.99 | 0 |
| Epodonios-all | 6449 | yes | 3.12 | 0 |
| Surfboard-tg-mixed | 5497 | yes | 1.53 | 0 |
| mahdibland-V2RayAggregator | 5353 | yes | 1.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 4653 | yes | 1.3 | 0 |
| barry-far-vless | 4569 | yes | 1.09 | 0 |
| Surfboard-tg-vless | 3986 | yes | 1.64 | 0 |
| MatinGhanbari-all-sub | 3980 | yes | 1.37 | 0 |

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
| speed | 101 |
| 204 | 49 |
| cn-block | 25 |
| geo | 19 |
