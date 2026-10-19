# AutoNodes 每日报告

生成时间：2026-10-19 12:05:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 95360 |
| 去重后节点数 | 26130 |
| TCP 可达数 | 3000 |
| 真测通过数 | 350 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26130 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 81.6 |
| geo | 1.6 |
| probe | 255.8 |
| real_test | 210.2 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 62 | 26 | 36 | 41.9% |
| hysteria2 | 17 | 14 | 3 | 82.4% |
| shadowsocks | 145 | 130 | 15 | 89.7% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 38 | 19 | 19 | 50.0% |
| vless | 233 | 159 | 74 | 68.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 43 |
| 204:TimeoutError | 30 |
| cn-block:TimeoutError | 18 |
| geo:ClientOSError | 17 |
| speed:ClientOSError | 13 |
| geo:TimeoutError | 8 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6598 |
| ConnectionRefusedError | 1040 |
| OSError | 238 |
| gaierror | 172 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.87 | prefer | 361 | 0.803 | 1716 |
| Surfboard-tg-mixed | 0.552 | observe | 51 | 0.471 | 6867 |
| mheidari-all | 0.543 | observe | 13 | 0.615 | 23446 |
| ermaozi | 0.459 | observe | 63 | 0.429 | 696 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| Epodonios-all | 0.255 | observe | 0 | None | 7331 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9767 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5407 |
| barry-far-vless | 0.255 | observe | 0 | None | 5622 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.193 | 10 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.1 | 1 | 9 | 10 |
| ermaozi | 0.429 | 27 | 36 | 63 |
| Surfboard-tg-mixed | 0.471 | 24 | 27 | 51 |
| mheidari-all | 0.615 | 8 | 5 | 13 |
| Au1rxx-base64 | 0.803 | 290 | 71 | 361 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23446 | yes | 3.29 | 0 |
| SoliSpirit-all | 9767 | yes | 2.04 | 0 |
| Epodonios-all | 7331 | yes | 3.41 | 0 |
| Surfboard-tg-mixed | 6867 | yes | 2.38 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.32 | 0 |
| barry-far-vless | 5622 | yes | 0.69 | 0 |
| Surfboard-tg-vless | 5407 | yes | 2.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 0.45 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 1.77 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.73 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 76 |
| geo | 26 |
| cn-block | 25 |
| speed | 21 |
