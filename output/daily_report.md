# AutoNodes 每日报告

生成时间：2026-07-06 19:53:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 80333 |
| 去重后节点数 | 24569 |
| TCP 可达数 | 3000 |
| 真测通过数 | 289 |
| verified 输出数 | 289 |
| global 输出数 | 298 |
| all 输出数 | 24569 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 40.2 |
| geo | 1.3 |
| probe | 48.8 |
| real_test | 80.9 |
| tcp | 31.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 125 | 93 | 32 | 74.4% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 213 | 134 | 79 | 62.9% |
| vless | 54 | 14 | 40 | 25.9% |
| vmess | 6 | 5 | 1 | 83.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 37 |
| 204:ClientOSError | 24 |
| 204:ProxyError | 22 |
| cn-block:ProxyError | 14 |
| cn-block:TimeoutError | 11 |
| geo:TimeoutError | 11 |
| cn-block:ClientOSError | 9 |
| geo:ClientOSError | 8 |
| 204:TimeoutError | 7 |
| geo:ProxyError | 6 |
| speed:TimeoutError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4619 |
| ConnectionRefusedError | 775 |
| OSError | 158 |
| gaierror | 94 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.781 | prefer | 56 | 0.786 | 121 |
| Surfboard-tg-mixed | 0.777 | prefer | 130 | 0.7 | 6111 |
| mheidari-all | 0.777 | prefer | 64 | 0.703 | 16332 |
| DeltaKronecker-all | 0.548 | observe | 154 | 0.468 | 8330 |
| nscl5-all | 0.321 | observe | 1 | 1.0 | 1651 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4358 |
| Epodonios-all | 0.255 | observe | 0 | None | 7164 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7234 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.468 | 72 | 82 | 154 |
| Surfboard-tg-mixed | 0.7 | 91 | 39 | 130 |
| mheidari-all | 0.703 | 45 | 19 | 64 |
| Au1rxx-base64 | 0.786 | 44 | 12 | 56 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16332 | yes | 3.86 | 0 |
| DeltaKronecker-all | 8330 | yes | 3.2 | 0 |
| SoliSpirit-all | 7234 | yes | 2.43 | 0 |
| Epodonios-all | 7164 | yes | 1.69 | 0 |
| Surfboard-tg-mixed | 6111 | yes | 2.61 | 0 |
| mahdibland-V2RayAggregator | 5338 | yes | 1.76 | 0 |
| barry-far-vless | 5174 | yes | 1.26 | 0 |
| Surfboard-tg-vless | 4506 | yes | 1.98 | 0 |
| 10ium-ScrapeCategorize-Vless | 4358 | yes | 1.08 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.34 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 53 |
| speed | 41 |
| cn-block | 34 |
| geo | 25 |
