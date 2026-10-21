# AutoNodes 每日报告

生成时间：2026-10-21 11:12:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96052 |
| 去重后节点数 | 26933 |
| TCP 可达数 | 3000 |
| 真测通过数 | 352 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26933 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 78.8 |
| geo | 1.4 |
| probe | 240.1 |
| real_test | 208.2 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 58 | 33 | 25 | 56.9% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 138 | 123 | 15 | 89.1% |
| socks | 3 | 3 | 0 | 100.0% |
| trojan | 54 | 37 | 17 | 68.5% |
| vless | 208 | 141 | 67 | 67.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 27 |
| cn-block:TimeoutError | 23 |
| 204:TimeoutError | 19 |
| speed:ClientOSError | 12 |
| speed:TimeoutError | 11 |
| geo:ClientOSError | 10 |
| geo:TimeoutError | 9 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6499 |
| ConnectionRefusedError | 1038 |
| gaierror | 277 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.866 | prefer | 54 | 0.796 | 23726 |
| Au1rxx-base64 | 0.846 | prefer | 258 | 0.787 | 1528 |
| Surfboard-tg-mixed | 0.766 | prefer | 100 | 0.69 | 6977 |
| ermaozi-get_subscribe | 0.592 | observe | 40 | 0.575 | 516 |
| zhangkai | 0.592 | observe | 20 | 0.6 | 31 |
| DeltaKronecker-all | 0.3 | observe | 5 | 0.4 | 4067 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| Epodonios-all | 0.255 | observe | 0 | None | 7465 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10264 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.4 | 2 | 3 | 5 |
| ermaozi-get_subscribe | 0.575 | 23 | 17 | 40 |
| zhangkai | 0.6 | 12 | 8 | 20 |
| Surfboard-tg-mixed | 0.69 | 69 | 31 | 100 |
| Au1rxx-base64 | 0.787 | 203 | 55 | 258 |
| mheidari-all | 0.796 | 43 | 11 | 54 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23726 | yes | 3.77 | 0 |
| SoliSpirit-all | 10264 | yes | 2.33 | 0 |
| Epodonios-all | 7465 | yes | 2.61 | 0 |
| Surfboard-tg-mixed | 6977 | yes | 2.48 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.47 | 0 |
| barry-far-vless | 5763 | yes | 0.43 | 0 |
| Surfboard-tg-vless | 5462 | yes | 2.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 0.61 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 1.8 | 0 |
| DeltaKronecker-all | 4067 | yes | 2.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 50 |
| cn-block | 30 |
| speed | 24 |
| geo | 21 |
