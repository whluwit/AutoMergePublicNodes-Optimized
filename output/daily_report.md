# AutoNodes 每日报告

生成时间：2026-08-02 08:20:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 77306 |
| 去重后节点数 | 22691 |
| TCP 可达数 | 3000 |
| 真测通过数 | 781 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22691 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 45.5 |
| geo | 1.6 |
| probe | 63.3 |
| real_test | 189.6 |
| tcp | 34.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 143 | 143 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 150 | 129 | 21 | 86.0% |
| socks | 19 | 12 | 7 | 63.2% |
| trojan | 43 | 32 | 11 | 74.4% |
| vless | 788 | 444 | 344 | 56.3% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 157 |
| speed:TimeoutError | 71 |
| speed:ClientOSError | 48 |
| 204:TimeoutError | 31 |
| geo:ClientOSError | 28 |
| cn-block:TimeoutError | 20 |
| 204:ProxyError | 10 |
| 204:ClientOSError | 8 |
| cn-block:ClientOSError | 6 |
| speed:ProxyError | 4 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4636 |
| ConnectionRefusedError | 789 |
| gaierror | 300 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 219 | 0.982 | 344 |
| Au1rxx-base64 | 0.846 | prefer | 540 | 0.783 | 1589 |
| Surfboard-tg-mixed | 0.675 | observe | 119 | 0.597 | 5162 |
| DeltaKronecker-all | 0.34 | observe | 267 | 0.258 | 4549 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| mheidari-all | 0.255 | observe | 9 | 0.222 | 16553 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5486 |
| Epodonios-all | 0.255 | observe | 0 | None | 5764 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3969 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6688 |

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
| nscl5-all | 0.144 | observe | 3 | 0.0 | 0 | 1354 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| nscl5-all | 0.0 | 0 | 3 | 3 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.222 | 2 | 7 | 9 |
| DeltaKronecker-all | 0.258 | 69 | 198 | 267 |
| Surfboard-tg-mixed | 0.597 | 71 | 48 | 119 |
| Au1rxx-base64 | 0.783 | 423 | 117 | 540 |
| zhangkai | 0.982 | 215 | 4 | 219 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16553 | yes | 4.71 | 0 |
| SoliSpirit-all | 6688 | yes | 2.35 | 0 |
| Epodonios-all | 5764 | yes | 2.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 5486 | yes | 1.37 | 0 |
| Surfboard-tg-mixed | 5162 | yes | 3.75 | 0 |
| mahdibland-V2RayAggregator | 5071 | yes | 4.24 | 0 |
| DeltaKronecker-all | 4549 | yes | 4.48 | 0 |
| barry-far-vless | 4406 | yes | 1.03 | 0 |
| Surfboard-tg-vless | 4025 | yes | 3.03 | 0 |
| MatinGhanbari-all-sub | 3969 | yes | 1.51 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 185 |
| speed | 123 |
| 204 | 49 |
| cn-block | 28 |
