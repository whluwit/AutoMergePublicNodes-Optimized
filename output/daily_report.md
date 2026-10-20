# AutoNodes 每日报告

生成时间：2026-10-20 11:02:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 94094 |
| 去重后节点数 | 26431 |
| TCP 可达数 | 3000 |
| 真测通过数 | 378 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26431 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 139.7 |
| geo | 1.4 |
| probe | 288.0 |
| real_test | 206.7 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 74 | 38 | 36 | 51.4% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 142 | 130 | 12 | 91.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 31 | 22 | 9 | 71.0% |
| vless | 249 | 176 | 73 | 70.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 38 |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 19 |
| speed:ClientOSError | 12 |
| speed:TimeoutError | 9 |
| geo:ClientOSError | 8 |
| 204:ProxyConnectionError | 6 |
| cn-block:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6380 |
| ConnectionRefusedError | 1031 |
| gaierror | 342 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | prefer | 54 | 0.87 | 23400 |
| zhangkai | 0.91 | prefer | 20 | 0.95 | 27 |
| Au1rxx-base64 | 0.86 | prefer | 292 | 0.815 | 1180 |
| Surfboard-tg-mixed | 0.705 | prefer | 86 | 0.628 | 6911 |
| ermaozi-get_subscribe | 0.378 | observe | 54 | 0.352 | 510 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| Epodonios-all | 0.255 | observe | 0 | None | 7377 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9888 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5515 |

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
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| ermaozi-get_subscribe | 0.352 | 19 | 35 | 54 |
| Surfboard-tg-mixed | 0.628 | 54 | 32 | 86 |
| Au1rxx-base64 | 0.815 | 238 | 54 | 292 |
| mheidari-all | 0.87 | 47 | 7 | 54 |
| zhangkai | 0.95 | 19 | 1 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23400 | yes | 6.7 | 0 |
| SoliSpirit-all | 9888 | yes | 4.85 | 0 |
| Epodonios-all | 7377 | yes | 4.89 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 3.52 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.52 | 0 |
| barry-far-vless | 5733 | yes | 2.83 | 0 |
| Surfboard-tg-vless | 5515 | yes | 4.63 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 4.26 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 3.18 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 4.39 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 69 |
| cn-block | 27 |
| speed | 23 |
| geo | 13 |
