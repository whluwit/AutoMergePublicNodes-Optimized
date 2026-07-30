# AutoNodes 每日报告

生成时间：2026-07-30 08:22:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78399 |
| 去重后节点数 | 22761 |
| TCP 可达数 | 3000 |
| 真测通过数 | 537 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22761 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 43.1 |
| geo | 1.4 |
| probe | 58.5 |
| real_test | 147.1 |
| tcp | 31.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 118 | 118 | 0 | 100.0% |
| hysteria2 | 17 | 14 | 3 | 82.4% |
| shadowsocks | 191 | 164 | 27 | 85.9% |
| socks | 8 | 7 | 1 | 87.5% |
| trojan | 66 | 54 | 12 | 81.8% |
| vless | 459 | 179 | 280 | 39.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 154 |
| geo:ClientOSError | 43 |
| speed:ClientOSError | 35 |
| 204:TimeoutError | 24 |
| speed:TimeoutError | 23 |
| cn-block:TimeoutError | 20 |
| cn-block:ClientOSError | 9 |
| 204:ProxyError | 8 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4355 |
| ConnectionRefusedError | 715 |
| gaierror | 294 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.998 | prefer | 118 | 1.0 | 157 |
| Au1rxx-base64 | 0.902 | prefer | 244 | 0.857 | 1201 |
| Surfboard-tg-mixed | 0.687 | observe | 166 | 0.608 | 5473 |
| DeltaKronecker-all | 0.412 | observe | 317 | 0.331 | 5759 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| mheidari-all | 0.255 | observe | 9 | 0.222 | 16334 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5342 |
| Epodonios-all | 0.255 | observe | 0 | None | 6219 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.128 | observe | 1 | 0.0 | 0 | 20 |
| roosterkid-openproxylist-v2ray | 0.133 | observe | 1 | 0.0 | 0 | 150 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.222 | 2 | 7 | 9 |
| DeltaKronecker-all | 0.331 | 105 | 212 | 317 |
| Surfboard-tg-mixed | 0.608 | 101 | 65 | 166 |
| Au1rxx-base64 | 0.857 | 209 | 35 | 244 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16334 | yes | 4.09 | 0 |
| SoliSpirit-all | 6833 | yes | 3.4 | 0 |
| Epodonios-all | 6219 | yes | 3.68 | 0 |
| DeltaKronecker-all | 5759 | yes | 4.75 | 0 |
| Surfboard-tg-mixed | 5473 | yes | 4.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5342 | yes | 2.48 | 0 |
| mahdibland-V2RayAggregator | 5029 | yes | 2.49 | 0 |
| barry-far-vless | 4657 | yes | 2.08 | 0 |
| Surfboard-tg-vless | 4282 | yes | 3.24 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 197 |
| speed | 59 |
| 204 | 36 |
| cn-block | 31 |
