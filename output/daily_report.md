# AutoNodes 每日报告

生成时间：2026-10-04 04:14:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 99137 |
| 去重后节点数 | 27362 |
| TCP 可达数 | 3000 |
| 真测通过数 | 506 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27362 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 72.6 |
| geo | 1.4 |
| probe | 340.5 |
| real_test | 476.1 |
| tcp | 47.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 17 | 7 | 70.8% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 171 | 154 | 17 | 90.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 86 | 74 | 12 | 86.0% |
| vless | 574 | 243 | 331 | 42.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 179 |
| speed:TimeoutError | 80 |
| geo:ClientOSError | 34 |
| speed:ClientOSError | 18 |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 12 |
| 204:TimeoutError | 9 |
| 204:ProxyConnectionError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6925 |
| ConnectionRefusedError | 1163 |
| gaierror | 340 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | prefer | 303 | 0.921 | 1800 |
| Surfboard-tg-mixed | 0.913 | prefer | 76 | 0.842 | 7320 |
| ermaozi | 0.718 | prefer | 24 | 0.708 | 646 |
| mheidari-all | 0.392 | observe | 459 | 0.312 | 23371 |
| ermaozi-get_subscribe | 0.331 | observe | 2 | 1.0 | 505 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5192 |
| Epodonios-all | 0.255 | observe | 0 | None | 7797 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9367 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5893 |

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
| downweight | DeltaKronecker-all | 0.216 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.167 | 1 | 5 | 6 |
| mheidari-all | 0.312 | 143 | 316 | 459 |
| ermaozi | 0.708 | 17 | 7 | 24 |
| Surfboard-tg-mixed | 0.842 | 64 | 12 | 76 |
| Au1rxx-base64 | 0.921 | 279 | 24 | 303 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23371 | yes | 5.9 | 0 |
| SoliSpirit-all | 9367 | yes | 3.75 | 0 |
| Epodonios-all | 7797 | yes | 2.84 | 0 |
| Surfboard-tg-mixed | 7320 | yes | 4.62 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.83 | 0 |
| barry-far-vless | 6122 | yes | 3.24 | 0 |
| Surfboard-tg-vless | 5893 | yes | 4.16 | 0 |
| DeltaKronecker-all | 5207 | yes | 5.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 2.23 | 0 |
| mahdibland-V2RayAggregator | 4285 | yes | 2.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 214 |
| speed | 99 |
| 204 | 32 |
| cn-block | 23 |
