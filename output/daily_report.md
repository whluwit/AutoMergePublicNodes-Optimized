# AutoNodes 每日报告

生成时间：2026-09-19 20:06:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 91587 |
| 去重后节点数 | 25324 |
| TCP 可达数 | 3000 |
| 真测通过数 | 423 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25324 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 101.7 |
| geo | 1.4 |
| probe | 237.1 |
| real_test | 154.9 |
| tcp | 42.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 13 | 10 | 3 | 76.9% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 140 | 124 | 16 | 88.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 7 | 6 | 1 | 85.7% |
| vless | 388 | 266 | 122 | 68.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 38 |
| 204:TimeoutError | 25 |
| cn-block:ClientOSError | 22 |
| geo:TimeoutError | 18 |
| speed:ClientOSError | 12 |
| 204:ProxyError | 10 |
| cn-block:TimeoutError | 10 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5946 |
| ConnectionRefusedError | 904 |
| gaierror | 393 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.953 | prefer | 300 | 0.89 | 1650 |
| Surfboard-tg-mixed | 0.701 | prefer | 114 | 0.623 | 7303 |
| mheidari-all | 0.623 | observe | 125 | 0.544 | 19269 |
| ermaozi | 0.554 | observe | 11 | 0.818 | 250 |
| DeltaKronecker-all | 0.407 | observe | 11 | 0.455 | 6421 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5174 |
| Epodonios-all | 0.255 | observe | 0 | None | 7761 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.455 | 5 | 6 | 11 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.544 | 68 | 57 | 125 |
| Surfboard-tg-mixed | 0.623 | 71 | 43 | 114 |
| ermaozi | 0.818 | 9 | 2 | 11 |
| Au1rxx-base64 | 0.89 | 267 | 33 | 300 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19269 | yes | 3.89 | 0 |
| SoliSpirit-all | 9227 | yes | 4.62 | 0 |
| Epodonios-all | 7761 | yes | 4.63 | 0 |
| Surfboard-tg-mixed | 7303 | yes | 3.22 | 0 |
| DeltaKronecker-all | 6421 | yes | 4.96 | 0 |
| barry-far-vless | 6077 | yes | 1.61 | 0 |
| Surfboard-tg-vless | 5863 | yes | 3.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 1.8 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 2.3 | 0 |
| MatinGhanbari-all-sub | 3995 | yes | 2.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 58 |
| 204 | 37 |
| cn-block | 34 |
| speed | 14 |
