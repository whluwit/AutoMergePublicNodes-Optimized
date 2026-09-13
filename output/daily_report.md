# AutoNodes 每日报告

生成时间：2026-09-13 03:09:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 94344 |
| 去重后节点数 | 25317 |
| TCP 可达数 | 3000 |
| 真测通过数 | 628 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25317 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 82.8 |
| geo | 1.4 |
| probe | 473.5 |
| real_test | 678.0 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 30 | 18 | 12 | 60.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 178 | 171 | 7 | 96.1% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 23 | 10 | 13 | 43.5% |
| vless | 1021 | 400 | 621 | 39.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 228 |
| geo:ClientOSError | 106 |
| speed:TimeoutError | 99 |
| speed:ClientOSError | 97 |
| cn-block:ClientOSError | 52 |
| 204:TimeoutError | 34 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 18 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5889 |
| ConnectionRefusedError | 958 |
| gaierror | 412 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.947 | prefer | 384 | 0.885 | 1598 |
| Surfboard-tg-mixed | 0.937 | prefer | 61 | 0.869 | 7440 |
| ermaozi | 0.71 | prefer | 24 | 0.708 | 436 |
| DeltaKronecker-all | 0.385 | observe | 234 | 0.303 | 5970 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5301 |
| mheidari-all | 0.333 | observe | 570 | 0.253 | 20709 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 141 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7895 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.147 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| mheidari-all | 0.253 | 144 | 426 | 570 |
| DeltaKronecker-all | 0.303 | 71 | 163 | 234 |
| ermaozi | 0.708 | 17 | 7 | 24 |
| Surfboard-tg-mixed | 0.869 | 53 | 8 | 61 |
| Au1rxx-base64 | 0.885 | 340 | 44 | 384 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20709 | yes | 4.03 | 0 |
| SoliSpirit-all | 8734 | yes | 2.74 | 0 |
| Epodonios-all | 7895 | yes | 0.4 | 0 |
| Surfboard-tg-mixed | 7440 | yes | 2.82 | 0 |
| barry-far-vless | 6259 | yes | 1.86 | 0 |
| Surfboard-tg-vless | 6133 | yes | 4.34 | 0 |
| DeltaKronecker-all | 5970 | yes | 4.39 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 1.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 2.95 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 2.42 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 335 |
| speed | 196 |
| cn-block | 73 |
| 204 | 53 |
