# AutoNodes 每日报告

生成时间：2026-10-11 12:14:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 5/101 |
| 原始节点数 | 98225 |
| 去重后节点数 | 27537 |
| TCP 可达数 | 3000 |
| 真测通过数 | 484 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27537 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 90.9 |
| geo | 1.3 |
| probe | 347.8 |
| real_test | 364.3 |
| tcp | 48.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 12 | 1 | 11 | 8.3% |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 152 | 127 | 25 | 83.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 159 | 149 | 10 | 93.7% |
| vless | 228 | 167 | 61 | 73.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 18 |
| speed:ClientOSError | 16 |
| geo:ClientOSError | 15 |
| geo:TimeoutError | 10 |
| 204:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 7 |
| 204:ProxyConnectionError | 5 |
| 204:ProxyError | 3 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6818 |
| ConnectionRefusedError | 1023 |
| gaierror | 342 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | prefer | 346 | 0.905 | 1835 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| mheidari-all | 0.849 | prefer | 63 | 0.778 | 23631 |
| DeltaKronecker-all | 0.79 | prefer | 29 | 0.724 | 5372 |
| Surfboard-tg-mixed | 0.713 | prefer | 118 | 0.636 | 7157 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5099 |
| Epodonios-all | 0.255 | observe | 0 | None | 7574 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9580 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5553 |

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
| downweight | ermaozi-get_subscribe | 0.226 | 14 | 0.214 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.214 | 3 | 11 | 14 |
| Surfboard-tg-mixed | 0.636 | 75 | 43 | 118 |
| DeltaKronecker-all | 0.724 | 21 | 8 | 29 |
| mheidari-all | 0.778 | 49 | 14 | 63 |
| Au1rxx-base64 | 0.905 | 313 | 33 | 346 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23631 | yes | 6.26 | 0 |
| SoliSpirit-all | 9580 | yes | 6.43 | 0 |
| Epodonios-all | 7574 | yes | 6.57 | 0 |
| Surfboard-tg-mixed | 7157 | yes | 5.57 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.69 | 0 |
| barry-far-vless | 5786 | yes | 0.82 | 0 |
| Surfboard-tg-vless | 5553 | yes | 4.55 | 0 |
| DeltaKronecker-all | 5372 | yes | 5.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 5099 | yes | 2.91 | 0 |
| mahdibland-V2RayAggregator | 4318 | yes | 3.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.083 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 33 |
| geo | 28 |
| cn-block | 26 |
| speed | 24 |
