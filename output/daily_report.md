# AutoNodes 每日报告

生成时间：2026-07-07 14:25:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 85084 |
| 去重后节点数 | 24830 |
| TCP 可达数 | 3000 |
| 真测通过数 | 328 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24830 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 39.6 |
| geo | 1.4 |
| probe | 43.5 |
| real_test | 87.7 |
| tcp | 32.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 5 | 4 | 1 | 80.0% |
| shadowsocks | 128 | 114 | 14 | 89.1% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 186 | 156 | 30 | 83.9% |
| vless | 67 | 9 | 58 | 13.4% |
| vmess | 6 | 5 | 1 | 83.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 44 |
| 204:TimeoutError | 12 |
| 204:ClientOSError | 10 |
| geo:TimeoutError | 9 |
| geo:ClientOSError | 7 |
| cn-block:TimeoutError | 6 |
| geo:ProxyError | 6 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4668 |
| ConnectionRefusedError | 814 |
| OSError | 166 |
| gaierror | 94 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.889 | prefer | 92 | 0.815 | 18192 |
| Au1rxx-base64 | 0.882 | prefer | 55 | 0.891 | 115 |
| Surfboard-tg-mixed | 0.823 | prefer | 99 | 0.747 | 6102 |
| DeltaKronecker-all | 0.695 | observe | 146 | 0.616 | 8472 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3626 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4700 |
| Epodonios-all | 0.255 | observe | 0 | None | 7142 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.616 | 90 | 56 | 146 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.747 | 74 | 25 | 99 |
| mheidari-all | 0.815 | 75 | 17 | 92 |
| Au1rxx-base64 | 0.891 | 49 | 6 | 55 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18192 | yes | 3.53 | 0 |
| DeltaKronecker-all | 8472 | yes | 4.06 | 0 |
| SoliSpirit-all | 7271 | yes | 1.95 | 0 |
| Epodonios-all | 7142 | yes | 1.81 | 0 |
| Surfboard-tg-mixed | 6102 | yes | 2.55 | 0 |
| mahdibland-V2RayAggregator | 5338 | yes | 1.52 | 0 |
| barry-far-vless | 5254 | yes | 1.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 4700 | yes | 1.63 | 0 |
| Surfboard-tg-vless | 4575 | yes | 2.13 | 0 |
| MatinGhanbari-all-sub | 3977 | yes | 1.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 47 |
| 204 | 25 |
| geo | 22 |
| cn-block | 12 |
