# AutoNodes 每日报告

生成时间：2026-09-18 03:09:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 84467 |
| 去重后节点数 | 23106 |
| TCP 可达数 | 3000 |
| 真测通过数 | 579 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23106 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 77.8 |
| geo | 1.5 |
| probe | 332.0 |
| real_test | 566.0 |
| tcp | 38.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 30 | 23 | 7 | 76.7% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 188 | 179 | 9 | 95.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 46 | 26 | 20 | 56.5% |
| vless | 770 | 329 | 441 | 42.7% |
| vmess | 3 | 1 | 2 | 33.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 212 |
| geo:ClientOSError | 82 |
| speed:ClientOSError | 74 |
| speed:TimeoutError | 57 |
| cn-block:TimeoutError | 13 |
| 204:TimeoutError | 12 |
| 204:ProxyError | 11 |
| cn-block:ClientOSError | 9 |
| 204:ProxyConnectionError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5451 |
| ConnectionRefusedError | 826 |
| gaierror | 317 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | prefer | 281 | 0.907 | 1648 |
| ermaozi | 0.801 | prefer | 26 | 0.808 | 378 |
| Surfboard-tg-mixed | 0.595 | observe | 132 | 0.515 | 7509 |
| mheidari-all | 0.517 | observe | 85 | 0.435 | 15863 |
| DeltaKronecker-all | 0.448 | observe | 525 | 0.368 | 5931 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4261 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| ermaozi-get_subscribe | 0.256 | observe | 4 | 0.5 | 402 |
| Epodonios-all | 0.255 | observe | 0 | None | 7966 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.368 | 193 | 332 | 525 |
| mheidari-all | 0.435 | 37 | 48 | 85 |
| ermaozi-get_subscribe | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.515 | 68 | 64 | 132 |
| ermaozi | 0.808 | 21 | 5 | 26 |
| Au1rxx-base64 | 0.907 | 255 | 26 | 281 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15863 | yes | 5.23 | 0 |
| SoliSpirit-all | 8922 | yes | 2.58 | 0 |
| Epodonios-all | 7966 | yes | 3.1 | 0 |
| Surfboard-tg-mixed | 7509 | yes | 3.72 | 0 |
| barry-far-vless | 6180 | yes | 1.34 | 0 |
| Surfboard-tg-vless | 5961 | yes | 3.47 | 0 |
| DeltaKronecker-all | 5931 | yes | 4.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 3.01 | 0 |
| mahdibland-V2RayAggregator | 4261 | yes | 1.49 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 295 |
| speed | 131 |
| 204 | 30 |
| cn-block | 24 |
