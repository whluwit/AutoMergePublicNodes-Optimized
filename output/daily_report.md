# AutoNodes 每日报告

生成时间：2026-07-04 08:35:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 78938 |
| 去重后节点数 | 23506 |
| TCP 可达数 | 3000 |
| 真测通过数 | 310 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23506 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 37.7 |
| geo | 1.3 |
| probe | 46.6 |
| real_test | 111.0 |
| tcp | 30.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 61 | 55 | 6 | 90.2% |
| socks | 21 | 20 | 1 | 95.2% |
| trojan | 167 | 109 | 58 | 65.3% |
| vless | 184 | 82 | 102 | 44.6% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 59 |
| geo:TimeoutError | 29 |
| 204:ProxyError | 17 |
| cn-block:TimeoutError | 15 |
| cn-block:ProxyError | 8 |
| 204:ClientOSError | 8 |
| 204:TimeoutError | 8 |
| speed:ProxyError | 6 |
| geo:ClientOSError | 6 |
| geo:ProxyError | 5 |
| cn-block:ClientOSError | 3 |
| speed:TimeoutError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4408 |
| ConnectionRefusedError | 665 |
| OSError | 152 |
| gaierror | 114 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.878 | prefer | 22 | 0.909 | 77 |
| Surfboard-tg-mixed | 0.707 | prefer | 239 | 0.628 | 6152 |
| DeltaKronecker-all | 0.661 | observe | 170 | 0.582 | 7309 |
| nscl5-all | 0.359 | observe | 2 | 1.0 | 1189 |
| tg-ConfigV2rayNG | 0.319 | observe | 2 | 1.0 | 200 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4579 |
| Epodonios-all | 0.255 | observe | 0 | None | 7154 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7126 |

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
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.2 | 1 | 4 | 5 |
| DeltaKronecker-all | 0.582 | 99 | 71 | 170 |
| Surfboard-tg-mixed | 0.628 | 150 | 89 | 239 |
| Au1rxx-base64 | 0.909 | 20 | 2 | 22 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| tg-ConfigV2rayNG | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16136 | yes | 3.15 | 0 |
| DeltaKronecker-all | 7309 | yes | 3.81 | 0 |
| Epodonios-all | 7154 | yes | 3.36 | 0 |
| SoliSpirit-all | 7126 | yes | 2.3 | 0 |
| Surfboard-tg-mixed | 6152 | yes | 2.6 | 0 |
| mahdibland-V2RayAggregator | 5333 | yes | 1.46 | 0 |
| barry-far-vless | 5278 | yes | 0.81 | 0 |
| 10ium-ScrapeCategorize-Vless | 4579 | yes | 0.57 | 0 |
| Surfboard-tg-vless | 4573 | yes | 2.36 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 1.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 68 |
| geo | 40 |
| 204 | 33 |
| cn-block | 26 |
