# AutoNodes 每日报告

生成时间：2026-07-10 14:15:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 75854 |
| 去重后节点数 | 23671 |
| TCP 可达数 | 3000 |
| 真测通过数 | 208 |
| verified 输出数 | 208 |
| global 输出数 | 227 |
| all 输出数 | 23671 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 37.0 |
| geo | 1.4 |
| probe | 50.1 |
| real_test | 80.5 |
| tcp | 31.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 89 | 74 | 15 | 83.1% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 121 | 53 | 68 | 43.8% |
| vless | 171 | 36 | 135 | 21.1% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 56 |
| geo:TimeoutError | 47 |
| 204:TimeoutError | 24 |
| 204:ProxyError | 21 |
| cn-block:ProxyError | 18 |
| geo:ClientOSError | 14 |
| cn-block:ClientOSError | 14 |
| 204:ClientOSError | 7 |
| cn-block:TimeoutError | 7 |
| speed:TimeoutError | 7 |
| geo:ProxyError | 3 |
| speed:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4363 |
| ConnectionRefusedError | 664 |
| gaierror | 234 |
| OSError | 192 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.877 | prefer | 19 | 0.947 | 52 |
| Surfboard-tg-mixed | 0.725 | prefer | 122 | 0.648 | 5542 |
| nscl5-all | 0.404 | observe | 3 | 1.0 | 1148 |
| DeltaKronecker-all | 0.369 | observe | 237 | 0.287 | 7600 |
| mheidari-all | 0.361 | observe | 10 | 0.4 | 16259 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4165 |
| Epodonios-all | 0.255 | observe | 0 | None | 6344 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6483 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.287 | 68 | 169 | 237 |
| mheidari-all | 0.4 | 4 | 6 | 10 |
| Surfboard-tg-mixed | 0.648 | 79 | 43 | 122 |
| Au1rxx-base64 | 0.947 | 18 | 1 | 19 |
| nscl5-all | 1.0 | 3 | 0 | 3 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16259 | yes | 3.67 | 0 |
| DeltaKronecker-all | 7600 | yes | 3.75 | 0 |
| SoliSpirit-all | 6483 | yes | 2.66 | 0 |
| Epodonios-all | 6344 | yes | 0.8 | 0 |
| Surfboard-tg-mixed | 5542 | yes | 2.2 | 0 |
| mahdibland-V2RayAggregator | 5391 | yes | 0.9 | 0 |
| barry-far-vless | 4670 | yes | 1.83 | 0 |
| Surfboard-tg-vless | 4182 | yes | 1.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 4165 | yes | 2.21 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 2.56 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 66 |
| geo | 64 |
| 204 | 52 |
| cn-block | 39 |
