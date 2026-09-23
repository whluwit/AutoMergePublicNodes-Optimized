# AutoNodes 每日报告

生成时间：2026-09-23 03:19:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96683 |
| 去重后节点数 | 26603 |
| TCP 可达数 | 3000 |
| 真测通过数 | 524 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26603 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 77.8 |
| geo | 1.4 |
| probe | 403.4 |
| real_test | 647.5 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 34 | 23 | 11 | 67.6% |
| hysteria2 | 24 | 24 | 0 | 100.0% |
| shadowsocks | 142 | 139 | 3 | 97.9% |
| socks | 11 | 8 | 3 | 72.7% |
| trojan | 26 | 18 | 8 | 69.2% |
| vless | 989 | 311 | 678 | 31.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 300 |
| speed:TimeoutError | 112 |
| geo:ClientOSError | 96 |
| speed:ClientOSError | 81 |
| cn-block:ClientOSError | 55 |
| 204:ProxyError | 20 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 16 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6009 |
| ConnectionRefusedError | 929 |
| gaierror | 276 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.89 | prefer | 309 | 0.828 | 1598 |
| ermaozi | 0.701 | prefer | 30 | 0.7 | 346 |
| Surfboard-tg-mixed | 0.554 | observe | 36 | 0.472 | 7168 |
| DeltaKronecker-all | 0.463 | observe | 194 | 0.381 | 6324 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| mheidari-all | 0.314 | observe | 648 | 0.233 | 22274 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| ermaozi-get_subscribe | 0.283 | observe | 3 | 0.667 | 372 |
| Epodonios-all | 0.255 | observe | 0 | None | 7633 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.233 | 151 | 497 | 648 |
| ninja-vless | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.381 | 74 | 120 | 194 |
| Surfboard-tg-mixed | 0.472 | 17 | 19 | 36 |
| ermaozi-get_subscribe | 0.667 | 2 | 1 | 3 |
| ermaozi | 0.7 | 21 | 9 | 30 |
| Au1rxx-base64 | 0.828 | 256 | 53 | 309 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22274 | yes | 4.43 | 0 |
| SoliSpirit-all | 8906 | yes | 2.06 | 0 |
| Epodonios-all | 7633 | yes | 2.0 | 0 |
| Surfboard-tg-mixed | 7168 | yes | 2.61 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.85 | 0 |
| DeltaKronecker-all | 6324 | yes | 4.53 | 0 |
| barry-far-vless | 6057 | yes | 1.1 | 0 |
| Surfboard-tg-vless | 5836 | yes | 3.16 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 0.95 | 0 |
| mahdibland-V2RayAggregator | 4252 | yes | 0.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 397 |
| speed | 194 |
| cn-block | 71 |
| 204 | 41 |
