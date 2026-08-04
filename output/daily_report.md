# AutoNodes 每日报告

生成时间：2026-08-04 02:08:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 85812 |
| 去重后节点数 | 24670 |
| TCP 可达数 | 3000 |
| 真测通过数 | 692 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24670 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 26.6 |
| geo | 1.5 |
| probe | 60.8 |
| real_test | 177.8 |
| tcp | 37.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 67 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 160 | 153 | 7 | 95.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 84 | 73 | 11 | 86.9% |
| vless | 825 | 378 | 447 | 45.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 242 |
| speed:TimeoutError | 82 |
| speed:ClientOSError | 58 |
| geo:ClientOSError | 50 |
| cn-block:TimeoutError | 18 |
| 204:ProxyError | 5 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4950 |
| ConnectionRefusedError | 789 |
| gaierror | 335 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 67 | 1.0 | 92 |
| Au1rxx-base64 | 0.903 | prefer | 617 | 0.836 | 1692 |
| Surfboard-tg-mixed | 0.478 | observe | 131 | 0.397 | 5262 |
| DeltaKronecker-all | 0.269 | observe | 35 | 0.171 | 6205 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| Epodonios-all | 0.255 | observe | 0 | None | 5848 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6833 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4123 |
| barry-far-vless | 0.255 | observe | 0 | None | 4484 |

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
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.247 | 303 | 0.165 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.165 | 50 | 253 | 303 |
| DeltaKronecker-all | 0.171 | 6 | 29 | 35 |
| Surfboard-tg-mixed | 0.397 | 52 | 79 | 131 |
| Au1rxx-base64 | 0.836 | 516 | 101 | 617 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 67 | 0 | 67 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19963 | yes | 3.68 | 0 |
| SoliSpirit-all | 6833 | yes | 3.42 | 0 |
| DeltaKronecker-all | 6205 | yes | 4.1 | 0 |
| Epodonios-all | 5848 | yes | 3.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 5285 | yes | 2.01 | 0 |
| Surfboard-tg-mixed | 5262 | yes | 2.54 | 0 |
| mahdibland-V2RayAggregator | 5152 | yes | 0.47 | 0 |
| xiaoji235-airport-v2ray-all | 5127 | yes | 1.11 | 0 |
| barry-far-vless | 4484 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 4123 | yes | 2.27 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 292 |
| speed | 141 |
| cn-block | 21 |
| 204 | 13 |
