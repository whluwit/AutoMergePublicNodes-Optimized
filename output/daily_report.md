# AutoNodes 每日报告

生成时间：2026-07-13 02:25:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 77752 |
| 去重后节点数 | 24184 |
| TCP 可达数 | 3000 |
| 真测通过数 | 463 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24184 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 19.1 |
| geo | 1.3 |
| probe | 48.7 |
| real_test | 105.4 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 1 | 1 | 0 | 100.0% |
| shadowsocks | 102 | 96 | 6 | 94.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 144 | 138 | 6 | 95.8% |
| vless | 517 | 186 | 331 | 36.0% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 142 |
| geo:TimeoutError | 105 |
| speed:TimeoutError | 37 |
| geo:ClientOSError | 35 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4268 |
| ConnectionRefusedError | 675 |
| gaierror | 326 |
| OSError | 205 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.727 | prefer | 318 | 0.648 | 5562 |
| DeltaKronecker-all | 0.602 | observe | 155 | 0.523 | 8141 |
| mheidari-all | 0.544 | observe | 291 | 0.464 | 16513 |
| nscl5-all | 0.381 | observe | 4 | 0.75 | 1526 |
| xiaoji235-airport-v2ray-all | 0.321 | observe | 1 | 1.0 | 1647 |
| Au1rxx-base64 | 0.26 | observe | 1 | 1.0 | 132 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4003 |
| Epodonios-all | 0.255 | observe | 0 | None | 6591 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.464 | 135 | 156 | 291 |
| DeltaKronecker-all | 0.523 | 81 | 74 | 155 |
| Surfboard-tg-mixed | 0.648 | 206 | 112 | 318 |
| nscl5-all | 0.75 | 3 | 1 | 4 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16513 | yes | 3.41 | 0 |
| DeltaKronecker-all | 8141 | yes | 3.72 | 0 |
| Epodonios-all | 6591 | yes | 0.33 | 0 |
| SoliSpirit-all | 6407 | yes | 1.25 | 0 |
| Surfboard-tg-mixed | 5562 | yes | 2.43 | 0 |
| mahdibland-V2RayAggregator | 5438 | yes | 1.52 | 0 |
| barry-far-vless | 4867 | yes | 1.42 | 0 |
| Surfboard-tg-vless | 4251 | yes | 3.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 4003 | yes | 0.8 | 0 |
| MatinGhanbari-all-sub | 3976 | yes | 1.51 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 179 |
| geo | 140 |
| cn-block | 20 |
| 204 | 5 |
