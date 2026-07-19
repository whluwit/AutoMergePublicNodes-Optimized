# AutoNodes 每日报告

生成时间：2026-07-19 08:15:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 85003 |
| 去重后节点数 | 23609 |
| TCP 可达数 | 3000 |
| 真测通过数 | 722 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23609 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 29.4 |
| geo | 1.3 |
| probe | 76.7 |
| real_test | 220.6 |
| tcp | 33.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 124 | 108 | 16 | 87.1% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 471 | 439 | 32 | 93.2% |
| vless | 697 | 127 | 570 | 18.2% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 228 |
| geo:TimeoutError | 178 |
| cn-block:TimeoutError | 86 |
| geo:ClientOSError | 61 |
| speed:TimeoutError | 25 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 9 |
| 204:ClientOSError | 9 |
| 204:TimeoutError | 9 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4461 |
| ConnectionRefusedError | 666 |
| gaierror | 422 |
| OSError | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.902 | prefer | 127 | 0.827 | 5442 |
| Au1rxx-base64 | 0.777 | prefer | 116 | 0.776 | 149 |
| mheidari-all | 0.573 | observe | 955 | 0.493 | 20430 |
| xiaoji235-airport-v2ray-all | 0.48 | observe | 4 | 1.0 | 4642 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4478 |
| Epodonios-all | 0.255 | observe | 0 | None | 6647 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6843 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4204 |

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
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.238 | 99 | 0.152 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.152 | 15 | 84 | 99 |
| mheidari-all | 0.493 | 471 | 484 | 955 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| Au1rxx-base64 | 0.776 | 90 | 26 | 116 |
| Surfboard-tg-mixed | 0.827 | 105 | 22 | 127 |
| xiaoji235-airport-v2ray-all | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20430 | yes | 3.52 | 0 |
| SoliSpirit-all | 6843 | yes | 2.56 | 0 |
| Epodonios-all | 6647 | yes | 3.72 | 0 |
| DeltaKronecker-all | 6235 | yes | 3.97 | 0 |
| Surfboard-tg-mixed | 5442 | yes | 2.3 | 0 |
| mahdibland-V2RayAggregator | 5355 | yes | 1.59 | 0 |
| barry-far-vless | 4872 | yes | 1.39 | 0 |
| xiaoji235-airport-v2ray-all | 4642 | yes | 0.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 4478 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 4204 | yes | 2.12 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 254 |
| geo | 242 |
| cn-block | 98 |
| 204 | 27 |
