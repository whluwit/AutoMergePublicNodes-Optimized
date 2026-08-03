# AutoNodes 每日报告

生成时间：2026-08-03 14:33:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83611 |
| 去重后节点数 | 24679 |
| TCP 可达数 | 3000 |
| 真测通过数 | 551 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24679 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 33.1 |
| geo | 1.4 |
| probe | 57.6 |
| real_test | 142.6 |
| tcp | 37.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 67 | 0 | 100.0% |
| hysteria2 | 17 | 14 | 3 | 82.4% |
| shadowsocks | 142 | 116 | 26 | 81.7% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 18 | 17 | 1 | 94.4% |
| vless | 556 | 335 | 221 | 60.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 82 |
| 204:ProxyError | 36 |
| speed:TimeoutError | 28 |
| geo:TimeoutError | 25 |
| cn-block:TimeoutError | 25 |
| speed:ClientOSError | 17 |
| 204:TimeoutError | 15 |
| 204:ClientOSError | 10 |
| cn-block:ProxyError | 7 |
| cn-block:ClientOSError | 5 |
| speed:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5064 |
| ConnectionRefusedError | 804 |
| OSError | 226 |
| gaierror | 224 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.99 | prefer | 69 | 1.0 | 92 |
| Au1rxx-base64 | 0.798 | prefer | 518 | 0.732 | 1692 |
| mheidari-all | 0.577 | observe | 181 | 0.497 | 18776 |
| Surfboard-tg-mixed | 0.515 | observe | 16 | 0.5 | 5293 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3833 |
| DeltaKronecker-all | 0.27 | observe | 17 | 0.176 | 6205 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 54 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5285 |
| Epodonios-all | 0.255 | observe | 0 | None | 5891 |
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
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.176 | 3 | 14 | 17 |
| mheidari-all | 0.497 | 90 | 91 | 181 |
| Surfboard-tg-mixed | 0.5 | 8 | 8 | 16 |
| Au1rxx-base64 | 0.732 | 379 | 139 | 518 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 69 | 0 | 69 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18776 | yes | 5.28 | 0 |
| SoliSpirit-all | 6783 | yes | 4.18 | 0 |
| DeltaKronecker-all | 6205 | yes | 5.78 | 0 |
| Epodonios-all | 5891 | yes | 6.31 | 0 |
| Surfboard-tg-mixed | 5293 | yes | 4.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 5285 | yes | 3.28 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 3.21 | 0 |
| barry-far-vless | 4526 | yes | 2.72 | 0 |
| Surfboard-tg-vless | 4162 | yes | 3.37 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 109 |
| 204 | 61 |
| speed | 47 |
| cn-block | 37 |
