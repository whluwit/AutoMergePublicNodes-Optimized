# AutoNodes 每日报告

生成时间：2026-08-06 23:57:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 88841 |
| 去重后节点数 | 24642 |
| TCP 可达数 | 3000 |
| 真测通过数 | 430 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24642 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 20.5 |
| geo | 1.1 |
| probe | 49.7 |
| real_test | 80.3 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 162 | 151 | 11 | 93.2% |
| socks | 8 | 5 | 3 | 62.5% |
| trojan | 155 | 153 | 2 | 98.7% |
| vless | 147 | 78 | 69 | 53.1% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 25 |
| geo:ClientOSError | 21 |
| speed:ClientOSError | 15 |
| speed:TimeoutError | 10 |
| 204:TimeoutError | 7 |
| cn-block:TimeoutError | 3 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4881 |
| ConnectionRefusedError | 837 |
| gaierror | 370 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | prefer | 336 | 0.946 | 1338 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| mheidari-all | 0.649 | observe | 135 | 0.57 | 20787 |
| DeltaKronecker-all | 0.507 | observe | 8 | 0.75 | 5897 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 5184 |
| Surfboard-tg-mixed | 0.397 | observe | 12 | 0.417 | 5904 |
| nscl5-all | 0.32 | observe | 1 | 1.0 | 1621 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5219 |
| Epodonios-all | 0.255 | observe | 0 | None | 6481 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.417 | 5 | 7 | 12 |
| mheidari-all | 0.57 | 77 | 58 | 135 |
| DeltaKronecker-all | 0.75 | 6 | 2 | 8 |
| Au1rxx-base64 | 0.946 | 318 | 18 | 336 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20787 | yes | 4.29 | 0 |
| SoliSpirit-all | 7217 | yes | 3.11 | 0 |
| Epodonios-all | 6481 | yes | 5.4 | 0 |
| Surfboard-tg-mixed | 5904 | yes | 3.17 | 0 |
| DeltaKronecker-all | 5897 | yes | 4.73 | 0 |
| mahdibland-V2RayAggregator | 5225 | yes | 2.03 | 0 |
| 10ium-ScrapeCategorize-Vless | 5219 | yes | 1.33 | 0 |
| xiaoji235-airport-v2ray-all | 5184 | yes | 2.31 | 0 |
| barry-far-vless | 5041 | yes | 1.58 | 0 |
| Surfboard-tg-vless | 4729 | yes | 2.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 47 |
| speed | 25 |
| 204 | 10 |
| cn-block | 5 |
