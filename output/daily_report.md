# AutoNodes 每日报告

生成时间：2026-10-05 23:46:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98528 |
| 去重后节点数 | 27348 |
| TCP 可达数 | 3000 |
| 真测通过数 | 480 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27348 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 31.1 |
| geo | 1.5 |
| probe | 201.3 |
| real_test | 179.4 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 59 | 35 | 24 | 59.3% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 166 | 152 | 14 | 91.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 105 | 103 | 2 | 98.1% |
| vless | 209 | 166 | 43 | 79.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 28 |
| cn-block:TimeoutError | 21 |
| geo:ClientOSError | 9 |
| 204:TimeoutError | 8 |
| speed:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 4 |
| cn-block:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6711 |
| ConnectionRefusedError | 1060 |
| gaierror | 410 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | prefer | 69 | 0.942 | 7145 |
| Au1rxx-base64 | 0.965 | prefer | 318 | 0.893 | 1862 |
| mheidari-all | 0.891 | prefer | 109 | 0.817 | 23213 |
| ermaozi | 0.609 | observe | 60 | 0.583 | 701 |
| DeltaKronecker-all | 0.446 | observe | 5 | 0.8 | 5300 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5111 |
| Epodonios-all | 0.255 | observe | 0 | None | 7624 |
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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.583 | 35 | 25 | 60 |
| DeltaKronecker-all | 0.8 | 4 | 1 | 5 |
| mheidari-all | 0.817 | 89 | 20 | 109 |
| Au1rxx-base64 | 0.893 | 284 | 34 | 318 |
| Surfboard-tg-mixed | 0.942 | 65 | 4 | 69 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23213 | yes | 4.91 | 0 |
| SoliSpirit-all | 9352 | yes | 1.85 | 0 |
| Epodonios-all | 7624 | yes | 2.81 | 0 |
| Surfboard-tg-mixed | 7145 | yes | 3.3 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.57 | 0 |
| barry-far-vless | 5871 | yes | 1.05 | 0 |
| Surfboard-tg-vless | 5642 | yes | 3.03 | 0 |
| DeltaKronecker-all | 5300 | yes | 4.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 5111 | yes | 0.87 | 0 |
| mahdibland-V2RayAggregator | 4375 | yes | 2.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 36 |
| cn-block | 28 |
| geo | 13 |
| speed | 9 |
