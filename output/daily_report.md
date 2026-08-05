# AutoNodes 每日报告

生成时间：2026-08-05 08:32:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 85538 |
| 去重后节点数 | 23899 |
| TCP 可达数 | 3000 |
| 真测通过数 | 519 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23899 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 33.0 |
| geo | 1.4 |
| probe | 55.0 |
| real_test | 113.8 |
| tcp | 35.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 53 | 52 | 1 | 98.1% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 165 | 147 | 18 | 89.1% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 170 | 155 | 15 | 91.2% |
| vless | 235 | 143 | 92 | 60.9% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 48 |
| 204:TimeoutError | 18 |
| speed:TimeoutError | 16 |
| 204:ProxyError | 15 |
| speed:ClientOSError | 9 |
| geo:ClientOSError | 8 |
| cn-block:ProxyError | 6 |
| cn-block:TimeoutError | 5 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4965 |
| ConnectionRefusedError | 829 |
| gaierror | 295 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | prefer | 407 | 0.941 | 1403 |
| zhangkai | 0.967 | prefer | 53 | 0.981 | 72 |
| Surfboard-tg-mixed | 0.612 | observe | 122 | 0.533 | 5560 |
| tg-LonUp_M | 0.365 | observe | 3 | 1.0 | 176 |
| mheidari-all | 0.363 | observe | 44 | 0.273 | 20226 |
| DeltaKronecker-all | 0.267 | observe | 18 | 0.167 | 5316 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5260 |
| Epodonios-all | 0.255 | observe | 0 | None | 6163 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.167 | 3 | 15 | 18 |
| mheidari-all | 0.273 | 12 | 32 | 44 |
| Surfboard-tg-mixed | 0.533 | 65 | 57 | 122 |
| Au1rxx-base64 | 0.941 | 383 | 24 | 407 |
| zhangkai | 0.981 | 52 | 1 | 53 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20226 | yes | 4.93 | 0 |
| SoliSpirit-all | 6818 | yes | 2.82 | 0 |
| Epodonios-all | 6163 | yes | 2.74 | 0 |
| Surfboard-tg-mixed | 5560 | yes | 5.19 | 0 |
| DeltaKronecker-all | 5316 | yes | 4.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5260 | yes | 1.21 | 0 |
| mahdibland-V2RayAggregator | 5147 | yes | 2.39 | 0 |
| barry-far-vless | 4823 | yes | 1.43 | 0 |
| xiaoji235-airport-v2ray-all | 4655 | yes | 2.35 | 0 |
| Surfboard-tg-vless | 4397 | yes | 4.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 56 |
| 204 | 36 |
| speed | 25 |
| cn-block | 14 |
