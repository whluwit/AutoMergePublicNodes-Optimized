# AutoNodes 每日报告

生成时间：2026-08-14 07:23:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 81304 |
| 去重后节点数 | 23172 |
| TCP 可达数 | 3000 |
| 真测通过数 | 963 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23172 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 29.8 |
| geo | 1.4 |
| probe | 73.2 |
| real_test | 210.5 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 126 | 126 | 0 | 100.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 180 | 168 | 12 | 93.3% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 371 | 354 | 17 | 95.4% |
| vless | 638 | 295 | 343 | 46.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 145 |
| geo:ClientOSError | 76 |
| speed:ClientOSError | 46 |
| speed:TimeoutError | 33 |
| 204:TimeoutError | 30 |
| 204:ProxyError | 17 |
| cn-block:TimeoutError | 16 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| speed:ClientPayloadError | 2 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4574 |
| ConnectionRefusedError | 792 |
| gaierror | 262 |
| OSError | 26 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 126 | 1.0 | 159 |
| Au1rxx-base64 | 0.989 | prefer | 691 | 0.923 | 1671 |
| Surfboard-tg-mixed | 0.71 | prefer | 25 | 0.64 | 5896 |
| DeltaKronecker-all | 0.448 | observe | 476 | 0.368 | 5969 |
| mheidari-all | 0.441 | observe | 13 | 0.462 | 16991 |
| nscl5-all | 0.326 | observe | 1 | 1.0 | 1768 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5157 |
| Epodonios-all | 0.255 | observe | 0 | None | 6586 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.368 | 175 | 301 | 476 |
| mheidari-all | 0.462 | 6 | 7 | 13 |
| Surfboard-tg-mixed | 0.64 | 16 | 9 | 25 |
| Au1rxx-base64 | 0.923 | 638 | 53 | 691 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 126 | 0 | 126 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16991 | yes | 5.68 | 0 |
| SoliSpirit-all | 7698 | yes | 3.92 | 0 |
| Epodonios-all | 6586 | yes | 4.23 | 0 |
| DeltaKronecker-all | 5969 | yes | 4.29 | 0 |
| Surfboard-tg-mixed | 5896 | yes | 3.43 | 0 |
| mahdibland-V2RayAggregator | 5332 | yes | 2.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 5157 | yes | 2.4 | 0 |
| barry-far-vless | 4975 | yes | 2.16 | 0 |
| Surfboard-tg-vless | 4633 | yes | 3.2 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.5 | 0 |

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
| geo | 222 |
| speed | 81 |
| 204 | 48 |
| cn-block | 24 |
