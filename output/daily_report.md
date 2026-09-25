# AutoNodes 每日报告

生成时间：2026-09-25 16:31:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97423 |
| 去重后节点数 | 26456 |
| TCP 可达数 | 3000 |
| 真测通过数 | 369 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26456 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 75.2 |
| geo | 1.4 |
| probe | 257.3 |
| real_test | 175.4 |
| tcp | 43.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 22 | 11 | 11 | 50.0% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 153 | 131 | 22 | 85.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 4 | 4 | 0 | 100.0% |
| vless | 282 | 206 | 76 | 73.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 32 |
| 204:TimeoutError | 23 |
| 204:ProxyError | 17 |
| cn-block:TimeoutError | 17 |
| geo:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 1 |
| speed:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6252 |
| ConnectionRefusedError | 950 |
| gaierror | 338 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | prefer | 269 | 0.907 | 1699 |
| Surfboard-tg-mixed | 0.83 | prefer | 42 | 0.762 | 7258 |
| mheidari-all | 0.636 | observe | 140 | 0.557 | 22782 |
| ermaozi | 0.573 | observe | 18 | 0.611 | 304 |
| DeltaKronecker-all | 0.352 | observe | 6 | 0.5 | 5452 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 177 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7757 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9237 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.5 | 3 | 3 | 6 |
| mheidari-all | 0.557 | 78 | 62 | 140 |
| ermaozi | 0.611 | 11 | 7 | 18 |
| Surfboard-tg-mixed | 0.762 | 32 | 10 | 42 |
| Au1rxx-base64 | 0.907 | 244 | 25 | 269 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22782 | yes | 4.65 | 0 |
| SoliSpirit-all | 9237 | yes | 2.1 | 0 |
| Epodonios-all | 7757 | yes | 2.39 | 0 |
| Surfboard-tg-mixed | 7258 | yes | 3.46 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.51 | 0 |
| barry-far-vless | 6083 | yes | 1.01 | 0 |
| Surfboard-tg-vless | 5857 | yes | 3.66 | 0 |
| DeltaKronecker-all | 5452 | yes | 3.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 0.77 | 0 |
| mahdibland-V2RayAggregator | 4324 | yes | 1.88 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 52 |
| 204 | 45 |
| geo | 9 |
| speed | 7 |
