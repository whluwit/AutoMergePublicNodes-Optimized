# AutoNodes 每日报告

生成时间：2026-08-12 13:02:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 80185 |
| 去重后节点数 | 22267 |
| TCP 可达数 | 3000 |
| 真测通过数 | 596 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22267 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 30.9 |
| geo | 1.3 |
| probe | 50.4 |
| real_test | 122.4 |
| tcp | 32.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 127 | 1 | 99.2% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 161 | 149 | 12 | 92.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 121 | 114 | 7 | 94.2% |
| vless | 311 | 185 | 126 | 59.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 32 |
| geo:ClientOSError | 30 |
| 204:TimeoutError | 20 |
| geo:TimeoutError | 18 |
| speed:ClientOSError | 15 |
| cn-block:TimeoutError | 14 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4504 |
| ConnectionRefusedError | 789 |
| gaierror | 310 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 128 | 0.992 | 159 |
| Au1rxx-base64 | 0.934 | prefer | 428 | 0.869 | 1660 |
| Surfboard-tg-mixed | 0.64 | observe | 89 | 0.562 | 6040 |
| mheidari-all | 0.606 | observe | 9 | 0.889 | 16658 |
| DeltaKronecker-all | 0.513 | observe | 88 | 0.432 | 4975 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5328 |
| Epodonios-all | 0.255 | observe | 0 | None | 6671 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7619 |

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
| ermaozi | 0.175 | observe | 0 | None | 0 | 8 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.432 | 38 | 50 | 88 |
| Surfboard-tg-mixed | 0.562 | 50 | 39 | 89 |
| Au1rxx-base64 | 0.869 | 372 | 56 | 428 |
| mheidari-all | 0.889 | 8 | 1 | 9 |
| zhangkai | 0.992 | 127 | 1 | 128 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16658 | yes | 4.92 | 0 |
| SoliSpirit-all | 7619 | yes | 3.64 | 0 |
| Epodonios-all | 6671 | yes | 3.07 | 0 |
| Surfboard-tg-mixed | 6040 | yes | 4.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 5328 | yes | 0.86 | 0 |
| barry-far-vless | 5264 | yes | 1.23 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 2.7 | 0 |
| DeltaKronecker-all | 4975 | yes | 4.95 | 0 |
| Surfboard-tg-vless | 4924 | yes | 3.52 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 48 |
| speed | 48 |
| 204 | 32 |
| cn-block | 20 |
