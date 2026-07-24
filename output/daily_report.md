# AutoNodes 每日报告

生成时间：2026-07-24 02:17:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83447 |
| 去重后节点数 | 23086 |
| TCP 可达数 | 3000 |
| 真测通过数 | 822 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23086 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 32.5 |
| geo | 1.3 |
| probe | 68.1 |
| real_test | 191.9 |
| tcp | 32.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 23 | 20 | 3 | 87.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 633 | 591 | 42 | 93.4% |
| vless | 586 | 168 | 418 | 28.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 198 |
| speed:ClientOSError | 96 |
| speed:TimeoutError | 52 |
| geo:ClientOSError | 46 |
| cn-block:TimeoutError | 43 |
| 204:ProxyError | 12 |
| geo:ProxyError | 5 |
| 204:TimeoutError | 3 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4262 |
| ConnectionRefusedError | 689 |
| gaierror | 401 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.97 | prefer | 107 | 0.897 | 5362 |
| DeltaKronecker-all | 0.773 | prefer | 174 | 0.695 | 5572 |
| mheidari-all | 0.663 | observe | 958 | 0.584 | 20024 |
| Au1rxx-base64 | 0.531 | observe | 7 | 1.0 | 432 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3843 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4757 |
| Epodonios-all | 0.255 | observe | 0 | None | 6509 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.584 | 559 | 399 | 958 |
| DeltaKronecker-all | 0.695 | 121 | 53 | 174 |
| Surfboard-tg-mixed | 0.897 | 96 | 11 | 107 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 7 | 0 | 7 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20024 | yes | 3.65 | 0 |
| SoliSpirit-all | 6779 | yes | 1.66 | 0 |
| Epodonios-all | 6509 | yes | 1.58 | 0 |
| DeltaKronecker-all | 5572 | yes | 4.1 | 0 |
| Surfboard-tg-mixed | 5362 | yes | 2.69 | 0 |
| mahdibland-V2RayAggregator | 4971 | yes | 1.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 4757 | yes | 1.11 | 0 |
| barry-far-vless | 4750 | yes | 0.8 | 0 |
| Surfboard-tg-vless | 4119 | yes | 1.82 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 1.34 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 249 |
| speed | 151 |
| cn-block | 47 |
| 204 | 17 |
