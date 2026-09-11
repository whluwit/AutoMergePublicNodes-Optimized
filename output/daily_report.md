# AutoNodes 每日报告

生成时间：2026-09-11 20:30:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83905 |
| 去重后节点数 | 23383 |
| TCP 可达数 | 3000 |
| 真测通过数 | 391 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23383 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 72.6 |
| geo | 1.4 |
| probe | 191.7 |
| real_test | 210.8 |
| tcp | 40.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 28 | 14 | 14 | 50.0% |
| hysteria2 | 25 | 22 | 3 | 88.0% |
| shadowsocks | 154 | 136 | 18 | 88.3% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 35 | 29 | 6 | 82.9% |
| vless | 274 | 189 | 85 | 69.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 35 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 13 |
| cn-block:ClientOSError | 13 |
| speed:ClientOSError | 10 |
| speed:TimeoutError | 6 |
| 204:ProxyConnectionError | 4 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5561 |
| ConnectionRefusedError | 910 |
| gaierror | 534 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.902 | prefer | 267 | 0.839 | 1630 |
| DeltaKronecker-all | 0.811 | prefer | 24 | 0.75 | 6070 |
| mheidari-all | 0.798 | prefer | 76 | 0.724 | 15494 |
| Surfboard-tg-mixed | 0.73 | prefer | 121 | 0.653 | 7355 |
| ermaozi | 0.58 | observe | 21 | 0.571 | 377 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 194 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7830 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9022 |

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
| downweight | ermaozi-get_subscribe | 0.152 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.167 | 1 | 5 | 6 |
| ermaozi | 0.571 | 12 | 9 | 21 |
| Surfboard-tg-mixed | 0.653 | 79 | 42 | 121 |
| mheidari-all | 0.724 | 55 | 21 | 76 |
| DeltaKronecker-all | 0.75 | 18 | 6 | 24 |
| Au1rxx-base64 | 0.839 | 224 | 43 | 267 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15494 | yes | 5.3 | 0 |
| SoliSpirit-all | 9022 | yes | 4.1 | 0 |
| Epodonios-all | 7830 | yes | 3.48 | 0 |
| Surfboard-tg-mixed | 7355 | yes | 3.77 | 0 |
| barry-far-vless | 6209 | yes | 3.1 | 0 |
| DeltaKronecker-all | 6070 | yes | 4.92 | 0 |
| Surfboard-tg-vless | 5993 | yes | 4.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 2.89 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 3.15 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| geo | 37 |
| cn-block | 33 |
| speed | 16 |
