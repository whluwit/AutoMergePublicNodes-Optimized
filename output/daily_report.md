# AutoNodes 每日报告

生成时间：2026-10-18 15:28:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98081 |
| 去重后节点数 | 27683 |
| TCP 可达数 | 3000 |
| 真测通过数 | 381 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27683 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 90.7 |
| geo | 1.5 |
| probe | 277.3 |
| real_test | 249.1 |
| tcp | 48.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 33 | 23 | 10 | 69.7% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 138 | 111 | 27 | 80.4% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 41 | 24 | 17 | 58.5% |
| vless | 276 | 208 | 68 | 75.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 33 |
| 204:TimeoutError | 26 |
| 204:ProxyError | 13 |
| speed:ClientOSError | 12 |
| 204:ProxyConnectionError | 11 |
| geo:ClientOSError | 10 |
| speed:TimeoutError | 7 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6849 |
| ConnectionRefusedError | 1061 |
| gaierror | 397 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.879 | prefer | 356 | 0.812 | 1730 |
| mheidari-all | 0.822 | prefer | 29 | 0.759 | 23775 |
| ermaozi | 0.72 | prefer | 34 | 0.706 | 639 |
| Surfboard-tg-mixed | 0.634 | observe | 81 | 0.556 | 7095 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| Epodonios-all | 0.255 | observe | 0 | None | 7485 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10058 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5602 |

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
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| Surfboard-tg-mixed | 0.556 | 45 | 36 | 81 |
| ermaozi | 0.706 | 24 | 10 | 34 |
| mheidari-all | 0.759 | 22 | 7 | 29 |
| Au1rxx-base64 | 0.812 | 289 | 67 | 356 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23775 | yes | 6.2 | 0 |
| SoliSpirit-all | 10058 | yes | 3.83 | 0 |
| Epodonios-all | 7485 | yes | 6.83 | 0 |
| Surfboard-tg-mixed | 7095 | yes | 5.52 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.63 | 0 |
| barry-far-vless | 5815 | yes | 0.44 | 0 |
| Surfboard-tg-vless | 5602 | yes | 4.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 0.96 | 0 |
| DeltaKronecker-all | 4750 | yes | 5.81 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 0.79 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 53 |
| cn-block | 37 |
| speed | 19 |
| geo | 15 |
