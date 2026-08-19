# AutoNodes 每日报告

生成时间：2026-08-19 12:41:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82517 |
| 去重后节点数 | 22537 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1129 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22537 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 28.2 |
| geo | 1.2 |
| probe | 65.5 |
| real_test | 187.4 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 110 | 2 | 98.2% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 137 | 123 | 14 | 89.8% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 715 | 711 | 4 | 99.4% |
| vless | 220 | 173 | 47 | 78.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 11 |
| 204:TimeoutError | 10 |
| geo:ClientOSError | 9 |
| speed:TimeoutError | 7 |
| geo:TimeoutError | 7 |
| 204:ProxyError | 7 |
| cn-block:ProxyError | 6 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4792 |
| ConnectionRefusedError | 850 |
| gaierror | 420 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 614 | 0.985 | 1765 |
| mheidari-all | 1.0 | prefer | 314 | 0.924 | 16605 |
| zhangkai | 0.971 | prefer | 113 | 0.973 | 144 |
| Surfboard-tg-mixed | 0.911 | prefer | 140 | 0.836 | 6360 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3330 |
| DeltaKronecker-all | 0.382 | observe | 14 | 0.357 | 6390 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5067 |
| Epodonios-all | 0.255 | observe | 0 | None | 7081 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7049 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.357 | 5 | 9 | 14 |
| Surfboard-tg-mixed | 0.836 | 117 | 23 | 140 |
| mheidari-all | 0.924 | 290 | 24 | 314 |
| zhangkai | 0.973 | 110 | 3 | 113 |
| Au1rxx-base64 | 0.985 | 605 | 9 | 614 |
| nscl5-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16605 | yes | 4.1 | 0 |
| Epodonios-all | 7081 | yes | 2.63 | 0 |
| SoliSpirit-all | 7049 | yes | 2.38 | 0 |
| DeltaKronecker-all | 6390 | yes | 2.13 | 0 |
| Surfboard-tg-mixed | 6360 | yes | 3.43 | 0 |
| barry-far-vless | 5240 | yes | 0.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 5067 | yes | 1.35 | 0 |
| Surfboard-tg-vless | 4918 | yes | 2.91 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.75 | 0 |
| mahdibland-V2RayAggregator | 3995 | yes | 2.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 21 |
| cn-block | 20 |
| geo | 16 |
| speed | 12 |
