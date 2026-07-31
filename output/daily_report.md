# AutoNodes 每日报告

生成时间：2026-07-31 19:21:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78880 |
| 去重后节点数 | 22839 |
| TCP 可达数 | 3000 |
| 真测通过数 | 421 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22839 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 29.6 |
| geo | 1.3 |
| probe | 56.0 |
| real_test | 106.7 |
| tcp | 33.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 80 | 80 | 0 | 100.0% |
| hysteria2 | 17 | 12 | 5 | 70.6% |
| shadowsocks | 110 | 90 | 20 | 81.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 35 | 29 | 6 | 82.9% |
| vless | 304 | 208 | 96 | 68.4% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 42 |
| 204:TimeoutError | 17 |
| speed:TimeoutError | 15 |
| 204:ProxyError | 14 |
| speed:ClientOSError | 11 |
| cn-block:TimeoutError | 8 |
| geo:ClientOSError | 8 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| speed:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4574 |
| ConnectionRefusedError | 778 |
| gaierror | 256 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 80 | 1.0 | 110 |
| Au1rxx-base64 | 0.83 | prefer | 396 | 0.765 | 1655 |
| DeltaKronecker-all | 0.622 | observe | 15 | 0.667 | 5144 |
| Surfboard-tg-mixed | 0.542 | observe | 24 | 0.458 | 5433 |
| mheidari-all | 0.537 | observe | 33 | 0.455 | 16449 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 51 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5507 |
| Epodonios-all | 0.255 | observe | 0 | None | 6115 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.455 | 15 | 18 | 33 |
| Surfboard-tg-mixed | 0.458 | 11 | 13 | 24 |
| DeltaKronecker-all | 0.667 | 10 | 5 | 15 |
| Au1rxx-base64 | 0.765 | 303 | 93 | 396 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 80 | 0 | 80 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16449 | yes | 5.23 | 0 |
| SoliSpirit-all | 6602 | yes | 3.65 | 0 |
| Epodonios-all | 6115 | yes | 5.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 5507 | yes | 1.92 | 0 |
| Surfboard-tg-mixed | 5433 | yes | 3.56 | 0 |
| DeltaKronecker-all | 5144 | yes | 5.37 | 0 |
| mahdibland-V2RayAggregator | 5081 | yes | 3.01 | 0 |
| barry-far-vless | 4677 | yes | 1.29 | 0 |
| Surfboard-tg-vless | 4317 | yes | 3.27 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 1.39 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 51 |
| 204 | 35 |
| speed | 29 |
| cn-block | 15 |
