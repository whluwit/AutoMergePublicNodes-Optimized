# AutoNodes 每日报告

生成时间：2026-07-09 02:35:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79955 |
| 去重后节点数 | 24829 |
| TCP 可达数 | 3000 |
| 真测通过数 | 457 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24829 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 36.3 |
| geo | 1.3 |
| probe | 48.1 |
| real_test | 100.7 |
| tcp | 33.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 3 | 1 | 75.0% |
| shadowsocks | 138 | 131 | 7 | 94.9% |
| socks | 10 | 7 | 3 | 70.0% |
| trojan | 166 | 153 | 13 | 92.2% |
| vless | 325 | 120 | 205 | 36.9% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 93 |
| geo:TimeoutError | 78 |
| geo:ClientOSError | 17 |
| speed:TimeoutError | 12 |
| cn-block:TimeoutError | 10 |
| 204:ClientOSError | 7 |
| 204:TimeoutError | 6 |
| cn-block:ClientOSError | 3 |
| 204:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4746 |
| ConnectionRefusedError | 821 |
| OSError | 173 |
| gaierror | 112 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.805 | prefer | 78 | 0.808 | 129 |
| DeltaKronecker-all | 0.76 | prefer | 170 | 0.682 | 8321 |
| Surfboard-tg-mixed | 0.687 | observe | 324 | 0.608 | 5759 |
| mheidari-all | 0.661 | observe | 60 | 0.583 | 17104 |
| xiaoji235-airport-v2ray-all | 0.606 | observe | 9 | 0.889 | 2703 |
| nscl5-all | 0.26 | observe | 2 | 0.5 | 1319 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4408 |
| Epodonios-all | 0.255 | observe | 0 | None | 6606 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3969 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 2 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.583 | 35 | 25 | 60 |
| Surfboard-tg-mixed | 0.608 | 197 | 127 | 324 |
| DeltaKronecker-all | 0.682 | 116 | 54 | 170 |
| Au1rxx-base64 | 0.808 | 63 | 15 | 78 |
| xiaoji235-airport-v2ray-all | 0.889 | 8 | 1 | 9 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17104 | yes | 3.89 | 0 |
| DeltaKronecker-all | 8321 | yes | 4.39 | 0 |
| SoliSpirit-all | 6629 | yes | 2.28 | 0 |
| Epodonios-all | 6606 | yes | 0.9 | 0 |
| Surfboard-tg-mixed | 5759 | yes | 2.89 | 0 |
| mahdibland-V2RayAggregator | 5361 | yes | 0.2 | 0 |
| barry-far-vless | 4589 | yes | 1.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4408 | yes | 1.67 | 0 |
| Surfboard-tg-vless | 4275 | yes | 2.24 | 0 |
| MatinGhanbari-all-sub | 3969 | yes | 2.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 105 |
| geo | 95 |
| 204 | 15 |
| cn-block | 14 |
