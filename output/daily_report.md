# AutoNodes 每日报告

生成时间：2026-07-23 08:28:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83068 |
| 去重后节点数 | 22722 |
| TCP 可达数 | 3000 |
| 真测通过数 | 744 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22722 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| generate | 28.5 |
| geo | 1.3 |
| probe | 61.2 |
| real_test | 180.9 |
| tcp | 32.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 3 | 1 | 75.0% |
| shadowsocks | 21 | 12 | 9 | 57.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 594 | 555 | 39 | 93.4% |
| vless | 481 | 135 | 346 | 28.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 183 |
| speed:ClientOSError | 70 |
| geo:ClientOSError | 47 |
| cn-block:TimeoutError | 39 |
| speed:TimeoutError | 22 |
| 204:ProxyError | 18 |
| 204:TimeoutError | 6 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4290 |
| ConnectionRefusedError | 684 |
| gaierror | 320 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.929 | prefer | 381 | 0.85 | 19639 |
| Surfboard-tg-mixed | 0.617 | observe | 244 | 0.537 | 5330 |
| DeltaKronecker-all | 0.608 | observe | 470 | 0.528 | 5572 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 4399 |
| Au1rxx-base64 | 0.329 | observe | 2 | 1.0 | 432 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4757 |
| Epodonios-all | 0.255 | observe | 0 | None | 6489 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3968 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.528 | 248 | 222 | 470 |
| Surfboard-tg-mixed | 0.537 | 131 | 113 | 244 |
| mheidari-all | 0.85 | 324 | 57 | 381 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19639 | yes | 2.56 | 0 |
| SoliSpirit-all | 6912 | yes | 1.97 | 0 |
| Epodonios-all | 6489 | yes | 0.97 | 0 |
| DeltaKronecker-all | 5572 | yes | 2.78 | 0 |
| Surfboard-tg-mixed | 5330 | yes | 1.74 | 0 |
| mahdibland-V2RayAggregator | 4954 | yes | 1.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 4757 | yes | 1.14 | 0 |
| barry-far-vless | 4690 | yes | 1.01 | 0 |
| xiaoji235-airport-v2ray-all | 4399 | yes | 1.26 | 0 |
| Surfboard-tg-vless | 4154 | yes | 1.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 230 |
| speed | 94 |
| cn-block | 46 |
| 204 | 26 |
