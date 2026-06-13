# AutoNodes 每日报告

生成时间：2026-06-13 14:06:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/13 |
| 清理建议：优先/观察 | 1/30 |
| 原始节点数 | 40079 |
| 去重后节点数 | 15400 |
| TCP 可达数 | 1500 |
| 真测通过数 | 217 |
| verified 输出数 | 217 |
| global 输出数 | 231 |
| all 输出数 | 15400 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.1 |
| generate | 25.7 |
| geo | 1.3 |
| real_test | 152.1 |
| tcp | 36.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 6 | 1 | 5 | 16.7% |
| shadowsocks | 380 | 62 | 318 | 16.3% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 14 | 9 | 5 | 64.3% |
| trojan | 236 | 10 | 226 | 4.2% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 794 | 86 | 708 | 10.8% |
| vmess | 17 | 7 | 10 | 41.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 445 |
| 204:ProxyError | 396 |
| 204:TimeoutError | 107 |
| geo:status | 71 |
| geo:status | 65 |
| geo:status | 59 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 54 |
| cn-block:TimeoutError | 18 |
| cn-block:ClientOSError | 11 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| speed:TimeoutError | 8 |
| geo:TimeoutError | 4 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unsupported flow: xtls-rprx-vision-udp443 | 4 |
| speed:ClientOSError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o���mu����� | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 2 |
| cn-block:ProxyError | 2 |
| geo:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: i�s���G�k� | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1876 |
| ConnectionRefusedError | 447 |
| gaierror | 178 |
| OSError | 32 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.919 | prefer | 46 | 0.935 | 52 |
| Au1rxx-base64 | 0.49 | observe | 72 | 0.486 | 98 |
| roosterkid-openproxylist-v2ray | 0.446 | observe | 23 | 0.435 | 150 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3128 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| Epodonios-all | 0.24 | observe | 4 | 0.25 | 3000 |
| abc-configs-readme-latest30 | 0.208 | observe | 2 | 0.5 | 16 |
| Surfboard-tg-mixed | 0.204 | downweight | 723 | 0.123 | 4139 |
| barry-far-Sub2 | 0.195 | observe | 0 | None | 494 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| 10ium-HighSpeed | 0.047 | downweight | 72 | 0.0 | 0 | 839 |
| Barabama-we | 0.069 | downweight | 6 | 0.0 | 0 | 23 |
| moneyfly1-collectSub | 0.072 | downweight | 37 | 0.0 | 0 | 1164 |
| xiaoji235-airport-v2ray-all | 0.083 | downweight | 10 | 0.0 | 0 | 675 |
| ts-sf | 0.104 | downweight | 14 | 0.071 | 0 | 79 |
| ermaozi | 0.105 | observe | 2 | 0.0 | 0 | 29 |
| ninja-vless | 0.12 | downweight | 16 | 0.0 | 0 | 1791 |
| SoliSpirit-all | 0.12 | downweight | 23 | 0.0 | 0 | 3000 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| mahdibland-V2RayAggregator | 0.13 | downweight | 14 | 0.0 | 0 | 4566 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-HighSpeed | 0.047 | 72 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-we | 0.069 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.072 | 37 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.083 | 10 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ts-sf | 0.104 | 14 | 0.071 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.12 | 23 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.12 | 16 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.13 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.138 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.162 | 9 | 0.111 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.0 | 0 | 2 | 2 |
| Barabama-we | 0.0 | 0 | 6 | 6 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 9 | 9 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 10 | 10 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 14 | 14 |
| ninja-vless | 0.0 | 0 | 16 | 16 |
| SoliSpirit-all | 0.0 | 0 | 23 | 23 |
| moneyfly1-collectSub | 0.0 | 0 | 37 | 37 |
| 10ium-HighSpeed | 0.0 | 0 | 72 | 72 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4955 | yes | 2.99 | 0 |
| mahdibland-V2RayAggregator | 4566 | yes | 1.48 | 0 |
| Surfboard-tg-mixed | 4139 | yes | 2.07 | 0 |
| Surfboard-tg-vless | 3128 | yes | 2.31 | 0 |
| Epodonios-all | 3000 | yes | 1.96 | 0 |
| SoliSpirit-all | 3000 | yes | 1.52 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.35 | 0 |
| mheidari-all | 2000 | yes | 2.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 0.72 | 0 |
| barry-far-vless | 2000 | yes | 1.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| trojan | 0.042 |
| shadowsocksr | 0.0 |
| tuic | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 948 |
| geo | 202 |
| sing-box exited 1 | 91 |
| cn-block | 31 |
| speed | 11 |
