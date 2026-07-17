# AutoNodes 每日报告

生成时间：2026-07-17 08:06:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 98/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 79440 |
| 去重后节点数 | 24736 |
| TCP 可达数 | 3000 |
| 真测通过数 | 468 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24736 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 38.7 |
| geo | 1.1 |
| probe | 52.0 |
| real_test | 125.7 |
| tcp | 32.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 35 | 35 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 93 | 71 | 22 | 76.3% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 300 | 275 | 25 | 91.7% |
| vless | 320 | 80 | 240 | 25.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 112 |
| geo:TimeoutError | 103 |
| cn-block:TimeoutError | 24 |
| 204:TimeoutError | 21 |
| 204:ProxyError | 8 |
| geo:ClientOSError | 6 |
| speed:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4482 |
| ConnectionRefusedError | 659 |
| OSError | 219 |
| gaierror | 210 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.975 | prefer | 35 | 1.0 | 61 |
| Au1rxx-base64 | 0.947 | prefer | 100 | 0.95 | 149 |
| DeltaKronecker-all | 0.631 | observe | 292 | 0.551 | 8967 |
| Surfboard-tg-mixed | 0.617 | observe | 313 | 0.537 | 5358 |
| mheidari-all | 0.515 | observe | 11 | 0.636 | 16487 |
| nscl5-all | 0.328 | observe | 1 | 1.0 | 1821 |
| xiaoji235-airport-v2ray-all | 0.322 | observe | 1 | 1.0 | 1680 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4428 |
| Epodonios-all | 0.255 | observe | 0 | None | 6542 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.537 | 168 | 145 | 313 |
| DeltaKronecker-all | 0.551 | 161 | 131 | 292 |
| mheidari-all | 0.636 | 7 | 4 | 11 |
| Au1rxx-base64 | 0.95 | 95 | 5 | 100 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 35 | 0 | 35 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16487 | yes | 4.1 | 0 |
| DeltaKronecker-all | 8967 | yes | 4.4 | 0 |
| SoliSpirit-all | 7000 | yes | 2.37 | 0 |
| Epodonios-all | 6542 | yes | 1.87 | 0 |
| Surfboard-tg-mixed | 5358 | yes | 2.65 | 0 |
| mahdibland-V2RayAggregator | 5208 | yes | 1.96 | 0 |
| barry-far-vless | 4764 | yes | 1.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 4428 | yes | 1.28 | 0 |
| Surfboard-tg-vless | 4115 | yes | 2.81 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.91 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 117 |
| geo | 110 |
| 204 | 33 |
| cn-block | 29 |
