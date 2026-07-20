# AutoNodes 每日报告

生成时间：2026-07-20 14:01:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 85548 |
| 去重后节点数 | 24075 |
| TCP 可达数 | 3000 |
| 真测通过数 | 392 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24075 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 36.8 |
| geo | 1.1 |
| probe | 58.0 |
| real_test | 137.0 |
| tcp | 33.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 34 | 2 | 94.4% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 128 | 108 | 20 | 84.4% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 183 | 150 | 33 | 82.0% |
| vless | 484 | 94 | 390 | 19.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 282 |
| speed:ClientOSError | 77 |
| cn-block:TimeoutError | 31 |
| geo:ClientOSError | 16 |
| 204:TimeoutError | 12 |
| speed:TimeoutError | 8 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 5 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4778 |
| ConnectionRefusedError | 688 |
| gaierror | 304 |
| OSError | 215 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.923 | prefer | 36 | 0.944 | 61 |
| Au1rxx-base64 | 0.899 | prefer | 242 | 0.864 | 969 |
| Surfboard-tg-mixed | 0.531 | observe | 173 | 0.451 | 5287 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5035 |
| mheidari-all | 0.293 | observe | 299 | 0.211 | 19893 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4714 |
| Epodonios-all | 0.255 | observe | 0 | None | 6550 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6890 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| DeltaKronecker-all | 0.16 | downweight | 85 | 0.071 | 0 | 5962 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.16 | 85 | 0.071 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.071 | 6 | 79 | 85 |
| mheidari-all | 0.211 | 63 | 236 | 299 |
| Surfboard-tg-mixed | 0.451 | 78 | 95 | 173 |
| Au1rxx-base64 | 0.864 | 209 | 33 | 242 |
| zhangkai | 0.944 | 34 | 2 | 36 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19893 | yes | 3.43 | 0 |
| SoliSpirit-all | 6890 | yes | 2.25 | 0 |
| Epodonios-all | 6550 | yes | 2.93 | 0 |
| DeltaKronecker-all | 5962 | yes | 3.6 | 0 |
| Surfboard-tg-mixed | 5287 | yes | 1.88 | 0 |
| mahdibland-V2RayAggregator | 5193 | yes | 1.5 | 0 |
| xiaoji235-airport-v2ray-all | 5035 | yes | 1.26 | 0 |
| barry-far-vless | 4908 | yes | 0.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4714 | yes | 1.05 | 0 |
| Surfboard-tg-vless | 4082 | yes | 2.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 299 |
| speed | 86 |
| cn-block | 37 |
| 204 | 23 |
