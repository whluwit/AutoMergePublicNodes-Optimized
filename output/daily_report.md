# AutoNodes 每日报告

生成时间：2026-08-04 19:29:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 86061 |
| 去重后节点数 | 24512 |
| TCP 可达数 | 3000 |
| 真测通过数 | 478 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24512 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 29.7 |
| geo | 1.2 |
| probe | 52.0 |
| real_test | 110.3 |
| tcp | 37.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 51 | 50 | 1 | 98.0% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 127 | 94 | 33 | 74.0% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 158 | 154 | 4 | 97.5% |
| vless | 221 | 157 | 64 | 71.0% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 22 |
| geo:TimeoutError | 21 |
| geo:ClientOSError | 20 |
| 204:ProxyError | 15 |
| cn-block:TimeoutError | 7 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5086 |
| ConnectionRefusedError | 836 |
| gaierror | 259 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.965 | prefer | 51 | 0.98 | 72 |
| Au1rxx-base64 | 0.931 | prefer | 431 | 0.87 | 1560 |
| Surfboard-tg-mixed | 0.586 | observe | 77 | 0.506 | 5570 |
| DeltaKronecker-all | 0.474 | observe | 10 | 0.6 | 5788 |
| mheidari-all | 0.461 | observe | 11 | 0.545 | 19967 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 58 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5251 |
| Epodonios-all | 0.255 | observe | 0 | None | 6154 |
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
| tg-LonUp_M | 0.135 | observe | 1 | 0.0 | 0 | 177 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.506 | 39 | 38 | 77 |
| mheidari-all | 0.545 | 6 | 5 | 11 |
| DeltaKronecker-all | 0.6 | 6 | 4 | 10 |
| Au1rxx-base64 | 0.87 | 375 | 56 | 431 |
| zhangkai | 0.98 | 50 | 1 | 51 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19967 | yes | 5.56 | 0 |
| SoliSpirit-all | 6965 | yes | 3.96 | 0 |
| Epodonios-all | 6154 | yes | 4.95 | 0 |
| DeltaKronecker-all | 5788 | yes | 6.58 | 0 |
| Surfboard-tg-mixed | 5570 | yes | 2.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 5251 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 5141 | yes | 4.41 | 0 |
| barry-far-vless | 4787 | yes | 1.74 | 0 |
| xiaoji235-airport-v2ray-all | 4655 | yes | 1.05 | 0 |
| Surfboard-tg-vless | 4451 | yes | 4.1 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 42 |
| geo | 41 |
| cn-block | 12 |
| speed | 11 |
