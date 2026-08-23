# AutoNodes 每日报告

生成时间：2026-08-23 06:37:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 98/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 77583 |
| 去重后节点数 | 21117 |
| TCP 可达数 | 3000 |
| 真测通过数 | 796 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21117 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 34.2 |
| geo | 1.4 |
| probe | 58.5 |
| real_test | 171.7 |
| tcp | 34.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 114 | 114 | 0 | 100.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 218 | 209 | 9 | 95.9% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 147 | 134 | 13 | 91.2% |
| vless | 466 | 317 | 149 | 68.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 66 |
| speed:TimeoutError | 30 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 20 |
| speed:ClientOSError | 12 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 6 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4650 |
| ConnectionRefusedError | 827 |
| gaierror | 323 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 113 | 1.0 | 144 |
| Au1rxx-base64 | 0.996 | prefer | 490 | 0.924 | 1821 |
| Surfboard-tg-mixed | 0.891 | prefer | 146 | 0.815 | 6303 |
| mheidari-all | 0.631 | observe | 105 | 0.552 | 14434 |
| DeltaKronecker-all | 0.51 | observe | 105 | 0.429 | 5288 |
| nscl5-all | 0.483 | observe | 5 | 1.0 | 1082 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 131 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4989 |
| Epodonios-all | 0.255 | observe | 0 | None | 6860 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.429 | 45 | 60 | 105 |
| mheidari-all | 0.552 | 58 | 47 | 105 |
| Surfboard-tg-mixed | 0.815 | 119 | 27 | 146 |
| Au1rxx-base64 | 0.924 | 453 | 37 | 490 |
| ninja-vless | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| nscl5-all | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14434 | yes | 4.05 | 0 |
| SoliSpirit-all | 7111 | yes | 4.86 | 0 |
| Epodonios-all | 6860 | yes | 4.85 | 0 |
| Surfboard-tg-mixed | 6303 | yes | 3.28 | 0 |
| barry-far-vless | 5430 | yes | 1.82 | 0 |
| DeltaKronecker-all | 5288 | yes | 4.3 | 0 |
| Surfboard-tg-vless | 5154 | yes | 3.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 4989 | yes | 3.25 | 0 |
| mahdibland-V2RayAggregator | 4094 | yes | 1.31 | 0 |
| MatinGhanbari-all-sub | 3989 | yes | 2.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 87 |
| speed | 42 |
| cn-block | 29 |
| 204 | 14 |
