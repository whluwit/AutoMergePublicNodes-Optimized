# AutoNodes 每日报告

生成时间：2026-10-16 03:07:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99770 |
| 去重后节点数 | 27948 |
| TCP 可达数 | 3000 |
| 真测通过数 | 555 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27948 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| generate | 86.6 |
| geo | 1.5 |
| probe | 289.3 |
| real_test | 479.3 |
| tcp | 47.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 38 | 24 | 14 | 63.2% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 158 | 148 | 10 | 93.7% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 40 | 33 | 7 | 82.5% |
| vless | 637 | 329 | 308 | 51.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 94 |
| speed:TimeoutError | 74 |
| speed:ClientOSError | 67 |
| geo:ClientOSError | 40 |
| 204:ProxyError | 16 |
| 204:TimeoutError | 15 |
| cn-block:TimeoutError | 10 |
| 204:ClientOSError | 9 |
| cn-block:ClientOSError | 7 |
| geo:ProxyError | 4 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6569 |
| ConnectionRefusedError | 1068 |
| gaierror | 311 |
| OSError | 240 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.803 | prefer | 652 | 0.724 | 1992 |
| ermaozi | 0.653 | observe | 38 | 0.632 | 693 |
| Surfboard-tg-mixed | 0.446 | observe | 5 | 0.8 | 7135 |
| DeltaKronecker-all | 0.398 | observe | 20 | 0.3 | 5147 |
| mheidari-all | 0.354 | observe | 177 | 0.271 | 23985 |
| ermaozi-get_subscribe | 0.278 | observe | 1 | 1.0 | 574 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1992 |
| Epodonios-all | 0.255 | observe | 0 | None | 7647 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.271 | 48 | 129 | 177 |
| DeltaKronecker-all | 0.3 | 6 | 14 | 20 |
| ermaozi | 0.632 | 24 | 14 | 38 |
| Au1rxx-base64 | 0.724 | 472 | 180 | 652 |
| Surfboard-tg-mixed | 0.8 | 4 | 1 | 5 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23985 | yes | 6.59 | 0 |
| SoliSpirit-all | 9899 | yes | 6.24 | 0 |
| Epodonios-all | 7647 | yes | 6.82 | 0 |
| Surfboard-tg-mixed | 7135 | yes | 4.65 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.93 | 0 |
| barry-far-vless | 5878 | yes | 3.82 | 0 |
| Surfboard-tg-vless | 5628 | yes | 5.13 | 0 |
| DeltaKronecker-all | 5147 | yes | 7.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 3.36 | 0 |
| mahdibland-V2RayAggregator | 4235 | yes | 1.11 | 0 |

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
| speed | 141 |
| geo | 138 |
| 204 | 42 |
| cn-block | 19 |
