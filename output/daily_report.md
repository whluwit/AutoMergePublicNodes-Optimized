# AutoNodes 每日报告

生成时间：2026-10-11 21:36:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 99281 |
| 去重后节点数 | 27444 |
| TCP 可达数 | 3000 |
| 真测通过数 | 485 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27444 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 85.8 |
| geo | 1.5 |
| probe | 260.1 |
| real_test | 303.5 |
| tcp | 46.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 2 | 6 | 25.0% |
| http | 40 | 23 | 17 | 57.5% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 126 | 117 | 9 | 92.9% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 129 | 129 | 0 | 100.0% |
| vless | 225 | 191 | 34 | 84.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 13 |
| speed:ClientOSError | 11 |
| 204:ProxyConnectionError | 6 |
| 204:TimeoutError | 6 |
| speed:TimeoutError | 4 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| geo:TimeoutError | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6163 |
| ConnectionRefusedError | 1043 |
| gaierror | 454 |
| OSError | 240 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 377 | 0.942 | 1858 |
| mheidari-all | 0.905 | prefer | 112 | 0.83 | 23882 |
| ermaozi | 0.611 | observe | 39 | 0.59 | 635 |
| Surfboard-tg-mixed | 0.609 | observe | 12 | 0.75 | 7031 |
| DeltaKronecker-all | 0.349 | observe | 3 | 0.667 | 5372 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5099 |
| Epodonios-all | 0.255 | observe | 0 | None | 7711 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9704 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.203 | 8 | 0.25 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 2 | 6 | 8 |
| ermaozi | 0.59 | 23 | 16 | 39 |
| DeltaKronecker-all | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.75 | 9 | 3 | 12 |
| mheidari-all | 0.83 | 93 | 19 | 112 |
| Au1rxx-base64 | 0.942 | 355 | 22 | 377 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23882 | yes | 6.48 | 0 |
| SoliSpirit-all | 9704 | yes | 4.79 | 0 |
| Epodonios-all | 7711 | yes | 5.82 | 0 |
| Surfboard-tg-mixed | 7031 | yes | 4.92 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.49 | 0 |
| barry-far-vless | 5966 | yes | 1.71 | 0 |
| Surfboard-tg-vless | 5590 | yes | 4.19 | 0 |
| DeltaKronecker-all | 5372 | yes | 7.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 5099 | yes | 1.95 | 0 |
| mahdibland-V2RayAggregator | 4284 | yes | 3.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 33 |
| cn-block | 17 |
| speed | 15 |
| geo | 5 |
