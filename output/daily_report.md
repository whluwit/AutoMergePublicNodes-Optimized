# AutoNodes 每日报告

生成时间：2026-07-17 02:15:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79323 |
| 去重后节点数 | 24537 |
| TCP 可达数 | 3000 |
| 真测通过数 | 538 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24537 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 19.8 |
| geo | 1.1 |
| probe | 53.4 |
| real_test | 121.7 |
| tcp | 32.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 137 | 130 | 7 | 94.9% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 342 | 329 | 13 | 96.2% |
| vless | 282 | 35 | 247 | 12.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 110 |
| geo:TimeoutError | 92 |
| geo:ClientOSError | 30 |
| speed:TimeoutError | 19 |
| cn-block:TimeoutError | 11 |
| 204:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| geo:status | 1 |
| 204:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4428 |
| ConnectionRefusedError | 671 |
| gaierror | 279 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | prefer | 136 | 0.956 | 5452 |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.827 | prefer | 110 | 0.827 | 149 |
| DeltaKronecker-all | 0.625 | observe | 497 | 0.545 | 8462 |
| mheidari-all | 0.426 | observe | 24 | 0.333 | 16574 |
| nscl5-all | 0.328 | observe | 1 | 1.0 | 1821 |
| xiaoji235-airport-v2ray-all | 0.322 | observe | 1 | 1.0 | 1680 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4470 |
| Epodonios-all | 0.255 | observe | 0 | None | 6574 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.333 | 8 | 16 | 24 |
| DeltaKronecker-all | 0.545 | 271 | 226 | 497 |
| Au1rxx-base64 | 0.827 | 91 | 19 | 110 |
| Surfboard-tg-mixed | 0.956 | 130 | 6 | 136 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16574 | yes | 3.86 | 0 |
| DeltaKronecker-all | 8462 | yes | 4.23 | 0 |
| SoliSpirit-all | 6815 | yes | 1.99 | 0 |
| Epodonios-all | 6574 | yes | 0.66 | 0 |
| Surfboard-tg-mixed | 5452 | yes | 2.79 | 0 |
| mahdibland-V2RayAggregator | 5260 | yes | 0.75 | 0 |
| barry-far-vless | 4857 | yes | 1.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 4470 | yes | 1.02 | 0 |
| Surfboard-tg-vless | 4223 | yes | 2.13 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.28 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 129 |
| geo | 123 |
| cn-block | 13 |
| 204 | 4 |
