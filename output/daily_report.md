# AutoNodes 每日报告

生成时间：2026-10-06 12:48:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97830 |
| 去重后节点数 | 26948 |
| TCP 可达数 | 3000 |
| 真测通过数 | 479 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26948 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 86.7 |
| geo | 1.5 |
| probe | 224.3 |
| real_test | 183.4 |
| tcp | 45.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 74 | 31 | 43 | 41.9% |
| hysteria2 | 24 | 24 | 0 | 100.0% |
| shadowsocks | 160 | 150 | 10 | 93.8% |
| socks | 8 | 4 | 4 | 50.0% |
| trojan | 102 | 89 | 13 | 87.3% |
| vless | 231 | 179 | 52 | 77.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 42 |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 17 |
| geo:TimeoutError | 10 |
| speed:ClientOSError | 10 |
| geo:ClientOSError | 6 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 6 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6016 |
| ConnectionRefusedError | 1025 |
| gaierror | 471 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.995 | prefer | 45 | 0.933 | 23204 |
| Au1rxx-base64 | 0.991 | prefer | 320 | 0.922 | 1805 |
| Surfboard-tg-mixed | 0.804 | prefer | 132 | 0.727 | 7050 |
| DeltaKronecker-all | 0.538 | observe | 22 | 0.455 | 4889 |
| ermaozi | 0.453 | observe | 78 | 0.423 | 708 |
| ermaozi-get_subscribe | 0.335 | observe | 2 | 1.0 | 597 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7553 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.423 | 33 | 45 | 78 |
| DeltaKronecker-all | 0.455 | 10 | 12 | 22 |
| Surfboard-tg-mixed | 0.727 | 96 | 36 | 132 |
| Au1rxx-base64 | 0.922 | 295 | 25 | 320 |
| mheidari-all | 0.933 | 42 | 3 | 45 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23204 | yes | 7.2 | 0 |
| SoliSpirit-all | 9571 | yes | 2.92 | 0 |
| Epodonios-all | 7553 | yes | 3.74 | 0 |
| Surfboard-tg-mixed | 7050 | yes | 4.7 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.22 | 0 |
| barry-far-vless | 5839 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 5573 | yes | 4.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 1.05 | 0 |
| DeltaKronecker-all | 4889 | yes | 5.6 | 0 |
| mahdibland-V2RayAggregator | 4373 | yes | 3.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 62 |
| cn-block | 27 |
| geo | 17 |
| speed | 16 |
