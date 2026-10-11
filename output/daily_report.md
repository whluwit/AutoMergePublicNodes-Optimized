# AutoNodes 每日报告

生成时间：2026-10-11 17:49:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 99914 |
| 去重后节点数 | 27587 |
| TCP 可达数 | 3000 |
| 真测通过数 | 426 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27587 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 78.8 |
| geo | 1.5 |
| probe | 295.3 |
| real_test | 346.0 |
| tcp | 47.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 2 | 6 | 25.0% |
| http | 18 | 9 | 9 | 50.0% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 114 | 100 | 14 | 87.7% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 167 | 142 | 25 | 85.0% |
| vless | 187 | 154 | 33 | 82.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 32 |
| cn-block:TimeoutError | 21 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 10 |
| speed:TimeoutError | 6 |
| cn-block:ProxyError | 2 |
| geo:TimeoutError | 2 |
| 204:ClientOSError | 2 |
| geo:ClientOSError | 2 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6493 |
| ConnectionRefusedError | 1040 |
| gaierror | 378 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | prefer | 378 | 0.905 | 1865 |
| mheidari-all | 0.843 | prefer | 57 | 0.772 | 23983 |
| DeltaKronecker-all | 0.602 | observe | 44 | 0.523 | 5372 |
| ermaozi | 0.493 | observe | 18 | 0.5 | 635 |
| Surfboard-tg-mixed | 0.372 | observe | 9 | 0.444 | 7223 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5099 |
| Epodonios-all | 0.255 | observe | 0 | None | 7642 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| downweight | ermaozi-get_subscribe | 0.203 | 8 | 0.25 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 2 | 6 | 8 |
| Surfboard-tg-mixed | 0.444 | 4 | 5 | 9 |
| ermaozi | 0.5 | 9 | 9 | 18 |
| DeltaKronecker-all | 0.523 | 23 | 21 | 44 |
| mheidari-all | 0.772 | 44 | 13 | 57 |
| Au1rxx-base64 | 0.905 | 342 | 36 | 378 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23983 | yes | 4.67 | 0 |
| SoliSpirit-all | 9946 | yes | 2.74 | 0 |
| Epodonios-all | 7642 | yes | 5.19 | 0 |
| Surfboard-tg-mixed | 7223 | yes | 3.36 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.79 | 0 |
| barry-far-vless | 5910 | yes | 1.01 | 0 |
| Surfboard-tg-vless | 5723 | yes | 4.12 | 0 |
| DeltaKronecker-all | 5372 | yes | 4.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 5099 | yes | 0.86 | 0 |
| mahdibland-V2RayAggregator | 4318 | yes | 2.25 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 46 |
| cn-block | 23 |
| speed | 17 |
| geo | 5 |
