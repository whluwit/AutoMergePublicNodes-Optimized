# AutoNodes 每日报告

生成时间：2026-10-08 04:22:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99282 |
| 去重后节点数 | 27674 |
| TCP 可达数 | 3000 |
| 真测通过数 | 240 |
| verified 输出数 | 240 |
| global 输出数 | 249 |
| all 输出数 | 27674 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 75.5 |
| geo | 1.5 |
| probe | 269.1 |
| real_test | 340.8 |
| tcp | 46.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 1 | 4 | 20.0% |
| http | 58 | 26 | 32 | 44.8% |
| hysteria2 | 23 | 22 | 1 | 95.7% |
| shadowsocks | 81 | 66 | 15 | 81.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 86 | 65 | 21 | 75.6% |
| vless | 295 | 57 | 238 | 19.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 149 |
| speed:TimeoutError | 45 |
| 204:ProxyError | 40 |
| geo:ClientOSError | 28 |
| speed:ClientOSError | 13 |
| 204:TimeoutError | 11 |
| cn-block:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6329 |
| ConnectionRefusedError | 1019 |
| gaierror | 477 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 39 | 0.974 | 1821 |
| Surfboard-tg-mixed | 0.679 | observe | 150 | 0.6 | 7193 |
| ermaozi-get_subscribe | 0.524 | observe | 28 | 0.5 | 592 |
| DeltaKronecker-all | 0.398 | observe | 20 | 0.3 | 5344 |
| ermaozi | 0.397 | observe | 36 | 0.361 | 715 |
| mheidari-all | 0.361 | observe | 276 | 0.279 | 23407 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7663 |

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
| mheidari-all | 0.279 | 77 | 199 | 276 |
| DeltaKronecker-all | 0.3 | 6 | 14 | 20 |
| ermaozi | 0.361 | 13 | 23 | 36 |
| ermaozi-get_subscribe | 0.5 | 14 | 14 | 28 |
| Surfboard-tg-mixed | 0.6 | 90 | 60 | 150 |
| Au1rxx-base64 | 0.974 | 38 | 1 | 39 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23407 | yes | 5.83 | 0 |
| SoliSpirit-all | 9572 | yes | 5.74 | 0 |
| Epodonios-all | 7663 | yes | 4.22 | 0 |
| Surfboard-tg-mixed | 7193 | yes | 4.57 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.75 | 0 |
| barry-far-vless | 5963 | yes | 1.36 | 0 |
| Surfboard-tg-vless | 5725 | yes | 4.0 | 0 |
| DeltaKronecker-all | 5344 | yes | 6.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 5138 | yes | 3.64 | 0 |
| mahdibland-V2RayAggregator | 4431 | yes | 1.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 178 |
| 204 | 58 |
| speed | 58 |
| cn-block | 18 |
