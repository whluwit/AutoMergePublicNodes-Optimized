# AutoNodes 每日报告

生成时间：2026-07-15 08:03:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 75501 |
| 去重后节点数 | 22798 |
| TCP 可达数 | 3000 |
| 真测通过数 | 368 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22798 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 30.3 |
| geo | 1.3 |
| probe | 50.5 |
| real_test | 107.7 |
| tcp | 31.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 124 | 105 | 19 | 84.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 236 | 204 | 32 | 86.4% |
| vless | 113 | 15 | 98 | 13.3% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 54 |
| speed:ClientOSError | 45 |
| 204:TimeoutError | 11 |
| cn-block:ClientOSError | 9 |
| speed:TimeoutError | 7 |
| cn-block:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| geo:ClientOSError | 4 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4166 |
| ConnectionRefusedError | 645 |
| gaierror | 366 |
| OSError | 208 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.802 | prefer | 106 | 0.802 | 149 |
| mheidari-all | 0.787 | prefer | 97 | 0.711 | 16158 |
| Surfboard-tg-mixed | 0.758 | prefer | 119 | 0.681 | 5625 |
| DeltaKronecker-all | 0.684 | observe | 157 | 0.605 | 6421 |
| nscl5-all | 0.307 | observe | 1 | 1.0 | 1300 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3759 |
| Epodonios-all | 0.255 | observe | 0 | None | 6608 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3975 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.605 | 95 | 62 | 157 |
| Surfboard-tg-mixed | 0.681 | 81 | 38 | 119 |
| mheidari-all | 0.711 | 69 | 28 | 97 |
| Au1rxx-base64 | 0.802 | 85 | 21 | 106 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16158 | yes | 2.85 | 0 |
| Epodonios-all | 6608 | yes | 3.02 | 0 |
| SoliSpirit-all | 6441 | yes | 1.87 | 0 |
| DeltaKronecker-all | 6421 | yes | 3.1 | 0 |
| Surfboard-tg-mixed | 5625 | yes | 2.03 | 0 |
| mahdibland-V2RayAggregator | 5187 | yes | 1.51 | 0 |
| barry-far-vless | 4712 | yes | 1.07 | 0 |
| Surfboard-tg-vless | 4133 | yes | 1.88 | 0 |
| MatinGhanbari-all-sub | 3975 | yes | 0.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 3759 | yes | 0.92 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 59 |
| speed | 54 |
| 204 | 20 |
| cn-block | 17 |
