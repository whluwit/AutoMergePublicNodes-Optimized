# AutoNodes 每日报告

生成时间：2026-07-09 19:41:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 78769 |
| 去重后节点数 | 23876 |
| TCP 可达数 | 3000 |
| 真测通过数 | 224 |
| verified 输出数 | 224 |
| global 输出数 | 234 |
| all 输出数 | 23876 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 27.4 |
| geo | 1.4 |
| probe | 47.0 |
| real_test | 67.4 |
| tcp | 31.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 89 | 76 | 13 | 85.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 91 | 50 | 41 | 54.9% |
| vless | 145 | 52 | 93 | 35.9% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 68 |
| 204:TimeoutError | 24 |
| geo:TimeoutError | 12 |
| geo:ClientOSError | 10 |
| 204:ProxyError | 8 |
| 204:ClientOSError | 7 |
| cn-block:ProxyError | 6 |
| cn-block:TimeoutError | 5 |
| speed:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4321 |
| ConnectionRefusedError | 836 |
| gaierror | 265 |
| OSError | 174 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.899 | prefer | 27 | 0.926 | 66 |
| Surfboard-tg-mixed | 0.629 | observe | 222 | 0.55 | 5585 |
| DeltaKronecker-all | 0.594 | observe | 68 | 0.515 | 7533 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 2703 |
| nscl5-all | 0.364 | observe | 2 | 1.0 | 1319 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4306 |
| Epodonios-all | 0.255 | observe | 0 | None | 6500 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6851 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.183 | 13 | 0.077 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.077 | 1 | 12 | 13 |
| DeltaKronecker-all | 0.515 | 35 | 33 | 68 |
| Surfboard-tg-mixed | 0.55 | 122 | 100 | 222 |
| Au1rxx-base64 | 0.926 | 25 | 2 | 27 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16918 | yes | 3.17 | 0 |
| DeltaKronecker-all | 7533 | yes | 2.94 | 0 |
| SoliSpirit-all | 6851 | yes | 1.55 | 0 |
| Epodonios-all | 6500 | yes | 1.52 | 0 |
| Surfboard-tg-mixed | 5585 | yes | 1.88 | 0 |
| mahdibland-V2RayAggregator | 5403 | yes | 1.33 | 0 |
| barry-far-vless | 4741 | yes | 1.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4306 | yes | 0.9 | 0 |
| Surfboard-tg-vless | 4106 | yes | 2.53 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 72 |
| 204 | 39 |
| geo | 24 |
| cn-block | 14 |
