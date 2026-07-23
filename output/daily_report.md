# AutoNodes 每日报告

生成时间：2026-07-23 19:13:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83097 |
| 去重后节点数 | 22696 |
| TCP 可达数 | 3000 |
| 真测通过数 | 659 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22696 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 42.5 |
| geo | 1.3 |
| probe | 68.0 |
| real_test | 172.9 |
| tcp | 32.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 35 | 1 | 97.2% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 13 | 8 | 5 | 61.5% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 503 | 462 | 41 | 91.8% |
| vless | 503 | 147 | 356 | 29.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 185 |
| geo:TimeoutError | 75 |
| 204:ProxyError | 33 |
| geo:ClientOSError | 31 |
| cn-block:TimeoutError | 30 |
| 204:TimeoutError | 27 |
| speed:TimeoutError | 7 |
| geo:ProxyError | 5 |
| cn-block:ProxyError | 4 |
| speed:ProxyError | 4 |
| cn-block:ClientOSError | 2 |
| 204:ClientOSError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4385 |
| ConnectionRefusedError | 692 |
| gaierror | 281 |
| OSError | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.969 | prefer | 322 | 0.891 | 19362 |
| zhangkai | 0.95 | prefer | 36 | 0.972 | 61 |
| Surfboard-tg-mixed | 0.78 | prefer | 88 | 0.705 | 5412 |
| DeltaKronecker-all | 0.521 | observe | 612 | 0.441 | 5572 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 4399 |
| Au1rxx-base64 | 0.329 | observe | 2 | 1.0 | 432 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4757 |
| Epodonios-all | 0.255 | observe | 0 | None | 6563 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.441 | 270 | 342 | 612 |
| Surfboard-tg-mixed | 0.705 | 62 | 26 | 88 |
| mheidari-all | 0.891 | 287 | 35 | 322 |
| zhangkai | 0.972 | 35 | 1 | 36 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19362 | yes | 4.1 | 0 |
| SoliSpirit-all | 6800 | yes | 2.2 | 0 |
| Epodonios-all | 6563 | yes | 1.83 | 0 |
| DeltaKronecker-all | 5572 | yes | 3.08 | 0 |
| Surfboard-tg-mixed | 5412 | yes | 2.91 | 0 |
| mahdibland-V2RayAggregator | 4971 | yes | 1.96 | 0 |
| barry-far-vless | 4890 | yes | 1.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 4757 | yes | 1.79 | 0 |
| xiaoji235-airport-v2ray-all | 4399 | yes | 1.14 | 0 |
| Surfboard-tg-vless | 4259 | yes | 2.27 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 196 |
| geo | 111 |
| 204 | 62 |
| cn-block | 36 |
