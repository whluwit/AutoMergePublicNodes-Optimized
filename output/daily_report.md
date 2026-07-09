# AutoNodes 每日报告

生成时间：2026-07-09 14:51:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79768 |
| 去重后节点数 | 23975 |
| TCP 可达数 | 3000 |
| 真测通过数 | 345 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23975 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 32.4 |
| geo | 1.3 |
| probe | 51.7 |
| real_test | 96.6 |
| tcp | 32.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 116 | 107 | 9 | 92.2% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 183 | 125 | 58 | 68.3% |
| vless | 185 | 63 | 122 | 34.1% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 42 |
| geo:TimeoutError | 41 |
| speed:ClientOSError | 33 |
| 204:TimeoutError | 17 |
| 204:ClientOSError | 15 |
| cn-block:ProxyError | 12 |
| geo:ClientOSError | 10 |
| geo:ProxyError | 8 |
| speed:ProxyError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:TimeoutError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4360 |
| ConnectionRefusedError | 847 |
| gaierror | 340 |
| OSError | 175 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.935 | prefer | 55 | 0.945 | 120 |
| Surfboard-tg-mixed | 0.837 | prefer | 109 | 0.761 | 5805 |
| DeltaKronecker-all | 0.781 | prefer | 105 | 0.705 | 7533 |
| mheidari-all | 0.512 | observe | 225 | 0.431 | 16991 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 2703 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4306 |
| Epodonios-all | 0.255 | observe | 0 | None | 6648 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7014 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 8 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.431 | 97 | 128 | 225 |
| DeltaKronecker-all | 0.705 | 74 | 31 | 105 |
| Surfboard-tg-mixed | 0.761 | 83 | 26 | 109 |
| Au1rxx-base64 | 0.945 | 52 | 3 | 55 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16991 | yes | 3.6 | 0 |
| DeltaKronecker-all | 7533 | yes | 3.57 | 0 |
| SoliSpirit-all | 7014 | yes | 2.82 | 0 |
| Epodonios-all | 6648 | yes | 1.9 | 0 |
| Surfboard-tg-mixed | 5805 | yes | 2.24 | 0 |
| mahdibland-V2RayAggregator | 5440 | yes | 0.46 | 0 |
| barry-far-vless | 4797 | yes | 1.6 | 0 |
| Surfboard-tg-vless | 4318 | yes | 2.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 4306 | yes | 1.89 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 1.69 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 74 |
| geo | 59 |
| speed | 38 |
| cn-block | 20 |
