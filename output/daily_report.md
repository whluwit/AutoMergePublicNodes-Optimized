# AutoNodes 每日报告

生成时间：2026-07-27 19:25:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85908 |
| 去重后节点数 | 22911 |
| TCP 可达数 | 3000 |
| 真测通过数 | 748 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22911 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 30.9 |
| geo | 1.1 |
| probe | 64.2 |
| real_test | 165.4 |
| tcp | 31.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 59 | 59 | 0 | 100.0% |
| hysteria2 | 12 | 10 | 2 | 83.3% |
| shadowsocks | 141 | 119 | 22 | 84.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 455 | 426 | 29 | 93.6% |
| vless | 298 | 132 | 166 | 44.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 84 |
| speed:ClientOSError | 42 |
| 204:TimeoutError | 24 |
| geo:ClientOSError | 17 |
| cn-block:TimeoutError | 16 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 8 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4162 |
| ConnectionRefusedError | 739 |
| gaierror | 329 |
| OSError | 223 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.996 | prefer | 450 | 0.938 | 1499 |
| zhangkai | 0.987 | prefer | 59 | 1.0 | 74 |
| mheidari-all | 0.839 | prefer | 143 | 0.762 | 19371 |
| DeltaKronecker-all | 0.617 | observe | 134 | 0.537 | 5643 |
| Surfboard-tg-mixed | 0.552 | observe | 178 | 0.472 | 5739 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3959 |
| MatinGhanbari-super-sub | 0.263 | observe | 1 | 1.0 | 199 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4831 |
| Epodonios-all | 0.255 | observe | 0 | None | 6710 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.472 | 84 | 94 | 178 |
| DeltaKronecker-all | 0.537 | 72 | 62 | 134 |
| mheidari-all | 0.762 | 109 | 34 | 143 |
| Au1rxx-base64 | 0.938 | 422 | 28 | 450 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| MatinGhanbari-super-sub | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 59 | 0 | 59 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19371 | yes | 3.47 | 0 |
| Epodonios-all | 6710 | yes | 1.78 | 0 |
| SoliSpirit-all | 6251 | yes | 2.4 | 0 |
| Surfboard-tg-mixed | 5739 | yes | 2.22 | 0 |
| DeltaKronecker-all | 5643 | yes | 3.55 | 0 |
| barry-far-vless | 5170 | yes | 1.94 | 0 |
| mahdibland-V2RayAggregator | 4997 | yes | 1.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 4831 | yes | 1.49 | 0 |
| Surfboard-tg-vless | 4648 | yes | 2.32 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 1.83 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 102 |
| speed | 50 |
| 204 | 41 |
| cn-block | 27 |
