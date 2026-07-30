# AutoNodes 每日报告

生成时间：2026-07-30 13:52:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 79209 |
| 去重后节点数 | 23080 |
| TCP 可达数 | 3000 |
| 真测通过数 | 408 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23080 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 42.1 |
| geo | 1.5 |
| probe | 54.6 |
| real_test | 113.8 |
| tcp | 32.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 139 | 112 | 27 | 80.6% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 29 | 18 | 11 | 62.1% |
| vless | 242 | 154 | 88 | 63.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 33 |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 19 |
| geo:ClientOSError | 18 |
| speed:TimeoutError | 13 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4549 |
| ConnectionRefusedError | 741 |
| gaierror | 246 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | prefer | 113 | 1.0 | 129 |
| Au1rxx-base64 | 0.838 | prefer | 232 | 0.784 | 1399 |
| Surfboard-tg-mixed | 0.678 | observe | 110 | 0.6 | 5442 |
| DeltaKronecker-all | 0.625 | observe | 75 | 0.547 | 5759 |
| mheidari-all | 0.421 | observe | 6 | 0.667 | 16336 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5342 |
| Epodonios-all | 0.255 | observe | 0 | None | 6193 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.547 | 41 | 34 | 75 |
| Surfboard-tg-mixed | 0.6 | 66 | 44 | 110 |
| mheidari-all | 0.667 | 4 | 2 | 6 |
| Au1rxx-base64 | 0.784 | 182 | 50 | 232 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16336 | yes | 4.59 | 0 |
| SoliSpirit-all | 7149 | yes | 4.03 | 0 |
| Epodonios-all | 6193 | yes | 2.53 | 0 |
| DeltaKronecker-all | 5759 | yes | 4.6 | 0 |
| Surfboard-tg-mixed | 5442 | yes | 2.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5342 | yes | 1.87 | 0 |
| mahdibland-V2RayAggregator | 5029 | yes | 2.36 | 0 |
| barry-far-vless | 4667 | yes | 1.53 | 0 |
| Surfboard-tg-vless | 4363 | yes | 3.13 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 1.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 51 |
| 204 | 35 |
| cn-block | 23 |
| speed | 23 |
