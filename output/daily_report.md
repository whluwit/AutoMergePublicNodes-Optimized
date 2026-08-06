# AutoNodes 每日报告

生成时间：2026-08-06 02:11:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 88519 |
| 去重后节点数 | 24703 |
| TCP 可达数 | 3000 |
| 真测通过数 | 525 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24703 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| generate | 34.5 |
| geo | 1.3 |
| probe | 52.8 |
| real_test | 130.3 |
| tcp | 36.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 15 | 15 | 0 | 100.0% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 160 | 149 | 11 | 93.1% |
| socks | 13 | 9 | 4 | 69.2% |
| trojan | 164 | 151 | 13 | 92.1% |
| vless | 518 | 178 | 340 | 34.4% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 178 |
| speed:TimeoutError | 60 |
| geo:ClientOSError | 50 |
| speed:ClientOSError | 45 |
| 204:TimeoutError | 11 |
| cn-block:TimeoutError | 10 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5007 |
| ConnectionRefusedError | 829 |
| gaierror | 333 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 362 | 0.961 | 1423 |
| zhangkai | 0.789 | prefer | 15 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.673 | observe | 180 | 0.594 | 5917 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5260 |
| Epodonios-all | 0.255 | observe | 0 | None | 6515 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7468 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4798 |
| barry-far-vless | 0.255 | observe | 0 | None | 5104 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.205 | 38 | 0.105 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.105 | 4 | 34 | 38 |
| mheidari-all | 0.172 | 50 | 241 | 291 |
| Surfboard-tg-mixed | 0.594 | 107 | 73 | 180 |
| Au1rxx-base64 | 0.961 | 348 | 14 | 362 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 15 | 0 | 15 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21048 | yes | 4.33 | 0 |
| SoliSpirit-all | 7468 | yes | 3.38 | 0 |
| Epodonios-all | 6515 | yes | 4.8 | 0 |
| Surfboard-tg-mixed | 5917 | yes | 3.46 | 0 |
| DeltaKronecker-all | 5316 | yes | 4.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 5260 | yes | 2.35 | 0 |
| mahdibland-V2RayAggregator | 5206 | yes | 2.27 | 0 |
| barry-far-vless | 5104 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 4798 | yes | 2.92 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 230 |
| speed | 106 |
| 204 | 19 |
| cn-block | 14 |
