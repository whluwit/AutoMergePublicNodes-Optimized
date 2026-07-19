# AutoNodes 每日报告

生成时间：2026-07-19 13:12:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 86855 |
| 去重后节点数 | 23672 |
| TCP 可达数 | 3000 |
| 真测通过数 | 443 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23672 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 42.1 |
| geo | 1.0 |
| probe | 61.4 |
| real_test | 178.4 |
| tcp | 34.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 144 | 125 | 19 | 86.8% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 164 | 132 | 32 | 80.5% |
| vless | 709 | 138 | 571 | 19.5% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 346 |
| speed:ClientOSError | 96 |
| geo:ClientOSError | 70 |
| cn-block:TimeoutError | 49 |
| 204:TimeoutError | 20 |
| speed:TimeoutError | 14 |
| 204:ProxyError | 11 |
| 204:ClientOSError | 9 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:37748: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4842 |
| ConnectionRefusedError | 664 |
| gaierror | 411 |
| OSError | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.887 | prefer | 213 | 0.845 | 1125 |
| Surfboard-tg-mixed | 0.463 | observe | 204 | 0.382 | 5424 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 4642 |
| mheidari-all | 0.348 | observe | 512 | 0.268 | 20221 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6635 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3977 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4191 |
| barry-far-vless | 0.255 | observe | 0 | None | 4858 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| DeltaKronecker-all | 0.163 | downweight | 94 | 0.074 | 0 | 6235 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.163 | 94 | 0.074 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| SoliSpirit-all | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.074 | 7 | 87 | 94 |
| mheidari-all | 0.268 | 137 | 375 | 512 |
| Surfboard-tg-mixed | 0.382 | 78 | 126 | 204 |
| Au1rxx-base64 | 0.845 | 180 | 33 | 213 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20221 | yes | 4.52 | 0 |
| SoliSpirit-all | 6961 | yes | 1.94 | 0 |
| Epodonios-all | 6635 | yes | 2.49 | 0 |
| DeltaKronecker-all | 6235 | yes | 4.23 | 0 |
| Surfboard-tg-mixed | 5424 | yes | 2.8 | 0 |
| mahdibland-V2RayAggregator | 5355 | yes | 2.13 | 0 |
| barry-far-vless | 4858 | yes | 1.42 | 0 |
| xiaoji235-airport-v2ray-all | 4642 | yes | 1.22 | 0 |
| 10ium-ScrapeCategorize-Vless | 4478 | yes | 1.03 | 0 |
| Surfboard-tg-vless | 4191 | yes | 3.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 417 |
| speed | 110 |
| cn-block | 56 |
| 204 | 40 |
| sing-box exited 1 | 1 |
