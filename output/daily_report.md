# AutoNodes 每日报告

生成时间：2026-09-27 03:31:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 95995 |
| 去重后节点数 | 26622 |
| TCP 可达数 | 3000 |
| 真测通过数 | 522 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26622 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 71.9 |
| geo | 1.5 |
| probe | 279.0 |
| real_test | 380.3 |
| tcp | 43.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 38 | 30 | 8 | 78.9% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 179 | 165 | 14 | 92.2% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 59 | 37 | 22 | 62.7% |
| vless | 532 | 269 | 263 | 50.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 136 |
| speed:TimeoutError | 46 |
| geo:ClientOSError | 33 |
| speed:ClientOSError | 32 |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 15 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5881 |
| ConnectionRefusedError | 949 |
| gaierror | 429 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.916 | prefer | 280 | 0.854 | 1632 |
| Surfboard-tg-mixed | 0.824 | prefer | 217 | 0.747 | 7113 |
| ermaozi | 0.778 | prefer | 32 | 0.781 | 338 |
| ermaozi-get_subscribe | 0.423 | observe | 6 | 0.833 | 361 |
| mheidari-all | 0.377 | observe | 288 | 0.295 | 22408 |
| DeltaKronecker-all | 0.373 | observe | 5 | 0.6 | 5512 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.295 | 85 | 203 | 288 |
| DeltaKronecker-all | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.747 | 162 | 55 | 217 |
| ermaozi | 0.781 | 25 | 7 | 32 |
| ermaozi-get_subscribe | 0.833 | 5 | 1 | 6 |
| Au1rxx-base64 | 0.854 | 239 | 41 | 280 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22408 | yes | 4.96 | 0 |
| SoliSpirit-all | 8903 | yes | 1.65 | 0 |
| Epodonios-all | 7583 | yes | 2.54 | 0 |
| Surfboard-tg-mixed | 7113 | yes | 2.92 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.24 | 0 |
| barry-far-vless | 5907 | yes | 1.45 | 0 |
| Surfboard-tg-vless | 5686 | yes | 0.2 | 0 |
| DeltaKronecker-all | 5512 | yes | 3.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 0.58 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 2.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 169 |
| speed | 79 |
| 204 | 32 |
| cn-block | 32 |
