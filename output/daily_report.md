# AutoNodes 每日报告

生成时间：2026-07-12 08:13:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 76253 |
| 去重后节点数 | 23960 |
| TCP 可达数 | 3000 |
| 真测通过数 | 345 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23960 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 40.0 |
| geo | 1.3 |
| probe | 49.3 |
| real_test | 100.9 |
| tcp | 31.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 1 | 1 | 0 | 100.0% |
| shadowsocks | 114 | 98 | 16 | 86.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 221 | 183 | 38 | 82.8% |
| vless | 63 | 21 | 42 | 33.3% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 24 |
| geo:TimeoutError | 21 |
| 204:TimeoutError | 14 |
| geo:ClientOSError | 10 |
| cn-block:TimeoutError | 9 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4239 |
| ConnectionRefusedError | 643 |
| gaierror | 296 |
| OSError | 202 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.958 | prefer | 88 | 0.886 | 16299 |
| Surfboard-tg-mixed | 0.837 | prefer | 101 | 0.762 | 5277 |
| DeltaKronecker-all | 0.778 | prefer | 157 | 0.701 | 8141 |
| Au1rxx-base64 | 0.731 | prefer | 60 | 0.733 | 118 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4003 |
| Epodonios-all | 0.255 | observe | 0 | None | 6278 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6422 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4046 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.701 | 110 | 47 | 157 |
| Au1rxx-base64 | 0.733 | 44 | 16 | 60 |
| Surfboard-tg-mixed | 0.762 | 77 | 24 | 101 |
| mheidari-all | 0.886 | 78 | 10 | 88 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16299 | yes | 3.65 | 0 |
| DeltaKronecker-all | 8141 | yes | 4.13 | 0 |
| SoliSpirit-all | 6422 | yes | 2.35 | 0 |
| Epodonios-all | 6278 | yes | 1.75 | 0 |
| mahdibland-V2RayAggregator | 5416 | yes | 1.57 | 0 |
| Surfboard-tg-mixed | 5277 | yes | 2.18 | 0 |
| barry-far-vless | 4645 | yes | 1.36 | 0 |
| Surfboard-tg-vless | 4046 | yes | 2.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4003 | yes | 1.8 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.72 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 31 |
| geo | 31 |
| 204 | 22 |
| cn-block | 14 |
