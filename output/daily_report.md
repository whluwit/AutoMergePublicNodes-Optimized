# AutoNodes 每日报告

生成时间：2026-08-03 19:29:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 84760 |
| 去重后节点数 | 25157 |
| TCP 可达数 | 3000 |
| 真测通过数 | 579 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25157 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 30.3 |
| geo | 1.5 |
| probe | 59.5 |
| real_test | 138.5 |
| tcp | 37.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 67 | 0 | 100.0% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 145 | 128 | 17 | 88.3% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 67 | 63 | 4 | 94.0% |
| vless | 489 | 301 | 188 | 61.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 84 |
| 204:ProxyError | 28 |
| speed:TimeoutError | 28 |
| 204:TimeoutError | 21 |
| geo:ClientOSError | 15 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 14 |
| 204:ClientOSError | 7 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4831 |
| ConnectionRefusedError | 800 |
| gaierror | 295 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 67 | 1.0 | 92 |
| Au1rxx-base64 | 0.817 | prefer | 553 | 0.749 | 1719 |
| Surfboard-tg-mixed | 0.735 | prefer | 27 | 0.667 | 5168 |
| mheidari-all | 0.641 | observe | 137 | 0.562 | 18750 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 5127 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5285 |
| Epodonios-all | 0.255 | observe | 0 | None | 5757 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6825 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.562 | 77 | 60 | 137 |
| Surfboard-tg-mixed | 0.667 | 18 | 9 | 27 |
| Au1rxx-base64 | 0.749 | 414 | 139 | 553 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 67 | 0 | 67 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18750 | yes | 5.19 | 0 |
| SoliSpirit-all | 6825 | yes | 5.1 | 0 |
| DeltaKronecker-all | 6205 | yes | 5.43 | 0 |
| Epodonios-all | 5757 | yes | 2.95 | 0 |
| 10ium-ScrapeCategorize-Vless | 5285 | yes | 1.21 | 0 |
| Surfboard-tg-mixed | 5168 | yes | 3.39 | 0 |
| mahdibland-V2RayAggregator | 5152 | yes | 4.51 | 0 |
| xiaoji235-airport-v2ray-all | 5127 | yes | 1.76 | 0 |
| barry-far-vless | 4498 | yes | 0.9 | 0 |
| Surfboard-tg-vless | 4147 | yes | 4.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 99 |
| 204 | 56 |
| speed | 43 |
| cn-block | 17 |
