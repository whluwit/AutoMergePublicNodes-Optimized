# AutoNodes 每日报告

生成时间：2026-08-08 01:19:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 82220 |
| 去重后节点数 | 23542 |
| TCP 可达数 | 3000 |
| 真测通过数 | 748 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23542 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 43.2 |
| geo | 1.4 |
| probe | 64.2 |
| real_test | 183.6 |
| tcp | 34.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 24 | 24 | 0 | 100.0% |
| shadowsocks | 163 | 155 | 8 | 95.1% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 161 | 146 | 15 | 90.7% |
| vless | 902 | 400 | 502 | 44.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 247 |
| geo:ClientOSError | 81 |
| cn-block:TimeoutError | 77 |
| speed:ClientOSError | 57 |
| speed:TimeoutError | 44 |
| 204:TimeoutError | 6 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4787 |
| ConnectionRefusedError | 827 |
| gaierror | 335 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | prefer | 444 | 0.937 | 1365 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.611 | observe | 30 | 0.533 | 6430 |
| mheidari-all | 0.602 | observe | 17 | 0.588 | 17687 |
| DeltaKronecker-all | 0.455 | observe | 761 | 0.375 | 5326 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7081 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7469 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5180 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.375 | 285 | 476 | 761 |
| Surfboard-tg-mixed | 0.533 | 16 | 14 | 30 |
| mheidari-all | 0.588 | 10 | 7 | 17 |
| Au1rxx-base64 | 0.937 | 416 | 28 | 444 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17687 | yes | 3.58 | 0 |
| SoliSpirit-all | 7469 | yes | 3.97 | 0 |
| Epodonios-all | 7081 | yes | 3.84 | 0 |
| Surfboard-tg-mixed | 6430 | yes | 3.1 | 0 |
| barry-far-vless | 5509 | yes | 0.69 | 0 |
| DeltaKronecker-all | 5326 | yes | 3.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 5282 | yes | 0.93 | 0 |
| Surfboard-tg-vless | 5180 | yes | 2.5 | 0 |
| mahdibland-V2RayAggregator | 5175 | yes | 2.27 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 328 |
| speed | 102 |
| cn-block | 84 |
| 204 | 14 |
