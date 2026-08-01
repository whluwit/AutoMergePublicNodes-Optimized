# AutoNodes 每日报告

生成时间：2026-08-01 08:17:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78781 |
| 去重后节点数 | 23173 |
| TCP 可达数 | 3000 |
| 真测通过数 | 654 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23173 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 25.8 |
| geo | 1.4 |
| probe | 62.4 |
| real_test | 162.7 |
| tcp | 34.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 157 | 157 | 0 | 100.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 152 | 115 | 37 | 75.7% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 51 | 46 | 5 | 90.2% |
| vless | 570 | 314 | 256 | 55.1% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 101 |
| speed:TimeoutError | 48 |
| geo:ClientOSError | 44 |
| speed:ClientOSError | 35 |
| 204:TimeoutError | 25 |
| 204:ProxyError | 14 |
| cn-block:TimeoutError | 12 |
| 204:ClientOSError | 12 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4609 |
| ConnectionRefusedError | 746 |
| gaierror | 231 |
| OSError | 223 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 159 | 1.0 | 228 |
| Au1rxx-base64 | 0.849 | prefer | 472 | 0.784 | 1656 |
| Surfboard-tg-mixed | 0.58 | observe | 86 | 0.5 | 5316 |
| DeltaKronecker-all | 0.425 | observe | 224 | 0.344 | 5502 |
| mheidari-all | 0.324 | observe | 8 | 0.375 | 16723 |
| xiaoji235-airport-v2ray-all | 0.282 | observe | 2 | 0.5 | 1861 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| Epodonios-all | 0.255 | observe | 0 | None | 5937 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6670 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.104 | observe | 2 | 0.0 | 0 | 15 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| Pawdroid | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.344 | 77 | 147 | 224 |
| mheidari-all | 0.375 | 3 | 5 | 8 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.5 | 43 | 43 | 86 |
| Au1rxx-base64 | 0.784 | 370 | 102 | 472 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16723 | yes | 4.72 | 0 |
| SoliSpirit-all | 6670 | yes | 3.33 | 0 |
| Epodonios-all | 5937 | yes | 4.9 | 0 |
| DeltaKronecker-all | 5502 | yes | 4.76 | 0 |
| 10ium-ScrapeCategorize-Vless | 5391 | yes | 1.88 | 0 |
| Surfboard-tg-mixed | 5316 | yes | 5.38 | 0 |
| mahdibland-V2RayAggregator | 5039 | yes | 2.93 | 0 |
| barry-far-vless | 4552 | yes | 1.63 | 0 |
| Surfboard-tg-vless | 4168 | yes | 3.23 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.47 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 146 |
| speed | 85 |
| 204 | 51 |
| cn-block | 22 |
