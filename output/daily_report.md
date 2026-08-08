# AutoNodes 每日报告

生成时间：2026-08-08 12:41:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83601 |
| 去重后节点数 | 23622 |
| TCP 可达数 | 3000 |
| 真测通过数 | 466 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23622 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 42.7 |
| geo | 1.4 |
| probe | 53.5 |
| real_test | 111.1 |
| tcp | 35.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 166 | 147 | 19 | 88.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 157 | 149 | 8 | 94.9% |
| vless | 239 | 123 | 116 | 51.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 29 |
| 204:TimeoutError | 24 |
| 204:ProxyError | 23 |
| geo:TimeoutError | 22 |
| speed:ClientOSError | 13 |
| speed:TimeoutError | 12 |
| cn-block:TimeoutError | 9 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4832 |
| ConnectionRefusedError | 804 |
| gaierror | 343 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | prefer | 344 | 0.933 | 1488 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| DeltaKronecker-all | 0.569 | observe | 231 | 0.489 | 5347 |
| Surfboard-tg-mixed | 0.547 | observe | 9 | 0.778 | 6590 |
| mheidari-all | 0.4 | observe | 4 | 0.75 | 17827 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 196 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5450 |
| Epodonios-all | 0.255 | observe | 0 | None | 7202 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.489 | 113 | 118 | 231 |
| mheidari-all | 0.75 | 3 | 1 | 4 |
| Surfboard-tg-mixed | 0.778 | 7 | 2 | 9 |
| Au1rxx-base64 | 0.933 | 321 | 23 | 344 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17827 | yes | 4.59 | 0 |
| SoliSpirit-all | 7636 | yes | 2.39 | 0 |
| Epodonios-all | 7202 | yes | 2.66 | 0 |
| Surfboard-tg-mixed | 6590 | yes | 3.25 | 0 |
| barry-far-vless | 5747 | yes | 1.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 5450 | yes | 2.03 | 0 |
| DeltaKronecker-all | 5347 | yes | 4.65 | 0 |
| Surfboard-tg-vless | 5299 | yes | 2.85 | 0 |
| mahdibland-V2RayAggregator | 5162 | yes | 2.44 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 51 |
| 204 | 51 |
| speed | 26 |
| cn-block | 17 |
