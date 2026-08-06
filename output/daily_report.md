# AutoNodes 每日报告

生成时间：2026-08-06 13:58:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 89497 |
| 去重后节点数 | 24511 |
| TCP 可达数 | 3000 |
| 真测通过数 | 454 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24511 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 40.4 |
| geo | 1.4 |
| probe | 48.6 |
| real_test | 93.4 |
| tcp | 36.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 22 | 16 | 6 | 72.7% |
| shadowsocks | 160 | 139 | 21 | 86.9% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 159 | 156 | 3 | 98.1% |
| vless | 185 | 119 | 66 | 64.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 24 |
| geo:ClientOSError | 16 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 12 |
| 204:ProxyError | 9 |
| 204:ClientOSError | 9 |
| speed:TimeoutError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| speed:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4962 |
| ConnectionRefusedError | 815 |
| gaierror | 296 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | prefer | 382 | 0.919 | 1538 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| mheidari-all | 0.622 | observe | 15 | 0.667 | 20767 |
| Surfboard-tg-mixed | 0.613 | observe | 118 | 0.534 | 5922 |
| DeltaKronecker-all | 0.543 | observe | 13 | 0.615 | 5897 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 5184 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5219 |
| Epodonios-all | 0.255 | observe | 0 | None | 6534 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7365 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.534 | 63 | 55 | 118 |
| DeltaKronecker-all | 0.615 | 8 | 5 | 13 |
| mheidari-all | 0.667 | 10 | 5 | 15 |
| Au1rxx-base64 | 0.919 | 351 | 31 | 382 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20767 | yes | 4.18 | 0 |
| SoliSpirit-all | 7365 | yes | 3.58 | 0 |
| Epodonios-all | 6534 | yes | 5.46 | 0 |
| Surfboard-tg-mixed | 5922 | yes | 4.37 | 0 |
| DeltaKronecker-all | 5897 | yes | 4.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 5219 | yes | 1.85 | 0 |
| mahdibland-V2RayAggregator | 5212 | yes | 2.29 | 0 |
| xiaoji235-airport-v2ray-all | 5184 | yes | 1.53 | 0 |
| barry-far-vless | 5092 | yes | 2.0 | 0 |
| Surfboard-tg-vless | 4784 | yes | 2.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 41 |
| 204 | 30 |
| cn-block | 22 |
| speed | 6 |
