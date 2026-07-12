# AutoNodes 每日报告

生成时间：2026-07-12 02:18:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 76484 |
| 去重后节点数 | 24080 |
| TCP 可达数 | 3000 |
| 真测通过数 | 509 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24080 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 25.6 |
| geo | 1.3 |
| probe | 50.1 |
| real_test | 117.1 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 1 | 1 | 0 | 100.0% |
| shadowsocks | 133 | 119 | 14 | 89.5% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 142 | 138 | 4 | 97.2% |
| vless | 509 | 206 | 303 | 40.5% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 126 |
| geo:TimeoutError | 94 |
| speed:TimeoutError | 38 |
| geo:ClientOSError | 29 |
| cn-block:TimeoutError | 11 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| 204:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4266 |
| ConnectionRefusedError | 656 |
| gaierror | 298 |
| OSError | 201 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.786 | prefer | 62 | 0.79 | 125 |
| Surfboard-tg-mixed | 0.756 | prefer | 322 | 0.677 | 5400 |
| mheidari-all | 0.603 | observe | 279 | 0.523 | 16350 |
| DeltaKronecker-all | 0.537 | observe | 125 | 0.456 | 7969 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 3953 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6385 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3977 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6420 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.456 | 57 | 68 | 125 |
| mheidari-all | 0.523 | 146 | 133 | 279 |
| Surfboard-tg-mixed | 0.677 | 218 | 104 | 322 |
| Au1rxx-base64 | 0.79 | 49 | 13 | 62 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16350 | yes | 3.53 | 0 |
| DeltaKronecker-all | 7969 | yes | 3.65 | 0 |
| SoliSpirit-all | 6420 | yes | 2.41 | 0 |
| Epodonios-all | 6385 | yes | 1.81 | 0 |
| mahdibland-V2RayAggregator | 5416 | yes | 1.07 | 0 |
| Surfboard-tg-mixed | 5400 | yes | 2.1 | 0 |
| barry-far-vless | 4725 | yes | 1.74 | 0 |
| Surfboard-tg-vless | 4135 | yes | 2.24 | 0 |
| MatinGhanbari-all-sub | 3977 | yes | 2.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 3953 | yes | 1.91 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 164 |
| geo | 123 |
| cn-block | 19 |
| 204 | 16 |
