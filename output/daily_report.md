# AutoNodes 每日报告

生成时间：2026-06-13 04:00:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/10 |
| 清理建议：优先/观察 | 1/33 |
| 原始节点数 | 39767 |
| 去重后节点数 | 15266 |
| TCP 可达数 | 1500 |
| 真测通过数 | 377 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15266 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.2 |
| generate | 25.6 |
| geo | 1.2 |
| real_test | 150.3 |
| tcp | 35.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 13 | 1 | 12 | 7.7% |
| shadowsocks | 367 | 88 | 279 | 24.0% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 272 | 51 | 221 | 18.8% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 775 | 185 | 590 | 23.9% |
| vmess | 15 | 6 | 9 | 40.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 464 |
| 204:ProxyError | 362 |
| geo:status | 64 |
| 204:TimeoutError | 62 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 60 |
| speed:TimeoutError | 41 |
| speed:ClientOSError | 17 |
| cn-block:ClientOSError | 11 |
| cn-block:TimeoutError | 9 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| geo:status | 7 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o���mu����� | 2 |
| geo:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-r04y17vc/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-x3js90ya/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-j31hj3mn/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �o | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ߾��ε�g��� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: chacha20-poly1305 | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1793 |
| ConnectionRefusedError | 454 |
| gaierror | 190 |
| OSError | 33 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.919 | prefer | 46 | 0.935 | 52 |
| Au1rxx-base64 | 0.488 | observe | 91 | 0.484 | 113 |
| roosterkid-openproxylist-v2ray | 0.413 | observe | 25 | 0.4 | 150 |
| Surfboard-tg-mixed | 0.374 | observe | 681 | 0.294 | 4106 |
| mheidari-all | 0.301 | observe | 93 | 0.215 | 2000 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3044 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| DeltaKronecker-all | 0.217 | downweight | 370 | 0.135 | 4706 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| mfuu-v2ray | 0.072 | downweight | 8 | 0.0 | 0 | 279 |
| moneyfly1-collectSub | 0.088 | downweight | 22 | 0.0 | 0 | 1164 |
| ninja-vless | 0.115 | downweight | 21 | 0.0 | 0 | 1791 |
| xiaoji235-airport-v2ray-all | 0.121 | downweight | 18 | 0.056 | 0 | 675 |
| SoliSpirit-all | 0.127 | downweight | 18 | 0.0 | 0 | 3000 |
| abc-configs-readme-latest30 | 0.128 | observe | 1 | 0.0 | 0 | 15 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.128 | downweight | 16 | 0.0 | 0 | 2000 |
| mahdibland-V2RayAggregator | 0.133 | downweight | 12 | 0.0 | 0 | 4561 |
| nscl5-all | 0.162 | downweight | 9 | 0.111 | 0 | 1119 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mfuu-v2ray | 0.072 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.088 | 22 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.115 | 21 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.121 | 18 | 0.056 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.127 | 18 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.128 | 16 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.133 | 12 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.162 | 9 | 0.111 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Epodonios-all | 0.196 | 67 | 0.104 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.217 | 370 | 0.135 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| mfuu-v2ray | 0.0 | 0 | 8 | 8 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 12 | 12 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 16 | 16 |
| SoliSpirit-all | 0.0 | 0 | 18 | 18 |
| ninja-vless | 0.0 | 0 | 21 | 21 |
| moneyfly1-collectSub | 0.0 | 0 | 22 | 22 |
| xiaoji235-airport-v2ray-all | 0.056 | 1 | 17 | 18 |
| Epodonios-all | 0.104 | 7 | 60 | 67 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4706 | yes | 3.3 | 0 |
| mahdibland-V2RayAggregator | 4561 | yes | 0.17 | 0 |
| Surfboard-tg-mixed | 4106 | yes | 2.13 | 0 |
| Surfboard-tg-vless | 3044 | yes | 1.33 | 0 |
| Epodonios-all | 3000 | yes | 2.01 | 0 |
| SoliSpirit-all | 3000 | yes | 2.07 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.83 | 0 |
| mheidari-all | 2000 | yes | 1.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.77 | 0 |
| barry-far-vless | 2000 | yes | 1.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| hysteria2 | 0.077 |
| shadowsocksr | 0.0 |
| tuic | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 888 |
| sing-box exited 1 | 84 |
| geo | 73 |
| speed | 58 |
| cn-block | 20 |
