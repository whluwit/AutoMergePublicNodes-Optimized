# AutoNodes 每日报告

生成时间：2026-07-01 03:02:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 75310 |
| 去重后节点数 | 23048 |
| TCP 可达数 | 3000 |
| 真测通过数 | 544 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23048 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| generate | 31.8 |
| geo | 1.4 |
| probe | 54.2 |
| real_test | 106.7 |
| tcp | 30.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 5 | 3 | 2 | 60.0% |
| shadowsocks | 139 | 127 | 12 | 91.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 155 | 128 | 27 | 82.6% |
| vless | 491 | 246 | 245 | 50.1% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 146 |
| geo:TimeoutError | 63 |
| speed:TimeoutError | 30 |
| geo:ClientOSError | 19 |
| cn-block:TimeoutError | 8 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ClientPayloadError | 1 |
| 204:TimeoutError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4305 |
| ConnectionRefusedError | 630 |
| gaierror | 159 |
| OSError | 144 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.827 | prefer | 350 | 0.749 | 5600 |
| Au1rxx-base64 | 0.808 | prefer | 49 | 0.816 | 93 |
| mheidari-all | 0.693 | observe | 259 | 0.614 | 15713 |
| DeltaKronecker-all | 0.49 | observe | 98 | 0.408 | 7352 |
| nscl5-all | 0.356 | observe | 2 | 1.0 | 1113 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| ermaozi | 0.256 | observe | 1 | 1.0 | 28 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.114 | downweight | 30 | 0.033 | 0 | 1298 |
| chromego_merge | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| peasoft-NoMoreWalls | 0.175 | observe | 0 | None | 0 | 3 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.114 | 30 | 0.033 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| xiaoji235-airport-v2ray-all | 0.033 | 1 | 29 | 30 |
| DeltaKronecker-all | 0.408 | 40 | 58 | 98 |
| mheidari-all | 0.614 | 159 | 100 | 259 |
| Surfboard-tg-mixed | 0.749 | 262 | 88 | 350 |
| Au1rxx-base64 | 0.816 | 40 | 9 | 49 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15713 | yes | 3.16 | 0 |
| DeltaKronecker-all | 7352 | yes | 3.31 | 0 |
| Epodonios-all | 6537 | yes | 1.44 | 0 |
| SoliSpirit-all | 6510 | yes | 1.72 | 0 |
| Surfboard-tg-mixed | 5600 | yes | 2.05 | 0 |
| mahdibland-V2RayAggregator | 5373 | yes | 2.54 | 0 |
| barry-far-vless | 4706 | yes | 1.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 4139 | yes | 1.41 | 0 |
| Surfboard-tg-vless | 4134 | yes | 1.57 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.09 | 0 |

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
| speed | 178 |
| geo | 82 |
| cn-block | 15 |
| 204 | 12 |
