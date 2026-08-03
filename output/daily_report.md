# AutoNodes 每日报告

生成时间：2026-08-03 02:28:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 81019 |
| 去重后节点数 | 22575 |
| TCP 可达数 | 3000 |
| 真测通过数 | 822 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22575 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 29.3 |
| geo | 1.5 |
| probe | 62.3 |
| real_test | 189.0 |
| tcp | 35.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 143 | 143 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 158 | 148 | 10 | 93.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 40 | 36 | 4 | 90.0% |
| vless | 816 | 474 | 342 | 58.1% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 135 |
| speed:ClientOSError | 78 |
| speed:TimeoutError | 71 |
| geo:ClientOSError | 46 |
| 204:TimeoutError | 10 |
| cn-block:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4821 |
| ConnectionRefusedError | 731 |
| gaierror | 275 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 144 | 1.0 | 344 |
| Au1rxx-base64 | 0.952 | prefer | 599 | 0.888 | 1634 |
| Surfboard-tg-mixed | 0.587 | observe | 19 | 0.526 | 5222 |
| DeltaKronecker-all | 0.461 | observe | 11 | 0.545 | 3437 |
| mheidari-all | 0.399 | observe | 399 | 0.318 | 18808 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 3833 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 56 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5486 |
| Epodonios-all | 0.255 | observe | 0 | None | 5849 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.318 | 127 | 272 | 399 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.526 | 10 | 9 | 19 |
| DeltaKronecker-all | 0.545 | 6 | 5 | 11 |
| Au1rxx-base64 | 0.888 | 532 | 67 | 599 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18808 | yes | 4.42 | 0 |
| SoliSpirit-all | 6721 | yes | 3.44 | 0 |
| Epodonios-all | 5849 | yes | 5.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 5486 | yes | 1.73 | 0 |
| Surfboard-tg-mixed | 5222 | yes | 3.58 | 0 |
| mahdibland-V2RayAggregator | 5208 | yes | 3.37 | 0 |
| barry-far-vless | 4560 | yes | 2.35 | 0 |
| Surfboard-tg-vless | 4172 | yes | 3.28 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.45 | 0 |
| xiaoji235-airport-v2ray-all | 3833 | yes | 2.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 182 |
| speed | 150 |
| 204 | 14 |
| cn-block | 14 |
