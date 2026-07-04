# AutoNodes 每日报告

生成时间：2026-07-04 02:33:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 78122 |
| 去重后节点数 | 23056 |
| TCP 可达数 | 3000 |
| 真测通过数 | 424 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23056 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 21.1 |
| geo | 1.4 |
| probe | 54.5 |
| real_test | 127.8 |
| tcp | 30.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 104 | 96 | 8 | 92.3% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 199 | 186 | 13 | 93.5% |
| vless | 469 | 93 | 376 | 19.8% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 210 |
| speed:ClientOSError | 110 |
| geo:ClientOSError | 38 |
| speed:TimeoutError | 25 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 2 |
| cn-block:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4291 |
| ConnectionRefusedError | 678 |
| gaierror | 200 |
| OSError | 152 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.971 | prefer | 126 | 0.897 | 6191 |
| Au1rxx-base64 | 0.654 | observe | 38 | 0.658 | 103 |
| DeltaKronecker-all | 0.491 | observe | 587 | 0.411 | 6997 |
| nscl5-all | 0.359 | observe | 2 | 1.0 | 1189 |
| tg-ConfigV2rayNG | 0.319 | observe | 2 | 1.0 | 200 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4368 |
| Epodonios-all | 0.255 | observe | 0 | None | 7108 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |

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
| downweight | mheidari-all | 0.247 | 28 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.143 | 4 | 24 | 28 |
| DeltaKronecker-all | 0.411 | 241 | 346 | 587 |
| Au1rxx-base64 | 0.658 | 25 | 13 | 38 |
| Surfboard-tg-mixed | 0.897 | 113 | 13 | 126 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| tg-ConfigV2rayNG | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16050 | yes | 3.2 | 0 |
| Epodonios-all | 7108 | yes | 3.42 | 0 |
| DeltaKronecker-all | 6997 | yes | 3.86 | 0 |
| SoliSpirit-all | 6864 | yes | 3.27 | 0 |
| Surfboard-tg-mixed | 6191 | yes | 2.47 | 0 |
| mahdibland-V2RayAggregator | 5333 | yes | 0.25 | 0 |
| barry-far-vless | 5289 | yes | 1.37 | 0 |
| Surfboard-tg-vless | 4665 | yes | 1.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4368 | yes | 1.7 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 1.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 248 |
| speed | 135 |
| cn-block | 8 |
| 204 | 7 |
