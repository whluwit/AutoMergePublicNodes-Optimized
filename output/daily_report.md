# AutoNodes 每日报告

生成时间：2026-10-03 11:08:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 98889 |
| 去重后节点数 | 27223 |
| TCP 可达数 | 3000 |
| 真测通过数 | 397 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27223 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 38.0 |
| geo | 1.1 |
| probe | 258.5 |
| real_test | 179.7 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 2 | 3 | 40.0% |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 159 | 143 | 16 | 89.9% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 42 | 22 | 20 | 52.4% |
| vless | 231 | 192 | 39 | 83.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 28 |
| cn-block:TimeoutError | 20 |
| geo:TimeoutError | 9 |
| speed:TimeoutError | 6 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| geo:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6719 |
| ConnectionRefusedError | 1168 |
| gaierror | 380 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 246 | 0.935 | 1738 |
| ermaozi | 0.949 | prefer | 24 | 0.958 | 645 |
| mheidari-all | 0.807 | prefer | 53 | 0.736 | 23264 |
| Surfboard-tg-mixed | 0.787 | prefer | 131 | 0.71 | 7251 |
| DeltaKronecker-all | 0.602 | observe | 17 | 0.588 | 5207 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5192 |
| Epodonios-all | 0.255 | observe | 0 | None | 7748 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9359 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5966 |

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
| downweight | ermaozi-get_subscribe | 0.24 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| DeltaKronecker-all | 0.588 | 10 | 7 | 17 |
| Surfboard-tg-mixed | 0.71 | 93 | 38 | 131 |
| mheidari-all | 0.736 | 39 | 14 | 53 |
| Au1rxx-base64 | 0.935 | 230 | 16 | 246 |
| ermaozi | 0.958 | 23 | 1 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23264 | yes | 3.26 | 0 |
| SoliSpirit-all | 9359 | yes | 1.35 | 0 |
| Epodonios-all | 7748 | yes | 1.75 | 0 |
| Surfboard-tg-mixed | 7251 | yes | 2.05 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.17 | 0 |
| barry-far-vless | 6206 | yes | 0.63 | 0 |
| Surfboard-tg-vless | 5966 | yes | 1.89 | 0 |
| DeltaKronecker-all | 5207 | yes | 3.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 4335 | yes | 1.57 | 0 |

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
| 204 | 35 |
| cn-block | 25 |
| geo | 11 |
| speed | 9 |
