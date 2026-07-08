# AutoNodes 每日报告

生成时间：2026-07-08 19:21:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83161 |
| 去重后节点数 | 24948 |
| TCP 可达数 | 3000 |
| 真测通过数 | 177 |
| verified 输出数 | 177 |
| global 输出数 | 184 |
| all 输出数 | 24948 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 38.8 |
| geo | 1.6 |
| probe | 41.3 |
| real_test | 60.7 |
| tcp | 32.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 89 | 73 | 16 | 82.0% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 71 | 32 | 39 | 45.1% |
| vless | 102 | 23 | 79 | 22.5% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 49 |
| geo:TimeoutError | 27 |
| 204:TimeoutError | 21 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 7 |
| cn-block:TimeoutError | 6 |
| cn-block:ProxyError | 3 |
| geo:ClientOSError | 3 |
| speed:TimeoutError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4501 |
| ConnectionRefusedError | 838 |
| gaierror | 244 |
| OSError | 170 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.77 | prefer | 66 | 0.773 | 129 |
| Surfboard-tg-mixed | 0.66 | observe | 79 | 0.582 | 5884 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 3640 |
| DeltaKronecker-all | 0.399 | observe | 114 | 0.316 | 8321 |
| mheidari-all | 0.382 | observe | 14 | 0.357 | 18123 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4408 |
| Epodonios-all | 0.255 | observe | 0 | None | 6761 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3966 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6878 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 3 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.316 | 36 | 78 | 114 |
| mheidari-all | 0.357 | 5 | 9 | 14 |
| Surfboard-tg-mixed | 0.582 | 46 | 33 | 79 |
| Au1rxx-base64 | 0.773 | 51 | 15 | 66 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18123 | yes | 3.79 | 0 |
| DeltaKronecker-all | 8321 | yes | 4.04 | 0 |
| SoliSpirit-all | 6878 | yes | 1.94 | 0 |
| Epodonios-all | 6761 | yes | 1.58 | 0 |
| Surfboard-tg-mixed | 5884 | yes | 2.35 | 0 |
| mahdibland-V2RayAggregator | 5361 | yes | 0.32 | 0 |
| barry-far-vless | 4940 | yes | 1.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4408 | yes | 1.19 | 0 |
| Surfboard-tg-vless | 4406 | yes | 1.97 | 0 |
| MatinGhanbari-all-sub | 3966 | yes | 1.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 52 |
| 204 | 37 |
| geo | 31 |
| cn-block | 16 |
