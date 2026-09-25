# AutoNodes 每日报告

生成时间：2026-09-25 11:10:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 96962 |
| 去重后节点数 | 26300 |
| TCP 可达数 | 3000 |
| 真测通过数 | 365 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26300 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 146.6 |
| geo | 1.3 |
| probe | 266.8 |
| real_test | 158.9 |
| tcp | 43.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 46 | 32 | 14 | 69.6% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 162 | 148 | 14 | 91.4% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 24 | 7 | 17 | 29.2% |
| vless | 218 | 154 | 64 | 70.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 30 |
| cn-block:TimeoutError | 25 |
| 204:ProxyError | 23 |
| geo:ClientOSError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 6 |
| geo:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 4 |
| geo:ProxyError | 2 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5852 |
| ConnectionRefusedError | 953 |
| gaierror | 343 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | prefer | 232 | 0.871 | 1624 |
| mheidari-all | 0.82 | prefer | 75 | 0.747 | 22444 |
| ermaozi | 0.701 | prefer | 46 | 0.696 | 338 |
| Surfboard-tg-mixed | 0.7 | prefer | 106 | 0.623 | 7280 |
| DeltaKronecker-all | 0.407 | observe | 11 | 0.455 | 5452 |
| ninja-vless | 0.312 | observe | 4 | 0.5 | 1791 |
| ermaozi-get_subscribe | 0.269 | observe | 1 | 1.0 | 359 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7869 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.455 | 5 | 6 | 11 |
| ninja-vless | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.623 | 66 | 40 | 106 |
| ermaozi | 0.696 | 32 | 14 | 46 |
| mheidari-all | 0.747 | 56 | 19 | 75 |
| Au1rxx-base64 | 0.871 | 202 | 30 | 232 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22444 | yes | 3.12 | 0 |
| SoliSpirit-all | 9065 | yes | 2.39 | 0 |
| Epodonios-all | 7869 | yes | 1.63 | 0 |
| Surfboard-tg-mixed | 7280 | yes | 2.42 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.87 | 0 |
| barry-far-vless | 6140 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 5801 | yes | 1.87 | 0 |
| DeltaKronecker-all | 5452 | yes | 2.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 1.41 | 0 |
| mahdibland-V2RayAggregator | 4324 | yes | 1.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 59 |
| cn-block | 35 |
| geo | 14 |
| speed | 5 |
