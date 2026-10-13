# AutoNodes 每日报告

生成时间：2026-10-13 00:25:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 100509 |
| 去重后节点数 | 27884 |
| TCP 可达数 | 3000 |
| 真测通过数 | 501 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27884 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 73.2 |
| geo | 1.5 |
| probe | 469.5 |
| real_test | 694.0 |
| tcp | 48.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 2 | 3 | 40.0% |
| http | 25 | 12 | 13 | 48.0% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 125 | 118 | 7 | 94.4% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 123 | 116 | 7 | 94.3% |
| vless | 642 | 228 | 414 | 35.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 200 |
| speed:TimeoutError | 109 |
| geo:ClientOSError | 45 |
| speed:ClientOSError | 37 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 15 |
| 204:TimeoutError | 9 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6706 |
| ConnectionRefusedError | 1054 |
| gaierror | 352 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.999 | prefer | 347 | 0.928 | 1844 |
| ermaozi | 0.527 | observe | 26 | 0.5 | 675 |
| Surfboard-tg-mixed | 0.421 | observe | 6 | 0.667 | 7208 |
| mheidari-all | 0.363 | observe | 546 | 0.282 | 23897 |
| DeltaKronecker-all | 0.344 | observe | 12 | 0.333 | 5701 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5028 |
| Epodonios-all | 0.255 | observe | 0 | None | 7736 |
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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.241 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.282 | 154 | 392 | 546 |
| DeltaKronecker-all | 0.333 | 4 | 8 | 12 |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| ermaozi | 0.5 | 13 | 13 | 26 |
| Surfboard-tg-mixed | 0.667 | 4 | 2 | 6 |
| Au1rxx-base64 | 0.928 | 322 | 25 | 347 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23897 | yes | 4.48 | 0 |
| SoliSpirit-all | 10128 | yes | 4.26 | 0 |
| Epodonios-all | 7736 | yes | 4.62 | 0 |
| Surfboard-tg-mixed | 7208 | yes | 3.97 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.76 | 0 |
| barry-far-vless | 6023 | yes | 2.34 | 0 |
| DeltaKronecker-all | 5701 | yes | 4.48 | 0 |
| Surfboard-tg-vless | 5678 | yes | 3.77 | 0 |
| 10ium-ScrapeCategorize-Vless | 5028 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 0.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 245 |
| speed | 147 |
| 204 | 28 |
| cn-block | 25 |
