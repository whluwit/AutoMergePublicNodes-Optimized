# AutoNodes 每日报告

生成时间：2026-07-26 13:15:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 81237 |
| 去重后节点数 | 22616 |
| TCP 可达数 | 3000 |
| 真测通过数 | 675 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22616 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 42.7 |
| geo | 1.3 |
| probe | 68.6 |
| real_test | 163.5 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 7 | 0 | 100.0% |
| http | 75 | 75 | 0 | 100.0% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 133 | 104 | 29 | 78.2% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 467 | 392 | 75 | 83.9% |
| vless | 225 | 87 | 138 | 38.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 73 |
| 204:TimeoutError | 52 |
| 204:ProxyError | 31 |
| cn-block:TimeoutError | 27 |
| speed:ClientOSError | 23 |
| geo:ClientOSError | 16 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 9 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4381 |
| ConnectionRefusedError | 691 |
| gaierror | 254 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.99 | prefer | 75 | 1.0 | 86 |
| Au1rxx-base64 | 0.969 | prefer | 432 | 0.912 | 1462 |
| Surfboard-tg-mixed | 0.757 | prefer | 29 | 0.69 | 5591 |
| mheidari-all | 0.686 | observe | 163 | 0.607 | 17011 |
| tg-oneclickvpnkeys | 0.519 | observe | 7 | 1.0 | 149 |
| DeltaKronecker-all | 0.456 | observe | 208 | 0.375 | 5950 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| ermaozi | 0.256 | observe | 1 | 1.0 | 30 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 6731 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 200 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.375 | 78 | 130 | 208 |
| mheidari-all | 0.607 | 99 | 64 | 163 |
| Surfboard-tg-mixed | 0.69 | 20 | 9 | 29 |
| Au1rxx-base64 | 0.912 | 394 | 38 | 432 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17011 | yes | 3.79 | 0 |
| Epodonios-all | 6731 | yes | 2.37 | 0 |
| SoliSpirit-all | 6620 | yes | 3.71 | 0 |
| DeltaKronecker-all | 5950 | yes | 4.2 | 0 |
| Surfboard-tg-mixed | 5591 | yes | 3.27 | 0 |
| mahdibland-V2RayAggregator | 4980 | yes | 1.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 2.79 | 0 |
| barry-far-vless | 4837 | yes | 2.25 | 0 |
| Surfboard-tg-vless | 4351 | yes | 2.63 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 2.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 90 |
| 204 | 84 |
| cn-block | 39 |
| speed | 32 |
