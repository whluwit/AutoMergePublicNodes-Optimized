# AutoNodes 每日报告

生成时间：2026-07-01 14:29:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 77019 |
| 去重后节点数 | 23292 |
| TCP 可达数 | 3000 |
| 真测通过数 | 258 |
| verified 输出数 | 258 |
| global 输出数 | 272 |
| all 输出数 | 23292 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 36.2 |
| geo | 1.5 |
| probe | 47.8 |
| real_test | 94.0 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 7 | 2 | 5 | 28.6% |
| shadowsocks | 94 | 76 | 18 | 80.9% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 322 | 117 | 205 | 36.3% |
| vless | 76 | 21 | 55 | 27.6% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 200 |
| 204:TimeoutError | 18 |
| geo:TimeoutError | 13 |
| cn-block:TimeoutError | 12 |
| geo:ClientOSError | 11 |
| 204:ClientOSError | 11 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| speed:TimeoutError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4462 |
| ConnectionRefusedError | 646 |
| OSError | 143 |
| gaierror | 138 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.786 | prefer | 44 | 0.795 | 87 |
| Surfboard-tg-mixed | 0.65 | observe | 149 | 0.57 | 5922 |
| DeltaKronecker-all | 0.411 | observe | 300 | 0.33 | 7631 |
| mheidari-all | 0.272 | observe | 7 | 0.286 | 15660 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4308 |
| Epodonios-all | 0.255 | observe | 0 | None | 6803 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6937 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.125 | downweight | 5 | 0.0 | 0 | 1298 |
| chromego_merge | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| peasoft-NoMoreWalls | 0.175 | observe | 0 | None | 0 | 3 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.125 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 5 | 5 |
| mheidari-all | 0.286 | 2 | 5 | 7 |
| DeltaKronecker-all | 0.33 | 99 | 201 | 300 |
| Surfboard-tg-mixed | 0.57 | 85 | 64 | 149 |
| Au1rxx-base64 | 0.795 | 35 | 9 | 44 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15660 | yes | 3.02 | 0 |
| DeltaKronecker-all | 7631 | yes | 3.22 | 0 |
| SoliSpirit-all | 6937 | yes | 2.0 | 0 |
| Epodonios-all | 6803 | yes | 0.53 | 0 |
| Surfboard-tg-mixed | 5922 | yes | 2.18 | 0 |
| mahdibland-V2RayAggregator | 5331 | yes | 0.62 | 0 |
| barry-far-vless | 4908 | yes | 0.43 | 0 |
| Surfboard-tg-vless | 4402 | yes | 2.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4308 | yes | 0.95 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.03 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 204 |
| 204 | 35 |
| geo | 24 |
| cn-block | 21 |
