# AutoNodes 每日报告

生成时间：2026-07-10 09:30:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 75290 |
| 去重后节点数 | 23405 |
| TCP 可达数 | 3000 |
| 真测通过数 | 339 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23405 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 27.5 |
| geo | 1.5 |
| probe | 45.3 |
| real_test | 90.2 |
| tcp | 31.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 88 | 80 | 8 | 90.9% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 190 | 168 | 22 | 88.4% |
| vless | 137 | 47 | 90 | 34.3% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 42 |
| geo:TimeoutError | 26 |
| 204:ProxyError | 15 |
| 204:ClientOSError | 8 |
| 204:TimeoutError | 8 |
| speed:TimeoutError | 8 |
| geo:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| cn-block:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4250 |
| ConnectionRefusedError | 669 |
| gaierror | 286 |
| OSError | 176 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.924 | prefer | 19 | 1.0 | 75 |
| DeltaKronecker-all | 0.843 | prefer | 192 | 0.766 | 7600 |
| Surfboard-tg-mixed | 0.74 | prefer | 204 | 0.662 | 5466 |
| nscl5-all | 0.301 | observe | 1 | 1.0 | 1148 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4165 |
| Epodonios-all | 0.255 | observe | 0 | None | 6278 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6680 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| mheidari-all | 0.144 | downweight | 7 | 0.0 | 0 | 15738 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.144 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.0 | 0 | 7 | 7 |
| Surfboard-tg-mixed | 0.662 | 135 | 69 | 204 |
| DeltaKronecker-all | 0.766 | 147 | 45 | 192 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 19 | 0 | 19 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15738 | yes | 3.35 | 0 |
| DeltaKronecker-all | 7600 | yes | 3.97 | 0 |
| SoliSpirit-all | 6680 | yes | 2.32 | 0 |
| Epodonios-all | 6278 | yes | 1.85 | 0 |
| Surfboard-tg-mixed | 5466 | yes | 2.3 | 0 |
| mahdibland-V2RayAggregator | 5391 | yes | 1.68 | 0 |
| barry-far-vless | 4587 | yes | 1.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4165 | yes | 1.52 | 0 |
| Surfboard-tg-vless | 4082 | yes | 2.13 | 0 |
| MatinGhanbari-all-sub | 3976 | yes | 1.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 51 |
| 204 | 31 |
| geo | 31 |
| cn-block | 9 |
