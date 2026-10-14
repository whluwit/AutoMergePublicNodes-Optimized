# AutoNodes 每日报告

生成时间：2026-10-14 11:12:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98253 |
| 去重后节点数 | 27177 |
| TCP 可达数 | 3000 |
| 真测通过数 | 335 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27177 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| generate | 76.6 |
| geo | 1.5 |
| probe | 230.0 |
| real_test | 225.2 |
| tcp | 47.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 60 | 32 | 28 | 53.3% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 128 | 120 | 8 | 93.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 50 | 37 | 13 | 74.0% |
| vless | 188 | 129 | 59 | 68.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 32 |
| 204:ProxyError | 28 |
| cn-block:TimeoutError | 20 |
| geo:ClientOSError | 9 |
| speed:ClientOSError | 6 |
| 204:ProxyConnectionError | 5 |
| speed:TimeoutError | 4 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6756 |
| ConnectionRefusedError | 1039 |
| gaierror | 291 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.916 | prefer | 255 | 0.847 | 1786 |
| zhangkai | 0.894 | prefer | 18 | 1.0 | 144 |
| mheidari-all | 0.892 | prefer | 46 | 0.826 | 23983 |
| Surfboard-tg-mixed | 0.67 | observe | 76 | 0.592 | 7056 |
| ermaozi-get_subscribe | 0.42 | observe | 46 | 0.391 | 598 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7542 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10026 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5579 |

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
| downweight | DeltaKronecker-all | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 5 | 5 |
| ermaozi-get_subscribe | 0.391 | 18 | 28 | 46 |
| Surfboard-tg-mixed | 0.592 | 45 | 31 | 76 |
| mheidari-all | 0.826 | 38 | 8 | 46 |
| Au1rxx-base64 | 0.847 | 216 | 39 | 255 |
| zhangkai | 1.0 | 18 | 0 | 18 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23983 | yes | 8.57 | 0 |
| SoliSpirit-all | 10026 | yes | 3.43 | 0 |
| Epodonios-all | 7542 | yes | 6.48 | 0 |
| Surfboard-tg-mixed | 7056 | yes | 5.07 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 4.08 | 0 |
| barry-far-vless | 5831 | yes | 2.74 | 0 |
| Surfboard-tg-vless | 5579 | yes | 4.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 2.23 | 0 |
| DeltaKronecker-all | 4803 | yes | 6.98 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 3.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 67 |
| cn-block | 23 |
| geo | 12 |
| speed | 10 |
