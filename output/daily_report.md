# AutoNodes 每日报告

生成时间：2026-09-30 21:55:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 97984 |
| 去重后节点数 | 27231 |
| TCP 可达数 | 3000 |
| 真测通过数 | 439 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27231 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 71.8 |
| geo | 1.4 |
| probe | 190.3 |
| real_test | 143.5 |
| tcp | 45.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 24 | 18 | 6 | 75.0% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 174 | 161 | 13 | 92.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 13 | 13 | 0 | 100.0% |
| vless | 291 | 225 | 66 | 77.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 43 |
| cn-block:TimeoutError | 12 |
| 204:ProxyError | 11 |
| 204:TimeoutError | 11 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6425 |
| ConnectionRefusedError | 1001 |
| gaierror | 417 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.911 | prefer | 334 | 0.841 | 1803 |
| Surfboard-tg-mixed | 0.911 | prefer | 63 | 0.841 | 7200 |
| mheidari-all | 0.909 | prefer | 103 | 0.835 | 22901 |
| zhangkai | 0.76 | prefer | 14 | 1.0 | 144 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 5434 |
| tg-oneclickvpnkeys | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7696 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9724 |

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
| downweight | ermaozi-get_subscribe | 0.248 | 9 | 0.333 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.333 | 3 | 6 | 9 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.835 | 86 | 17 | 103 |
| Surfboard-tg-mixed | 0.841 | 53 | 10 | 63 |
| Au1rxx-base64 | 0.841 | 281 | 53 | 334 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 14 | 0 | 14 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22901 | yes | 3.99 | 0 |
| SoliSpirit-all | 9724 | yes | 2.06 | 0 |
| Epodonios-all | 7696 | yes | 4.59 | 0 |
| Surfboard-tg-mixed | 7200 | yes | 3.0 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.3 | 0 |
| barry-far-vless | 6072 | yes | 2.29 | 0 |
| Surfboard-tg-vless | 5833 | yes | 2.63 | 0 |
| DeltaKronecker-all | 5434 | yes | 4.77 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 0.63 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 2.21 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 45 |
| 204 | 23 |
| cn-block | 18 |
| geo | 2 |
