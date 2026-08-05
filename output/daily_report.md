# AutoNodes 每日报告

生成时间：2026-08-05 14:00:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 86793 |
| 去重后节点数 | 24110 |
| TCP 可达数 | 3000 |
| 真测通过数 | 494 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24110 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 33.8 |
| geo | 1.4 |
| probe | 46.2 |
| real_test | 92.0 |
| tcp | 35.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 153 | 137 | 16 | 89.5% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 155 | 152 | 3 | 98.1% |
| vless | 234 | 161 | 73 | 68.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 27 |
| 204:TimeoutError | 14 |
| speed:TimeoutError | 11 |
| 204:ProxyError | 9 |
| geo:ClientOSError | 8 |
| cn-block:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4643 |
| ConnectionRefusedError | 822 |
| gaierror | 357 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.989 | prefer | 409 | 0.929 | 1544 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.698 | observe | 129 | 0.62 | 5783 |
| mheidari-all | 0.541 | observe | 19 | 0.474 | 20132 |
| DeltaKronecker-all | 0.337 | observe | 7 | 0.429 | 5316 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 4655 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5260 |
| Epodonios-all | 0.255 | observe | 0 | None | 6386 |
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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.429 | 3 | 4 | 7 |
| mheidari-all | 0.474 | 9 | 10 | 19 |
| Surfboard-tg-mixed | 0.62 | 80 | 49 | 129 |
| Au1rxx-base64 | 0.929 | 380 | 29 | 409 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20132 | yes | 5.51 | 0 |
| SoliSpirit-all | 7119 | yes | 4.15 | 0 |
| Epodonios-all | 6386 | yes | 2.98 | 0 |
| Surfboard-tg-mixed | 5783 | yes | 3.56 | 0 |
| DeltaKronecker-all | 5316 | yes | 5.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 5260 | yes | 2.61 | 0 |
| mahdibland-V2RayAggregator | 5147 | yes | 2.8 | 0 |
| barry-far-vless | 4943 | yes | 1.56 | 0 |
| xiaoji235-airport-v2ray-all | 4655 | yes | 2.24 | 0 |
| Surfboard-tg-vless | 4628 | yes | 4.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 36 |
| 204 | 28 |
| speed | 16 |
| cn-block | 13 |
