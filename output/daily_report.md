# AutoNodes 每日报告

生成时间：2026-09-26 03:29:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 96567 |
| 去重后节点数 | 26470 |
| TCP 可达数 | 3000 |
| 真测通过数 | 558 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26470 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 86.7 |
| geo | 1.5 |
| probe | 389.3 |
| real_test | 588.7 |
| tcp | 42.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 4 | 0 | 100.0% |
| http | 43 | 14 | 29 | 32.6% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 181 | 171 | 10 | 94.5% |
| socks | 9 | 6 | 3 | 66.7% |
| trojan | 7 | 6 | 1 | 85.7% |
| vless | 881 | 337 | 544 | 38.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 227 |
| speed:TimeoutError | 122 |
| cn-block:ClientOSError | 61 |
| geo:ClientOSError | 58 |
| speed:ClientOSError | 41 |
| 204:ProxyError | 32 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 14 |
| 204:ClientOSError | 8 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5580 |
| ConnectionRefusedError | 957 |
| gaierror | 448 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | prefer | 294 | 0.874 | 1598 |
| Surfboard-tg-mixed | 0.686 | observe | 92 | 0.609 | 7217 |
| DeltaKronecker-all | 0.441 | observe | 13 | 0.462 | 5452 |
| mheidari-all | 0.398 | observe | 697 | 0.317 | 22526 |
| ermaozi | 0.375 | observe | 34 | 0.353 | 352 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ermaozi-get_subscribe | 0.272 | observe | 13 | 0.308 | 375 |
| zhangkai | 0.261 | observe | 1 | 1.0 | 144 |
| Epodonios-all | 0.255 | observe | 0 | None | 7682 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.308 | 4 | 9 | 13 |
| mheidari-all | 0.317 | 221 | 476 | 697 |
| ermaozi | 0.353 | 12 | 22 | 34 |
| DeltaKronecker-all | 0.462 | 6 | 7 | 13 |
| Surfboard-tg-mixed | 0.609 | 56 | 36 | 92 |
| Au1rxx-base64 | 0.874 | 257 | 37 | 294 |
| zhangkai | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22526 | yes | 6.71 | 0 |
| SoliSpirit-all | 8921 | yes | 2.42 | 0 |
| Epodonios-all | 7682 | yes | 5.85 | 0 |
| Surfboard-tg-mixed | 7217 | yes | 3.9 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.03 | 0 |
| barry-far-vless | 6063 | yes | 0.57 | 0 |
| Surfboard-tg-vless | 5837 | yes | 4.14 | 0 |
| DeltaKronecker-all | 5452 | yes | 4.81 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 0.82 | 0 |
| mahdibland-V2RayAggregator | 4304 | yes | 2.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 286 |
| speed | 163 |
| cn-block | 78 |
| 204 | 61 |
