# AutoNodes 每日报告

生成时间：2026-07-08 02:18:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84060 |
| 去重后节点数 | 24941 |
| TCP 可达数 | 3000 |
| 真测通过数 | 525 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24941 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 45.0 |
| geo | 1.3 |
| probe | 53.9 |
| real_test | 138.6 |
| tcp | 32.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 5 | 4 | 1 | 80.0% |
| shadowsocks | 139 | 119 | 20 | 85.6% |
| socks | 8 | 7 | 1 | 87.5% |
| trojan | 153 | 145 | 8 | 94.8% |
| vless | 560 | 208 | 352 | 37.1% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 174 |
| speed:ClientOSError | 99 |
| geo:ClientOSError | 37 |
| speed:TimeoutError | 30 |
| 204:TimeoutError | 11 |
| cn-block:TimeoutError | 10 |
| 204:ClientOSError | 8 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4629 |
| ConnectionRefusedError | 823 |
| OSError | 171 |
| gaierror | 147 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.961 | prefer | 107 | 0.888 | 5874 |
| Au1rxx-base64 | 0.719 | prefer | 75 | 0.72 | 125 |
| DeltaKronecker-all | 0.644 | observe | 147 | 0.565 | 8472 |
| mheidari-all | 0.553 | observe | 533 | 0.473 | 18232 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3640 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 170 |
| nscl5-all | 0.317 | observe | 1 | 1.0 | 1561 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4700 |
| Epodonios-all | 0.255 | observe | 0 | None | 6908 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 11 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.473 | 252 | 281 | 533 |
| DeltaKronecker-all | 0.565 | 83 | 64 | 147 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.72 | 54 | 21 | 75 |
| Surfboard-tg-mixed | 0.888 | 95 | 12 | 107 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18232 | yes | 3.84 | 0 |
| DeltaKronecker-all | 8472 | yes | 4.31 | 0 |
| SoliSpirit-all | 6912 | yes | 2.25 | 0 |
| Epodonios-all | 6908 | yes | 0.6 | 0 |
| Surfboard-tg-mixed | 5874 | yes | 2.77 | 0 |
| mahdibland-V2RayAggregator | 5339 | yes | 0.41 | 0 |
| barry-far-vless | 5099 | yes | 1.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 4700 | yes | 1.45 | 0 |
| Surfboard-tg-vless | 4417 | yes | 2.16 | 0 |
| MatinGhanbari-all-sub | 3969 | yes | 1.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 211 |
| speed | 130 |
| 204 | 25 |
| cn-block | 16 |
