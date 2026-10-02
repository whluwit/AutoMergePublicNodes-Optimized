# AutoNodes 每日报告

生成时间：2026-10-02 17:28:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98378 |
| 去重后节点数 | 27127 |
| TCP 可达数 | 3000 |
| 真测通过数 | 338 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27127 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 99.9 |
| geo | 1.2 |
| probe | 215.7 |
| real_test | 168.0 |
| tcp | 47.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 3 | 2 | 60.0% |
| http | 24 | 12 | 12 | 50.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 141 | 125 | 16 | 88.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 18 | 10 | 8 | 55.6% |
| vless | 224 | 172 | 52 | 76.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 29 |
| 204:TimeoutError | 18 |
| 204:ProxyConnectionError | 13 |
| speed:TimeoutError | 10 |
| speed:ClientOSError | 6 |
| 204:ProxyError | 6 |
| geo:TimeoutError | 4 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 2 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6696 |
| ConnectionRefusedError | 1141 |
| gaierror | 362 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.929 | prefer | 275 | 0.862 | 1750 |
| Surfboard-tg-mixed | 0.819 | prefer | 44 | 0.75 | 7244 |
| mheidari-all | 0.772 | prefer | 76 | 0.697 | 22996 |
| ermaozi | 0.506 | observe | 25 | 0.48 | 620 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5276 |
| Epodonios-all | 0.255 | observe | 0 | None | 7739 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9417 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5909 |

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
| DeltaKronecker-all | 0.167 | 1 | 5 | 6 |
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| ermaozi | 0.48 | 12 | 13 | 25 |
| mheidari-all | 0.697 | 53 | 23 | 76 |
| Surfboard-tg-mixed | 0.75 | 33 | 11 | 44 |
| Au1rxx-base64 | 0.862 | 237 | 38 | 275 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22996 | yes | 4.71 | 0 |
| SoliSpirit-all | 9417 | yes | 5.44 | 0 |
| Epodonios-all | 7739 | yes | 5.57 | 0 |
| Surfboard-tg-mixed | 7244 | yes | 4.1 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.54 | 0 |
| barry-far-vless | 6150 | yes | 2.62 | 0 |
| Surfboard-tg-vless | 5909 | yes | 3.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 5276 | yes | 2.34 | 0 |
| DeltaKronecker-all | 4981 | yes | 5.68 | 0 |
| mahdibland-V2RayAggregator | 4310 | yes | 1.87 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 39 |
| cn-block | 33 |
| speed | 16 |
| geo | 5 |
