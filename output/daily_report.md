# AutoNodes 每日报告

生成时间：2026-07-03 02:37:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 77781 |
| 去重后节点数 | 23328 |
| TCP 可达数 | 3000 |
| 真测通过数 | 685 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23328 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.3 |
| generate | 28.9 |
| geo | 1.4 |
| probe | 68.9 |
| real_test | 199.2 |
| tcp | 31.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 139 | 121 | 18 | 87.1% |
| socks | 26 | 20 | 6 | 76.9% |
| trojan | 73 | 68 | 5 | 93.2% |
| vless | 1119 | 434 | 685 | 38.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 356 |
| geo:TimeoutError | 189 |
| geo:ClientOSError | 85 |
| 204:ProxyError | 30 |
| speed:TimeoutError | 13 |
| cn-block:TimeoutError | 11 |
| cn-block:ClientOSError | 10 |
| 204:TimeoutError | 9 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4407 |
| ConnectionRefusedError | 698 |
| OSError | 153 |
| gaierror | 111 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.909 | prefer | 39 | 0.846 | 16051 |
| Surfboard-tg-mixed | 0.786 | prefer | 331 | 0.707 | 6129 |
| Au1rxx-base64 | 0.621 | observe | 32 | 0.625 | 73 |
| DeltaKronecker-all | 0.457 | observe | 959 | 0.376 | 7467 |
| nscl5-all | 0.3 | observe | 1 | 1.0 | 1114 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4254 |
| Epodonios-all | 0.255 | observe | 0 | None | 7003 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6660 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.376 | 361 | 598 | 959 |
| Au1rxx-base64 | 0.625 | 20 | 12 | 32 |
| Surfboard-tg-mixed | 0.707 | 234 | 97 | 331 |
| mheidari-all | 0.846 | 33 | 6 | 39 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16051 | yes | 2.76 | 0 |
| DeltaKronecker-all | 7467 | yes | 3.0 | 0 |
| Epodonios-all | 7003 | yes | 1.2 | 0 |
| SoliSpirit-all | 6660 | yes | 1.29 | 0 |
| Surfboard-tg-mixed | 6129 | yes | 2.0 | 0 |
| mahdibland-V2RayAggregator | 5372 | yes | 1.27 | 0 |
| barry-far-vless | 5102 | yes | 0.67 | 0 |
| Surfboard-tg-vless | 4550 | yes | 1.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 4254 | yes | 0.99 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 0.87 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 371 |
| geo | 275 |
| 204 | 45 |
| cn-block | 23 |
