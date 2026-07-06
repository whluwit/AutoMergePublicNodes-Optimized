# AutoNodes 每日报告

生成时间：2026-07-06 15:26:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 79734 |
| 去重后节点数 | 24473 |
| TCP 可达数 | 3000 |
| 真测通过数 | 353 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24473 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 28.3 |
| geo | 1.4 |
| probe | 51.1 |
| real_test | 92.9 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 135 | 117 | 18 | 86.7% |
| socks | 13 | 8 | 5 | 61.5% |
| trojan | 190 | 173 | 17 | 91.1% |
| vless | 41 | 11 | 30 | 26.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 21 |
| 204:ClientOSError | 13 |
| geo:TimeoutError | 9 |
| 204:TimeoutError | 6 |
| speed:TimeoutError | 5 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4484 |
| ConnectionRefusedError | 776 |
| OSError | 158 |
| gaierror | 125 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.902 | prefer | 105 | 0.829 | 5986 |
| mheidari-all | 0.897 | prefer | 107 | 0.822 | 16268 |
| DeltaKronecker-all | 0.877 | prefer | 136 | 0.801 | 8330 |
| Au1rxx-base64 | 0.848 | prefer | 30 | 0.867 | 98 |
| nscl5-all | 0.377 | observe | 2 | 1.0 | 1651 |
| tg-LonUp_M | 0.327 | observe | 4 | 0.75 | 178 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4358 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.75 | 3 | 1 | 4 |
| DeltaKronecker-all | 0.801 | 109 | 27 | 136 |
| mheidari-all | 0.822 | 88 | 19 | 107 |
| Surfboard-tg-mixed | 0.829 | 87 | 18 | 105 |
| Au1rxx-base64 | 0.867 | 26 | 4 | 30 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16268 | yes | 3.42 | 0 |
| DeltaKronecker-all | 8330 | yes | 4.02 | 0 |
| SoliSpirit-all | 7108 | yes | 3.02 | 0 |
| Epodonios-all | 6989 | yes | 2.01 | 0 |
| Surfboard-tg-mixed | 5986 | yes | 2.68 | 0 |
| mahdibland-V2RayAggregator | 5349 | yes | 1.03 | 0 |
| barry-far-vless | 5099 | yes | 2.17 | 0 |
| Surfboard-tg-vless | 4436 | yes | 2.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 4358 | yes | 1.78 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 26 |
| 204 | 23 |
| geo | 13 |
| cn-block | 8 |
