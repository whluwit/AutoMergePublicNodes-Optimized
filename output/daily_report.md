# AutoNodes 每日报告

生成时间：2026-08-21 06:43:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 94187 |
| 去重后节点数 | 24566 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1214 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24566 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 39.1 |
| geo | 1.5 |
| probe | 69.1 |
| real_test | 225.5 |
| tcp | 38.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 193 | 186 | 7 | 96.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 668 | 655 | 13 | 98.1% |
| vless | 342 | 233 | 109 | 68.1% |
| vmess | 5 | 4 | 1 | 80.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 40 |
| speed:TimeoutError | 28 |
| geo:ClientOSError | 21 |
| 204:TimeoutError | 14 |
| speed:ClientOSError | 11 |
| cn-block:TimeoutError | 9 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4747 |
| ConnectionRefusedError | 934 |
| gaierror | 586 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 646 | 0.961 | 1607 |
| zhangkai | 0.997 | prefer | 111 | 1.0 | 144 |
| mheidari-all | 0.956 | prefer | 313 | 0.879 | 21864 |
| Surfboard-tg-mixed | 0.879 | prefer | 252 | 0.802 | 6375 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3031 |
| DeltaKronecker-all | 0.262 | observe | 20 | 0.15 | 6250 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5148 |
| Epodonios-all | 0.255 | observe | 0 | None | 7077 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7024 |

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
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.15 | 3 | 17 | 20 |
| Surfboard-tg-mixed | 0.802 | 202 | 50 | 252 |
| mheidari-all | 0.879 | 275 | 38 | 313 |
| Au1rxx-base64 | 0.961 | 621 | 25 | 646 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 111 | 0 | 111 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21864 | yes | 5.18 | 0 |
| Epodonios-all | 7077 | yes | 4.58 | 0 |
| SoliSpirit-all | 7024 | yes | 5.19 | 0 |
| Surfboard-tg-mixed | 6375 | yes | 3.23 | 0 |
| DeltaKronecker-all | 6250 | yes | 5.6 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.47 | 0 |
| barry-far-vless | 5415 | yes | 1.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 5148 | yes | 1.75 | 0 |
| Surfboard-tg-vless | 5092 | yes | 3.44 | 0 |
| mahdibland-V2RayAggregator | 4647 | yes | 2.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 61 |
| speed | 39 |
| 204 | 19 |
| cn-block | 13 |
