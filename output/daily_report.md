# AutoNodes 每日报告

生成时间：2026-09-26 20:44:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 96521 |
| 去重后节点数 | 26456 |
| TCP 可达数 | 3000 |
| 真测通过数 | 391 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26456 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 74.8 |
| geo | 1.5 |
| probe | 277.0 |
| real_test | 169.4 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 21 | 5 | 16 | 23.8% |
| hysteria2 | 24 | 16 | 8 | 66.7% |
| shadowsocks | 158 | 131 | 27 | 82.9% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 15 | 13 | 2 | 86.7% |
| vless | 300 | 224 | 76 | 74.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 34 |
| cn-block:ClientOSError | 22 |
| 204:ProxyConnectionError | 19 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 9 |
| speed:ClientOSError | 8 |
| speed:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| speed:ProxyError | 1 |
| speed:ClientPayloadError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5829 |
| ConnectionRefusedError | 973 |
| gaierror | 429 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.945 | prefer | 288 | 0.882 | 1654 |
| Surfboard-tg-mixed | 0.735 | prefer | 111 | 0.658 | 7263 |
| mheidari-all | 0.662 | observe | 96 | 0.583 | 22366 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 66 |
| Epodonios-all | 0.255 | observe | 0 | None | 7740 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8923 |

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
| downweight | ermaozi | 0.199 | 18 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| ermaozi | 0.167 | 3 | 15 | 18 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.583 | 56 | 40 | 96 |
| Surfboard-tg-mixed | 0.658 | 73 | 38 | 111 |
| Au1rxx-base64 | 0.882 | 254 | 34 | 288 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22366 | yes | 5.14 | 0 |
| SoliSpirit-all | 8923 | yes | 3.21 | 0 |
| Epodonios-all | 7740 | yes | 4.51 | 0 |
| Surfboard-tg-mixed | 7263 | yes | 3.73 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.81 | 0 |
| barry-far-vless | 6052 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 5823 | yes | 3.43 | 0 |
| DeltaKronecker-all | 5512 | yes | 5.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 1.0 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 3.04 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 67 |
| cn-block | 42 |
| speed | 18 |
| geo | 5 |
