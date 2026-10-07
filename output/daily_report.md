# AutoNodes 每日报告

生成时间：2026-10-07 04:10:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 97169 |
| 去重后节点数 | 27035 |
| TCP 可达数 | 3000 |
| 真测通过数 | 510 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27035 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 74.4 |
| geo | 1.3 |
| probe | 279.5 |
| real_test | 391.1 |
| tcp | 46.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 41 | 24 | 17 | 58.5% |
| hysteria2 | 26 | 23 | 3 | 88.5% |
| shadowsocks | 177 | 161 | 16 | 91.0% |
| socks | 8 | 3 | 5 | 37.5% |
| trojan | 128 | 116 | 12 | 90.6% |
| vless | 432 | 182 | 250 | 42.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 147 |
| speed:TimeoutError | 41 |
| geo:ClientOSError | 36 |
| 204:ProxyError | 27 |
| 204:TimeoutError | 16 |
| speed:ClientOSError | 11 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 9 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6726 |
| ConnectionRefusedError | 976 |
| gaierror | 364 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 309 | 0.935 | 1832 |
| Surfboard-tg-mixed | 0.7 | prefer | 198 | 0.621 | 7006 |
| ermaozi | 0.61 | observe | 41 | 0.585 | 726 |
| mheidari-all | 0.366 | observe | 250 | 0.284 | 22990 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7476 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9192 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5583 |

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
| downweight | DeltaKronecker-all | 0.193 | 10 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.1 | 1 | 9 | 10 |
| mheidari-all | 0.284 | 71 | 179 | 250 |
| ninja-vless | 0.333 | 1 | 2 | 3 |
| ermaozi | 0.585 | 24 | 17 | 41 |
| Surfboard-tg-mixed | 0.621 | 123 | 75 | 198 |
| Au1rxx-base64 | 0.935 | 289 | 20 | 309 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22990 | yes | 3.1 | 0 |
| SoliSpirit-all | 9192 | yes | 2.04 | 0 |
| Epodonios-all | 7476 | yes | 1.93 | 0 |
| Surfboard-tg-mixed | 7006 | yes | 2.48 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.98 | 0 |
| barry-far-vless | 5837 | yes | 1.53 | 0 |
| Surfboard-tg-vless | 5583 | yes | 2.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 1.42 | 0 |
| DeltaKronecker-all | 4889 | yes | 2.61 | 0 |
| mahdibland-V2RayAggregator | 4373 | yes | 1.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 184 |
| speed | 54 |
| 204 | 46 |
| cn-block | 20 |
