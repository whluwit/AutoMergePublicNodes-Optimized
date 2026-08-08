# AutoNodes 每日报告

生成时间：2026-08-08 06:46:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 81866 |
| 去重后节点数 | 23409 |
| TCP 可达数 | 3000 |
| 真测通过数 | 480 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23409 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 40.3 |
| geo | 1.6 |
| probe | 53.3 |
| real_test | 107.1 |
| tcp | 34.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 26 | 25 | 1 | 96.2% |
| shadowsocks | 164 | 155 | 9 | 94.5% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 163 | 138 | 25 | 84.7% |
| vless | 255 | 138 | 117 | 54.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 64 |
| 204:TimeoutError | 22 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 16 |
| speed:ClientOSError | 13 |
| speed:TimeoutError | 10 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| 204:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4623 |
| ConnectionRefusedError | 824 |
| gaierror | 359 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 363 | 0.959 | 1368 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| DeltaKronecker-all | 0.54 | observe | 98 | 0.459 | 5347 |
| Surfboard-tg-mixed | 0.517 | observe | 117 | 0.436 | 6313 |
| mheidari-all | 0.509 | observe | 33 | 0.424 | 17696 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 169 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5450 |
| Epodonios-all | 0.255 | observe | 0 | None | 6914 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.424 | 14 | 19 | 33 |
| Surfboard-tg-mixed | 0.436 | 51 | 66 | 117 |
| DeltaKronecker-all | 0.459 | 45 | 53 | 98 |
| Au1rxx-base64 | 0.959 | 348 | 15 | 363 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17696 | yes | 4.0 | 0 |
| SoliSpirit-all | 7402 | yes | 2.86 | 0 |
| Epodonios-all | 6914 | yes | 4.47 | 0 |
| Surfboard-tg-mixed | 6313 | yes | 4.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 5450 | yes | 1.49 | 0 |
| barry-far-vless | 5409 | yes | 1.01 | 0 |
| DeltaKronecker-all | 5347 | yes | 3.31 | 0 |
| mahdibland-V2RayAggregator | 5162 | yes | 2.03 | 0 |
| Surfboard-tg-vless | 5099 | yes | 3.12 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 85 |
| 204 | 27 |
| speed | 24 |
| cn-block | 19 |
