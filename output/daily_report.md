# AutoNodes 每日报告

生成时间：2026-08-01 02:30:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 78568 |
| 去重后节点数 | 22801 |
| TCP 可达数 | 3000 |
| 真测通过数 | 881 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22801 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 36.0 |
| geo | 1.4 |
| probe | 79.1 |
| real_test | 260.6 |
| tcp | 34.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 80 | 80 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 165 | 152 | 13 | 92.1% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 41 | 36 | 5 | 87.8% |
| vless | 1305 | 594 | 711 | 45.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 271 |
| speed:ClientOSError | 159 |
| cn-block:TimeoutError | 113 |
| geo:ClientOSError | 82 |
| speed:TimeoutError | 67 |
| 204:TimeoutError | 12 |
| cn-block:ClientOSError | 11 |
| 204:ProxyError | 10 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4620 |
| ConnectionRefusedError | 748 |
| OSError | 223 |
| gaierror | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 80 | 1.0 | 110 |
| Au1rxx-base64 | 0.951 | prefer | 518 | 0.886 | 1661 |
| Surfboard-tg-mixed | 0.563 | observe | 16 | 0.562 | 5432 |
| DeltaKronecker-all | 0.415 | observe | 980 | 0.335 | 5144 |
| nscl5-all | 0.362 | observe | 2 | 1.0 | 1258 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5507 |
| Epodonios-all | 0.255 | observe | 0 | None | 6122 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6608 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.239 | 12 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.167 | 2 | 10 | 12 |
| DeltaKronecker-all | 0.335 | 328 | 652 | 980 |
| Surfboard-tg-mixed | 0.562 | 9 | 7 | 16 |
| Au1rxx-base64 | 0.886 | 459 | 59 | 518 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 80 | 0 | 80 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16450 | yes | 4.86 | 0 |
| SoliSpirit-all | 6608 | yes | 3.63 | 0 |
| Epodonios-all | 6122 | yes | 5.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 5507 | yes | 1.43 | 0 |
| Surfboard-tg-mixed | 5432 | yes | 3.89 | 0 |
| DeltaKronecker-all | 5144 | yes | 5.08 | 0 |
| mahdibland-V2RayAggregator | 5081 | yes | 2.97 | 0 |
| barry-far-vless | 4596 | yes | 1.72 | 0 |
| Surfboard-tg-vless | 4234 | yes | 3.66 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 354 |
| speed | 228 |
| cn-block | 126 |
| 204 | 25 |
