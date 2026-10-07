# AutoNodes 每日报告

生成时间：2026-10-07 12:42:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 98651 |
| 去重后节点数 | 27328 |
| TCP 可达数 | 3000 |
| 真测通过数 | 429 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27328 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 90.4 |
| geo | 1.5 |
| probe | 294.6 |
| real_test | 200.0 |
| tcp | 44.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 1 | 7 | 12.5% |
| http | 41 | 25 | 16 | 61.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 147 | 139 | 8 | 94.6% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 101 | 92 | 9 | 91.1% |
| vless | 214 | 158 | 56 | 73.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 24 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 19 |
| speed:ClientOSError | 11 |
| speed:TimeoutError | 8 |
| geo:ClientOSError | 6 |
| geo:TimeoutError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5775 |
| ConnectionRefusedError | 1024 |
| gaierror | 458 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | prefer | 332 | 0.913 | 1830 |
| mheidari-all | 0.924 | prefer | 43 | 0.86 | 23381 |
| Surfboard-tg-mixed | 0.721 | prefer | 90 | 0.644 | 7069 |
| ermaozi | 0.644 | observe | 45 | 0.622 | 664 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7480 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9550 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5616 |

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
| downweight | ermaozi-get_subscribe | 0.145 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.125 | 1 | 7 | 8 |
| DeltaKronecker-all | 0.143 | 1 | 6 | 7 |
| ermaozi | 0.622 | 28 | 17 | 45 |
| Surfboard-tg-mixed | 0.644 | 58 | 32 | 90 |
| mheidari-all | 0.86 | 37 | 6 | 43 |
| Au1rxx-base64 | 0.913 | 303 | 29 | 332 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23381 | yes | 6.48 | 0 |
| SoliSpirit-all | 9550 | yes | 4.86 | 0 |
| Epodonios-all | 7480 | yes | 0.27 | 0 |
| Surfboard-tg-mixed | 7069 | yes | 4.45 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5861 | yes | 1.26 | 0 |
| Surfboard-tg-vless | 5616 | yes | 4.24 | 0 |
| DeltaKronecker-all | 5344 | yes | 6.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 5138 | yes | 3.08 | 0 |
| mahdibland-V2RayAggregator | 4418 | yes | 3.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 44 |
| cn-block | 25 |
| speed | 20 |
| geo | 11 |
