# AutoNodes 每日报告

生成时间：2026-07-02 02:53:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 76269 |
| 去重后节点数 | 23383 |
| TCP 可达数 | 3000 |
| 真测通过数 | 592 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23383 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 28.8 |
| geo | 1.3 |
| probe | 58.1 |
| real_test | 144.3 |
| tcp | 30.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 11 | 3 | 8 | 27.3% |
| shadowsocks | 142 | 121 | 21 | 85.2% |
| socks | 37 | 33 | 4 | 89.2% |
| trojan | 146 | 127 | 19 | 87.0% |
| vless | 741 | 266 | 475 | 35.9% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 232 |
| geo:TimeoutError | 154 |
| geo:ClientOSError | 53 |
| speed:TimeoutError | 39 |
| 204:ProxyError | 14 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| 204:TimeoutError | 7 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 2 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4280 |
| ConnectionRefusedError | 693 |
| gaierror | 204 |
| OSError | 152 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.826 | prefer | 344 | 0.747 | 5714 |
| Au1rxx-base64 | 0.765 | prefer | 69 | 0.768 | 103 |
| mheidari-all | 0.561 | observe | 316 | 0.481 | 16042 |
| DeltaKronecker-all | 0.35 | observe | 343 | 0.268 | 7631 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4308 |
| Epodonios-all | 0.255 | observe | 0 | None | 6523 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6496 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.113 | downweight | 8 | 0.0 | 0 | 1293 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.113 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 8 | 8 |
| DeltaKronecker-all | 0.268 | 92 | 251 | 343 |
| mheidari-all | 0.481 | 152 | 164 | 316 |
| Surfboard-tg-mixed | 0.747 | 257 | 87 | 344 |
| Au1rxx-base64 | 0.768 | 53 | 16 | 69 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16042 | yes | 3.59 | 0 |
| DeltaKronecker-all | 7631 | yes | 3.8 | 0 |
| Epodonios-all | 6523 | yes | 1.88 | 0 |
| SoliSpirit-all | 6496 | yes | 2.69 | 0 |
| Surfboard-tg-mixed | 5714 | yes | 2.81 | 0 |
| mahdibland-V2RayAggregator | 5331 | yes | 0.36 | 0 |
| barry-far-vless | 4744 | yes | 0.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 4308 | yes | 1.88 | 0 |
| Surfboard-tg-vless | 4236 | yes | 2.14 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 273 |
| geo | 207 |
| 204 | 27 |
| cn-block | 20 |
