# AutoNodes 每日报告

生成时间：2026-08-21 01:07:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 95474 |
| 去重后节点数 | 25198 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1155 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25198 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 29.1 |
| geo | 1.4 |
| probe | 74.0 |
| real_test | 210.2 |
| tcp | 40.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 110 | 110 | 0 | 100.0% |
| hysteria2 | 33 | 32 | 1 | 97.0% |
| shadowsocks | 206 | 197 | 9 | 95.6% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 653 | 639 | 14 | 97.9% |
| vless | 354 | 172 | 182 | 48.6% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 81 |
| geo:ClientOSError | 41 |
| speed:TimeoutError | 40 |
| cn-block:TimeoutError | 19 |
| speed:ClientOSError | 11 |
| cn-block:ClientOSError | 5 |
| 204:TimeoutError | 4 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5197 |
| ConnectionRefusedError | 967 |
| gaierror | 507 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 548 | 0.989 | 1663 |
| zhangkai | 0.997 | prefer | 111 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.872 | prefer | 287 | 0.794 | 6424 |
| mheidari-all | 0.812 | prefer | 363 | 0.733 | 21987 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3031 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| Epodonios-all | 0.255 | observe | 0 | None | 7184 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3990 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7352 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5136 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.22 | 48 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.125 | 6 | 42 | 48 |
| mheidari-all | 0.733 | 266 | 97 | 363 |
| Surfboard-tg-mixed | 0.794 | 228 | 59 | 287 |
| Au1rxx-base64 | 0.989 | 542 | 6 | 548 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 111 | 0 | 111 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21987 | yes | 4.77 | 0 |
| SoliSpirit-all | 7352 | yes | 3.46 | 0 |
| Epodonios-all | 7184 | yes | 3.83 | 0 |
| DeltaKronecker-all | 6781 | yes | 4.75 | 0 |
| Surfboard-tg-mixed | 6424 | yes | 2.38 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.55 | 0 |
| barry-far-vless | 5451 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 5136 | yes | 5.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 1.83 | 0 |
| mahdibland-V2RayAggregator | 4586 | yes | 0.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 123 |
| speed | 51 |
| cn-block | 25 |
| 204 | 9 |
