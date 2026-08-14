# AutoNodes 每日报告

生成时间：2026-08-14 01:33:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 79314 |
| 去重后节点数 | 21292 |
| TCP 可达数 | 3000 |
| 真测通过数 | 988 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21292 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 34.6 |
| geo | 1.1 |
| probe | 62.8 |
| real_test | 198.5 |
| tcp | 32.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 171 | 158 | 13 | 92.4% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 411 | 401 | 10 | 97.6% |
| vless | 460 | 281 | 179 | 61.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 56 |
| speed:TimeoutError | 49 |
| cn-block:TimeoutError | 33 |
| 204:TimeoutError | 16 |
| speed:ClientOSError | 16 |
| geo:ClientOSError | 15 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4136 |
| ConnectionRefusedError | 793 |
| gaierror | 345 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 712 | 0.94 | 1951 |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| DeltaKronecker-all | 0.922 | prefer | 36 | 0.861 | 3656 |
| Surfboard-tg-mixed | 0.882 | prefer | 109 | 0.807 | 5942 |
| mheidari-all | 0.442 | observe | 197 | 0.36 | 16929 |
| Epodonios-all | 0.255 | observe | 0 | None | 6600 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7491 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4695 |
| barry-far-vless | 0.255 | observe | 0 | None | 5056 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | nscl5-all | 0.217 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| nscl5-all | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.36 | 71 | 126 | 197 |
| Surfboard-tg-mixed | 0.807 | 88 | 21 | 109 |
| DeltaKronecker-all | 0.861 | 31 | 5 | 36 |
| Au1rxx-base64 | 0.94 | 669 | 43 | 712 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16929 | yes | 4.59 | 0 |
| SoliSpirit-all | 7491 | yes | 4.17 | 0 |
| Epodonios-all | 6600 | yes | 4.86 | 0 |
| Surfboard-tg-mixed | 5942 | yes | 2.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 5203 | yes | 3.13 | 0 |
| mahdibland-V2RayAggregator | 5197 | yes | 1.17 | 0 |
| barry-far-vless | 5056 | yes | 2.83 | 0 |
| Surfboard-tg-vless | 4695 | yes | 3.65 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.21 | 0 |
| DeltaKronecker-all | 3656 | yes | 5.22 | 0 |

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
| geo | 73 |
| speed | 67 |
| cn-block | 39 |
| 204 | 26 |
