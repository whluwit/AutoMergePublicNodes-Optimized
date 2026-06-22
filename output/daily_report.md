# AutoNodes 每日报告

生成时间：2026-06-22 13:00:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 76222 |
| 去重后节点数 | 22594 |
| TCP 可达数 | 3000 |
| 真测通过数 | 713 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22594 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 43.5 |
| geo | 1.3 |
| probe | 62.7 |
| real_test | 158.0 |
| tcp | 30.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 69 | 69 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 77 | 73 | 4 | 94.8% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 67 | 60 | 7 | 89.6% |
| vless | 795 | 503 | 292 | 63.3% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 94 |
| 204:TimeoutError | 71 |
| geo:TimeoutError | 55 |
| 204:ProxyError | 26 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 15 |
| 204:ClientOSError | 10 |
| speed:TimeoutError | 10 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4231 |
| ConnectionRefusedError | 598 |
| gaierror | 187 |
| OSError | 106 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.991 | prefer | 69 | 1.0 | 131 |
| Au1rxx-base64 | 0.927 | prefer | 87 | 0.931 | 150 |
| mheidari-all | 0.861 | prefer | 308 | 0.782 | 14984 |
| DeltaKronecker-all | 0.658 | observe | 538 | 0.578 | 7452 |
| Surfboard-tg-mixed | 0.57 | observe | 11 | 0.727 | 5324 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| nscl5-all | 0.31 | observe | 1 | 1.0 | 1364 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4466 |
| Epodonios-all | 0.255 | observe | 0 | None | 7787 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3982 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.578 | 311 | 227 | 538 |
| Surfboard-tg-mixed | 0.727 | 8 | 3 | 11 |
| mheidari-all | 0.782 | 241 | 67 | 308 |
| Au1rxx-base64 | 0.931 | 81 | 6 | 87 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 69 | 0 | 69 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14984 | yes | 4.07 | 0 |
| Epodonios-all | 7787 | yes | 2.43 | 0 |
| DeltaKronecker-all | 7452 | yes | 3.38 | 0 |
| SoliSpirit-all | 7031 | yes | 2.4 | 0 |
| Surfboard-tg-mixed | 5324 | yes | 1.93 | 0 |
| barry-far-vless | 4897 | yes | 2.04 | 0 |
| mahdibland-V2RayAggregator | 4559 | yes | 1.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 4466 | yes | 1.64 | 0 |
| Surfboard-tg-vless | 4148 | yes | 2.76 | 0 |
| MatinGhanbari-all-sub | 3982 | yes | 1.87 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 107 |
| speed | 105 |
| geo | 70 |
| cn-block | 21 |
