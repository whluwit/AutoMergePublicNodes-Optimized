# AutoNodes 每日报告

生成时间：2026-09-24 03:09:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 96863 |
| 去重后节点数 | 26603 |
| TCP 可达数 | 3000 |
| 真测通过数 | 575 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26603 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 90.0 |
| geo | 1.5 |
| probe | 343.8 |
| real_test | 634.9 |
| tcp | 43.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 56 | 34 | 22 | 60.7% |
| hysteria2 | 23 | 22 | 1 | 95.7% |
| shadowsocks | 183 | 175 | 8 | 95.6% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 31 | 13 | 18 | 41.9% |
| vless | 877 | 321 | 556 | 36.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 231 |
| speed:TimeoutError | 113 |
| geo:ClientOSError | 59 |
| cn-block:ClientOSError | 58 |
| speed:ClientOSError | 54 |
| 204:ProxyError | 32 |
| 204:TimeoutError | 30 |
| cn-block:TimeoutError | 21 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6170 |
| ConnectionRefusedError | 946 |
| gaierror | 336 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.951 | prefer | 258 | 0.888 | 1648 |
| Surfboard-tg-mixed | 0.864 | prefer | 95 | 0.789 | 7099 |
| ermaozi | 0.643 | observe | 52 | 0.635 | 339 |
| mheidari-all | 0.385 | observe | 761 | 0.305 | 22298 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4332 |
| DeltaKronecker-all | 0.3 | observe | 5 | 0.4 | 6471 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5131 |
| Epodonios-all | 0.255 | observe | 0 | None | 7563 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8875 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.235 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.305 | 232 | 529 | 761 |
| ninja-vless | 0.333 | 1 | 2 | 3 |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| DeltaKronecker-all | 0.4 | 2 | 3 | 5 |
| ermaozi | 0.635 | 33 | 19 | 52 |
| Surfboard-tg-mixed | 0.789 | 75 | 20 | 95 |
| Au1rxx-base64 | 0.888 | 229 | 29 | 258 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22298 | yes | 5.41 | 0 |
| SoliSpirit-all | 8875 | yes | 3.51 | 0 |
| Epodonios-all | 7563 | yes | 2.84 | 0 |
| Surfboard-tg-mixed | 7099 | yes | 3.08 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.35 | 0 |
| DeltaKronecker-all | 6471 | yes | 4.76 | 0 |
| barry-far-vless | 5948 | yes | 1.9 | 0 |
| Surfboard-tg-vless | 5729 | yes | 3.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 3.07 | 0 |
| mahdibland-V2RayAggregator | 4332 | yes | 2.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 291 |
| speed | 168 |
| cn-block | 81 |
| 204 | 66 |
