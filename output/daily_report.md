# AutoNodes 每日报告

生成时间：2026-10-11 03:55:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97432 |
| 去重后节点数 | 27464 |
| TCP 可达数 | 3000 |
| 真测通过数 | 533 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27464 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 82.7 |
| geo | 1.5 |
| probe | 420.6 |
| real_test | 642.3 |
| tcp | 46.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 10 | 1 | 9 | 10.0% |
| http | 38 | 31 | 7 | 81.6% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 125 | 121 | 4 | 96.8% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 140 | 121 | 19 | 86.4% |
| vless | 576 | 246 | 330 | 42.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 180 |
| speed:TimeoutError | 67 |
| geo:ClientOSError | 39 |
| speed:ClientOSError | 35 |
| 204:ProxyError | 15 |
| cn-block:TimeoutError | 15 |
| 204:ClientOSError | 10 |
| cn-block:ClientOSError | 6 |
| 204:TimeoutError | 3 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5988 |
| ConnectionRefusedError | 1066 |
| gaierror | 538 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 386 | 0.917 | 1801 |
| zhangkai | 0.96 | prefer | 20 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.58 | observe | 20 | 0.5 | 7087 |
| ermaozi-get_subscribe | 0.462 | observe | 30 | 0.433 | 610 |
| mheidari-all | 0.382 | observe | 435 | 0.301 | 23592 |
| DeltaKronecker-all | 0.352 | observe | 11 | 0.364 | 5009 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4347 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7576 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.301 | 131 | 304 | 435 |
| DeltaKronecker-all | 0.364 | 4 | 7 | 11 |
| ermaozi-get_subscribe | 0.433 | 13 | 17 | 30 |
| Surfboard-tg-mixed | 0.5 | 10 | 10 | 20 |
| Au1rxx-base64 | 0.917 | 354 | 32 | 386 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23592 | yes | 6.05 | 0 |
| SoliSpirit-all | 9365 | yes | 1.46 | 0 |
| Epodonios-all | 7576 | yes | 5.41 | 0 |
| Surfboard-tg-mixed | 7087 | yes | 4.49 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.67 | 0 |
| barry-far-vless | 5790 | yes | 1.66 | 0 |
| Surfboard-tg-vless | 5545 | yes | 3.87 | 0 |
| DeltaKronecker-all | 5009 | yes | 6.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4999 | yes | 0.74 | 0 |
| mahdibland-V2RayAggregator | 4347 | yes | 3.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 219 |
| speed | 102 |
| 204 | 29 |
| cn-block | 22 |
