# AutoNodes 每日报告

生成时间：2026-08-19 01:04:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 82078 |
| 去重后节点数 | 22293 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1365 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22293 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 31.4 |
| geo | 1.4 |
| probe | 74.9 |
| real_test | 269.4 |
| tcp | 34.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 149 | 145 | 4 | 97.3% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 890 | 878 | 12 | 98.7% |
| vless | 367 | 192 | 175 | 52.3% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 97 |
| speed:TimeoutError | 41 |
| geo:ClientOSError | 16 |
| speed:ClientOSError | 13 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4437 |
| ConnectionRefusedError | 885 |
| gaierror | 378 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 821 | 0.99 | 1745 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.889 | prefer | 171 | 0.813 | 6360 |
| mheidari-all | 0.823 | prefer | 367 | 0.744 | 16675 |
| nscl5-all | 0.489 | observe | 6 | 0.833 | 3330 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| ninja-vless | 0.279 | observe | 2 | 0.5 | 1791 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5068 |
| Epodonios-all | 0.255 | observe | 0 | None | 6993 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3983 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.186 | 64 | 0.094 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.094 | 6 | 58 | 64 |
| ninja-vless | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.744 | 273 | 94 | 367 |
| Surfboard-tg-mixed | 0.813 | 139 | 32 | 171 |
| nscl5-all | 0.833 | 5 | 1 | 6 |
| Au1rxx-base64 | 0.99 | 813 | 8 | 821 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16675 | yes | 4.69 | 0 |
| SoliSpirit-all | 7100 | yes | 3.79 | 0 |
| Epodonios-all | 6993 | yes | 0.68 | 0 |
| Surfboard-tg-mixed | 6360 | yes | 5.15 | 0 |
| DeltaKronecker-all | 5725 | yes | 4.85 | 0 |
| barry-far-vless | 5194 | yes | 1.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 5068 | yes | 3.02 | 0 |
| Surfboard-tg-vless | 4899 | yes | 3.64 | 0 |
| mahdibland-V2RayAggregator | 4035 | yes | 2.88 | 0 |
| MatinGhanbari-all-sub | 3983 | yes | 1.11 | 0 |

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
| geo | 113 |
| speed | 54 |
| cn-block | 20 |
| 204 | 8 |
