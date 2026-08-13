# AutoNodes 每日报告

生成时间：2026-08-13 07:24:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79378 |
| 去重后节点数 | 22353 |
| TCP 可达数 | 3000 |
| 真测通过数 | 732 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22353 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 37.0 |
| geo | 1.4 |
| probe | 64.0 |
| real_test | 157.5 |
| tcp | 34.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 167 | 158 | 9 | 94.6% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 224 | 213 | 11 | 95.1% |
| vless | 371 | 208 | 163 | 56.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 67 |
| speed:TimeoutError | 32 |
| 204:TimeoutError | 23 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 13 |
| speed:ClientOSError | 11 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:status | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4520 |
| ConnectionRefusedError | 763 |
| gaierror | 244 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 452 | 0.951 | 1509 |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.777 | prefer | 140 | 0.7 | 5801 |
| mheidari-all | 0.545 | observe | 125 | 0.464 | 16910 |
| DeltaKronecker-all | 0.341 | observe | 67 | 0.254 | 4975 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5203 |
| Epodonios-all | 0.255 | observe | 0 | None | 6457 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7624 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4621 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.128 | observe | 1 | 0.0 | 0 | 20 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.254 | 17 | 50 | 67 |
| mheidari-all | 0.464 | 58 | 67 | 125 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.7 | 98 | 42 | 140 |
| Au1rxx-base64 | 0.951 | 430 | 22 | 452 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16910 | yes | 5.34 | 0 |
| SoliSpirit-all | 7624 | yes | 1.39 | 0 |
| Epodonios-all | 6457 | yes | 3.92 | 0 |
| Surfboard-tg-mixed | 5801 | yes | 4.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 5203 | yes | 0.76 | 0 |
| mahdibland-V2RayAggregator | 5197 | yes | 4.59 | 0 |
| barry-far-vless | 5041 | yes | 0.52 | 0 |
| DeltaKronecker-all | 4975 | yes | 3.53 | 0 |
| Surfboard-tg-vless | 4621 | yes | 3.31 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.07 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 89 |
| speed | 45 |
| 204 | 31 |
| cn-block | 20 |
