# AutoNodes 每日报告

生成时间：2026-07-22 13:45:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 82331 |
| 去重后节点数 | 22710 |
| TCP 可达数 | 3000 |
| 真测通过数 | 533 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22710 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 42.7 |
| geo | 1.3 |
| probe | 60.1 |
| real_test | 150.7 |
| tcp | 31.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 16 | 7 | 9 | 43.8% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 445 | 399 | 46 | 89.7% |
| vless | 324 | 84 | 240 | 25.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 99 |
| speed:ClientOSError | 92 |
| cn-block:TimeoutError | 26 |
| 204:TimeoutError | 23 |
| geo:ClientOSError | 20 |
| speed:TimeoutError | 16 |
| cn-block:ProxyError | 6 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4198 |
| ConnectionRefusedError | 687 |
| gaierror | 309 |
| OSError | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.883 | prefer | 59 | 0.814 | 5401 |
| mheidari-all | 0.699 | observe | 588 | 0.619 | 19287 |
| DeltaKronecker-all | 0.647 | observe | 139 | 0.568 | 5212 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 4246 |
| Au1rxx-base64 | 0.329 | observe | 2 | 1.0 | 432 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4613 |
| Epodonios-all | 0.255 | observe | 0 | None | 6476 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.568 | 79 | 60 | 139 |
| mheidari-all | 0.619 | 364 | 224 | 588 |
| Surfboard-tg-mixed | 0.814 | 48 | 11 | 59 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19287 | yes | 4.0 | 0 |
| SoliSpirit-all | 6830 | yes | 2.4 | 0 |
| Epodonios-all | 6476 | yes | 1.43 | 0 |
| Surfboard-tg-mixed | 5401 | yes | 1.24 | 0 |
| DeltaKronecker-all | 5212 | yes | 4.23 | 0 |
| mahdibland-V2RayAggregator | 5204 | yes | 0.2 | 0 |
| barry-far-vless | 4805 | yes | 1.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 4613 | yes | 1.97 | 0 |
| xiaoji235-airport-v2ray-all | 4246 | yes | 1.77 | 0 |
| Surfboard-tg-vless | 4210 | yes | 2.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 121 |
| speed | 108 |
| cn-block | 35 |
| 204 | 32 |
