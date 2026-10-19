# AutoNodes 每日报告

生成时间：2026-10-19 18:25:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 1/104 |
| 原始节点数 | 94362 |
| 去重后节点数 | 26032 |
| TCP 可达数 | 3000 |
| 真测通过数 | 341 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26032 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| generate | 83.5 |
| geo | 1.6 |
| probe | 232.5 |
| real_test | 206.3 |
| tcp | 44.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 18 | 12 | 6 | 66.7% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 133 | 107 | 26 | 80.5% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 27 | 24 | 3 | 88.9% |
| vless | 248 | 182 | 66 | 73.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 18 |
| geo:ClientOSError | 14 |
| speed:ClientOSError | 13 |
| 204:ProxyError | 10 |
| speed:TimeoutError | 7 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| cn-block:ClientOSError | 3 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6601 |
| ConnectionRefusedError | 1030 |
| OSError | 239 |
| gaierror | 188 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.897 | prefer | 357 | 0.835 | 1598 |
| zhangkai | 0.654 | observe | 11 | 1.0 | 27 |
| mheidari-all | 0.612 | observe | 16 | 0.625 | 23148 |
| Surfboard-tg-mixed | 0.515 | observe | 44 | 0.432 | 6948 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 172 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| Epodonios-all | 0.255 | observe | 0 | None | 7406 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9916 |

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
| downweight | DeltaKronecker-all | 0.148 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ermaozi-get_subscribe | 0.149 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.0 | 0 | 6 | 6 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| Surfboard-tg-mixed | 0.432 | 19 | 25 | 44 |
| mheidari-all | 0.625 | 10 | 6 | 16 |
| Au1rxx-base64 | 0.835 | 298 | 59 | 357 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 11 | 0 | 11 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23148 | yes | 6.31 | 0 |
| SoliSpirit-all | 9916 | yes | 2.53 | 0 |
| Epodonios-all | 7406 | yes | 5.14 | 0 |
| Surfboard-tg-mixed | 6948 | yes | 4.19 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.58 | 0 |
| barry-far-vless | 5654 | yes | 2.0 | 0 |
| Surfboard-tg-vless | 5438 | yes | 4.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 0.9 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 2.44 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 38 |
| cn-block | 24 |
| speed | 22 |
| geo | 18 |
