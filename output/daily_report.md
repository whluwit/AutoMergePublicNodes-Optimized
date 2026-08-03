# AutoNodes 每日报告

生成时间：2026-08-03 09:39:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83341 |
| 去重后节点数 | 24485 |
| TCP 可达数 | 3000 |
| 真测通过数 | 579 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24485 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 28.5 |
| geo | 1.5 |
| probe | 55.0 |
| real_test | 134.1 |
| tcp | 36.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 143 | 143 | 0 | 100.0% |
| hysteria2 | 18 | 12 | 6 | 66.7% |
| shadowsocks | 136 | 116 | 20 | 85.3% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 32 | 25 | 7 | 78.1% |
| vless | 491 | 280 | 211 | 57.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 105 |
| speed:TimeoutError | 44 |
| 204:ProxyError | 21 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 13 |
| geo:ClientOSError | 10 |
| cn-block:ProxyError | 6 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 3 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4895 |
| ConnectionRefusedError | 766 |
| gaierror | 245 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 143 | 1.0 | 344 |
| Au1rxx-base64 | 0.796 | prefer | 526 | 0.732 | 1629 |
| mheidari-all | 0.555 | observe | 17 | 0.529 | 18806 |
| Surfboard-tg-mixed | 0.397 | observe | 99 | 0.313 | 5244 |
| DeltaKronecker-all | 0.361 | observe | 30 | 0.267 | 6205 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3833 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 54 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5285 |
| Epodonios-all | 0.255 | observe | 0 | None | 5831 |

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
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.267 | 8 | 22 | 30 |
| Surfboard-tg-mixed | 0.313 | 31 | 68 | 99 |
| mheidari-all | 0.529 | 9 | 8 | 17 |
| Au1rxx-base64 | 0.732 | 385 | 141 | 526 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18806 | yes | 5.25 | 0 |
| SoliSpirit-all | 6567 | yes | 4.34 | 0 |
| DeltaKronecker-all | 6205 | yes | 5.55 | 0 |
| Epodonios-all | 5831 | yes | 6.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 5285 | yes | 3.52 | 0 |
| Surfboard-tg-mixed | 5244 | yes | 3.86 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 3.29 | 0 |
| barry-far-vless | 4467 | yes | 2.27 | 0 |
| Surfboard-tg-vless | 4132 | yes | 3.61 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 118 |
| speed | 59 |
| 204 | 45 |
| cn-block | 23 |
