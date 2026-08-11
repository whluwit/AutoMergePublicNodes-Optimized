# AutoNodes 每日报告

生成时间：2026-08-11 07:02:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84699 |
| 去重后节点数 | 24202 |
| TCP 可达数 | 3000 |
| 真测通过数 | 471 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24202 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 34.2 |
| geo | 1.4 |
| probe | 50.7 |
| real_test | 101.9 |
| tcp | 36.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 49 | 0 | 100.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 160 | 142 | 18 | 88.8% |
| socks | 10 | 8 | 2 | 80.0% |
| trojan | 134 | 120 | 14 | 89.6% |
| vless | 211 | 136 | 75 | 64.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 29 |
| 204:ProxyError | 16 |
| 204:TimeoutError | 13 |
| geo:ClientOSError | 12 |
| speed:ClientOSError | 11 |
| cn-block:TimeoutError | 9 |
| speed:TimeoutError | 8 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4411 |
| ConnectionRefusedError | 803 |
| gaierror | 331 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | prefer | 49 | 1.0 | 67 |
| Au1rxx-base64 | 0.969 | prefer | 352 | 0.915 | 1414 |
| Surfboard-tg-mixed | 0.781 | prefer | 105 | 0.705 | 6265 |
| mheidari-all | 0.49 | observe | 37 | 0.405 | 20272 |
| DeltaKronecker-all | 0.396 | observe | 36 | 0.306 | 5522 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5419 |
| Epodonios-all | 0.255 | observe | 0 | None | 6871 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7464 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5103 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.306 | 11 | 25 | 36 |
| mheidari-all | 0.405 | 15 | 22 | 37 |
| Surfboard-tg-mixed | 0.705 | 74 | 31 | 105 |
| Au1rxx-base64 | 0.915 | 322 | 30 | 352 |
| zhangkai | 1.0 | 49 | 0 | 49 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20272 | yes | 3.8 | 0 |
| SoliSpirit-all | 7464 | yes | 3.85 | 0 |
| Epodonios-all | 6871 | yes | 3.96 | 0 |
| Surfboard-tg-mixed | 6265 | yes | 3.19 | 0 |
| DeltaKronecker-all | 5522 | yes | 4.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 5419 | yes | 2.64 | 0 |
| barry-far-vless | 5410 | yes | 1.01 | 0 |
| mahdibland-V2RayAggregator | 5209 | yes | 2.2 | 0 |
| Surfboard-tg-vless | 5103 | yes | 2.52 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 44 |
| 204 | 32 |
| speed | 20 |
| cn-block | 13 |
