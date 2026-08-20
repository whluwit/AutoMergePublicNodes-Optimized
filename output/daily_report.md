# AutoNodes 每日报告

生成时间：2026-08-20 18:38:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 95088 |
| 去重后节点数 | 25211 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1125 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25211 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 26.3 |
| geo | 1.4 |
| probe | 75.6 |
| real_test | 234.1 |
| tcp | 38.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 174 | 162 | 12 | 93.1% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 653 | 647 | 6 | 99.1% |
| vless | 267 | 182 | 85 | 68.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 40 |
| speed:TimeoutError | 14 |
| geo:TimeoutError | 11 |
| cn-block:ClientOSError | 10 |
| 204:TimeoutError | 9 |
| speed:ClientOSError | 8 |
| cn-block:TimeoutError | 6 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4953 |
| ConnectionRefusedError | 994 |
| gaierror | 626 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 563 | 0.966 | 1789 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.985 | prefer | 145 | 0.91 | 6460 |
| mheidari-all | 0.909 | prefer | 402 | 0.831 | 22064 |
| DeltaKronecker-all | 0.352 | observe | 6 | 0.5 | 6781 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| Epodonios-all | 0.255 | observe | 0 | None | 7182 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7349 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5173 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 3 | 3 | 6 |
| mheidari-all | 0.831 | 334 | 68 | 402 |
| Surfboard-tg-mixed | 0.91 | 132 | 13 | 145 |
| Au1rxx-base64 | 0.966 | 544 | 19 | 563 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22064 | yes | 3.49 | 0 |
| SoliSpirit-all | 7349 | yes | 2.24 | 0 |
| Epodonios-all | 7182 | yes | 3.61 | 0 |
| DeltaKronecker-all | 6781 | yes | 3.73 | 0 |
| Surfboard-tg-mixed | 6460 | yes | 2.41 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.35 | 0 |
| barry-far-vless | 5501 | yes | 0.72 | 0 |
| Surfboard-tg-vless | 5173 | yes | 2.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 1.48 | 0 |
| mahdibland-V2RayAggregator | 4586 | yes | 0.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 53 |
| speed | 22 |
| cn-block | 17 |
| 204 | 13 |
