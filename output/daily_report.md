# AutoNodes 每日报告

生成时间：2026-07-31 02:27:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 78339 |
| 去重后节点数 | 23008 |
| TCP 可达数 | 3000 |
| 真测通过数 | 593 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23008 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 36.0 |
| geo | 1.4 |
| probe | 60.5 |
| real_test | 157.1 |
| tcp | 32.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 154 | 146 | 8 | 94.8% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 53 | 47 | 6 | 88.7% |
| vless | 739 | 271 | 468 | 36.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 267 |
| speed:ClientOSError | 64 |
| geo:ClientOSError | 54 |
| speed:TimeoutError | 53 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4474 |
| ConnectionRefusedError | 751 |
| gaierror | 283 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | prefer | 113 | 1.0 | 129 |
| Au1rxx-base64 | 0.976 | prefer | 238 | 0.929 | 1272 |
| Surfboard-tg-mixed | 0.721 | prefer | 204 | 0.642 | 5393 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| DeltaKronecker-all | 0.328 | observe | 503 | 0.247 | 5759 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 43 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5342 |
| Epodonios-all | 0.255 | observe | 0 | None | 6141 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6717 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.231 | 14 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.143 | 2 | 12 | 14 |
| DeltaKronecker-all | 0.247 | 124 | 379 | 503 |
| Surfboard-tg-mixed | 0.642 | 131 | 73 | 204 |
| Au1rxx-base64 | 0.929 | 221 | 17 | 238 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16264 | yes | 4.14 | 0 |
| SoliSpirit-all | 6717 | yes | 1.7 | 0 |
| Epodonios-all | 6141 | yes | 2.17 | 0 |
| DeltaKronecker-all | 5759 | yes | 4.2 | 0 |
| Surfboard-tg-mixed | 5393 | yes | 3.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 5342 | yes | 1.41 | 0 |
| mahdibland-V2RayAggregator | 5047 | yes | 2.25 | 0 |
| barry-far-vless | 4647 | yes | 0.76 | 0 |
| Surfboard-tg-vless | 4267 | yes | 2.5 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 322 |
| speed | 117 |
| cn-block | 25 |
| 204 | 21 |
