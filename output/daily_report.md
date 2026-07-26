# AutoNodes 每日报告

生成时间：2026-07-26 02:28:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 80317 |
| 去重后节点数 | 22465 |
| TCP 可达数 | 3000 |
| 真测通过数 | 893 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22465 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 27.9 |
| geo | 1.4 |
| probe | 64.3 |
| real_test | 206.6 |
| tcp | 30.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 154 | 141 | 13 | 91.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 501 | 465 | 36 | 92.8% |
| vless | 579 | 199 | 380 | 34.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 160 |
| geo:TimeoutError | 129 |
| speed:TimeoutError | 47 |
| cn-block:TimeoutError | 44 |
| geo:ClientOSError | 23 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 6 |
| 204:ProxyError | 5 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4036 |
| ConnectionRefusedError | 700 |
| gaierror | 355 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 76 | 1.0 | 119 |
| Au1rxx-base64 | 0.954 | prefer | 458 | 0.902 | 1356 |
| Surfboard-tg-mixed | 0.689 | observe | 251 | 0.61 | 5480 |
| mheidari-all | 0.604 | observe | 408 | 0.525 | 17144 |
| DeltaKronecker-all | 0.369 | observe | 126 | 0.286 | 5838 |
| tg-ConfigV2rayNG | 0.263 | observe | 1 | 1.0 | 200 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4879 |
| Epodonios-all | 0.255 | observe | 0 | None | 6569 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6329 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.286 | 36 | 90 | 126 |
| mheidari-all | 0.525 | 214 | 194 | 408 |
| Surfboard-tg-mixed | 0.61 | 153 | 98 | 251 |
| Au1rxx-base64 | 0.902 | 413 | 45 | 458 |
| tg-ConfigV2rayNG | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 76 | 0 | 76 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17224 | yes | 4.6 | 0 |
| Epodonios-all | 6569 | yes | 1.41 | 0 |
| SoliSpirit-all | 6329 | yes | 3.72 | 0 |
| DeltaKronecker-all | 5838 | yes | 4.75 | 0 |
| Surfboard-tg-mixed | 5480 | yes | 3.54 | 0 |
| mahdibland-V2RayAggregator | 4980 | yes | 1.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 4879 | yes | 2.55 | 0 |
| barry-far-vless | 4852 | yes | 1.94 | 0 |
| Surfboard-tg-vless | 4211 | yes | 3.36 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 2.88 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 207 |
| geo | 152 |
| cn-block | 53 |
| 204 | 18 |
