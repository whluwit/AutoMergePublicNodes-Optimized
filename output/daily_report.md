# AutoNodes 每日报告

生成时间：2026-08-12 19:00:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79762 |
| 去重后节点数 | 22328 |
| TCP 可达数 | 3000 |
| 真测通过数 | 587 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22328 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 29.7 |
| geo | 1.4 |
| probe | 55.5 |
| real_test | 124.5 |
| tcp | 33.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 152 | 136 | 16 | 89.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 120 | 109 | 11 | 90.8% |
| vless | 254 | 194 | 60 | 76.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 18 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 9 |
| geo:TimeoutError | 9 |
| geo:ClientOSError | 6 |
| 204:ProxyError | 6 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4646 |
| ConnectionRefusedError | 788 |
| gaierror | 296 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.934 | prefer | 460 | 0.867 | 1703 |
| mheidari-all | 0.749 | prefer | 13 | 0.923 | 16743 |
| Surfboard-tg-mixed | 0.741 | prefer | 57 | 0.667 | 5975 |
| DeltaKronecker-all | 0.602 | observe | 17 | 0.588 | 4975 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5328 |
| Epodonios-all | 0.255 | observe | 0 | None | 6597 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7349 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4789 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 8 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.588 | 10 | 7 | 17 |
| Surfboard-tg-mixed | 0.667 | 38 | 19 | 57 |
| Au1rxx-base64 | 0.867 | 399 | 61 | 460 |
| mheidari-all | 0.923 | 12 | 1 | 13 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16743 | yes | 3.88 | 0 |
| SoliSpirit-all | 7349 | yes | 1.97 | 0 |
| Epodonios-all | 6597 | yes | 2.52 | 0 |
| Surfboard-tg-mixed | 5975 | yes | 3.22 | 0 |
| 10ium-ScrapeCategorize-Vless | 5328 | yes | 1.19 | 0 |
| mahdibland-V2RayAggregator | 5209 | yes | 3.98 | 0 |
| barry-far-vless | 5121 | yes | 0.73 | 0 |
| DeltaKronecker-all | 4975 | yes | 4.17 | 0 |
| Surfboard-tg-vless | 4789 | yes | 2.75 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 0.98 | 0 |

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
| speed | 30 |
| 204 | 23 |
| cn-block | 21 |
| geo | 16 |
