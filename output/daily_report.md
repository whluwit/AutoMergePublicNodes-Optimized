# AutoNodes 每日报告

生成时间：2026-10-12 04:18:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99269 |
| 去重后节点数 | 27605 |
| TCP 可达数 | 3000 |
| 真测通过数 | 544 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27605 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 84.8 |
| geo | 1.5 |
| probe | 355.0 |
| real_test | 648.6 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 32 | 17 | 65.3% |
| hysteria2 | 27 | 27 | 0 | 100.0% |
| shadowsocks | 121 | 119 | 2 | 98.3% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 132 | 125 | 7 | 94.7% |
| vless | 582 | 236 | 346 | 40.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 182 |
| speed:TimeoutError | 82 |
| 204:ProxyError | 27 |
| speed:ClientOSError | 25 |
| geo:ClientOSError | 25 |
| cn-block:TimeoutError | 18 |
| cn-block:ClientOSError | 5 |
| 204:TimeoutError | 4 |
| 204:ClientOSError | 2 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6317 |
| ConnectionRefusedError | 1056 |
| gaierror | 467 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.992 | prefer | 381 | 0.921 | 1815 |
| Surfboard-tg-mixed | 0.898 | prefer | 20 | 0.85 | 7200 |
| ermaozi | 0.682 | observe | 50 | 0.66 | 708 |
| mheidari-all | 0.388 | observe | 450 | 0.307 | 23656 |
| DeltaKronecker-all | 0.298 | observe | 11 | 0.273 | 5372 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| Epodonios-all | 0.255 | observe | 0 | None | 7699 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9443 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.273 | 3 | 8 | 11 |
| mheidari-all | 0.307 | 138 | 312 | 450 |
| ermaozi | 0.66 | 33 | 17 | 50 |
| Surfboard-tg-mixed | 0.85 | 17 | 3 | 20 |
| Au1rxx-base64 | 0.921 | 351 | 30 | 381 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23656 | yes | 6.43 | 0 |
| SoliSpirit-all | 9443 | yes | 4.28 | 0 |
| Epodonios-all | 7699 | yes | 6.65 | 0 |
| Surfboard-tg-mixed | 7200 | yes | 4.72 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5961 | yes | 0.85 | 0 |
| Surfboard-tg-vless | 5717 | yes | 5.73 | 0 |
| DeltaKronecker-all | 5372 | yes | 6.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 5099 | yes | 0.63 | 0 |
| mahdibland-V2RayAggregator | 4284 | yes | 3.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 208 |
| speed | 107 |
| 204 | 34 |
| cn-block | 24 |
