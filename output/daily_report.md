# AutoNodes 每日报告

生成时间：2026-06-12 00:03:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/11 |
| 清理建议：优先/观察 | 1/32 |
| 原始节点数 | 39955 |
| 去重后节点数 | 15027 |
| TCP 可达数 | 1500 |
| 真测通过数 | 389 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15027 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 2.8 |
| generate | 19.9 |
| geo | 1.2 |
| real_test | 156.0 |
| tcp | 37.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 5 | 1 | 4 | 20.0% |
| shadowsocks | 375 | 99 | 276 | 26.4% |
| shadowsocksr | 5 | 0 | 5 | 0.0% |
| socks | 32 | 24 | 8 | 75.0% |
| trojan | 178 | 45 | 133 | 25.3% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 844 | 172 | 672 | 20.4% |
| vmess | 16 | 6 | 10 | 37.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 392 |
| 204:ProxyError | 360 |
| 204:TimeoutError | 88 |
| speed:ClientOSError | 63 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 55 |
| speed:TimeoutError | 49 |
| geo:status | 36 |
| cn-block:TimeoutError | 14 |
| cn-block:ClientOSError | 12 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 5 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 5 |
| geo:status | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unsupported flow: xtls-rprx-vision-udp443 | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: i�s���G�k� | 2 |
| geo:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-tt47k4iu/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-o0akm4b2/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-cy0j5hpn/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �o | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1909 |
| ConnectionRefusedError | 427 |
| gaierror | 160 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | prefer | 43 | 0.977 | 52 |
| Au1rxx-base64 | 0.62 | observe | 71 | 0.62 | 88 |
| Surfboard-tg-mixed | 0.395 | observe | 731 | 0.315 | 4225 |
| mheidari-all | 0.335 | observe | 92 | 0.25 | 2000 |
| Epodonios-all | 0.287 | observe | 2 | 0.5 | 3000 |
| roosterkid-openproxylist-v2ray | 0.273 | observe | 28 | 0.25 | 150 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3224 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| DeltaKronecker-all | 0.198 | downweight | 321 | 0.115 | 4660 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| mfuu-v2ray | 0.063 | downweight | 17 | 0.0 | 0 | 387 |
| Barabama-we | 0.074 | downweight | 5 | 0.0 | 0 | 23 |
| 10ium-HighSpeed | 0.085 | downweight | 76 | 0.039 | 0 | 839 |
| moneyfly1-collectSub | 0.087 | downweight | 23 | 0.0 | 0 | 1164 |
| nscl5-all | 0.104 | downweight | 7 | 0.0 | 0 | 984 |
| abc-configs-readme-latest30 | 0.105 | observe | 2 | 0.0 | 0 | 24 |
| ermaozi | 0.105 | observe | 2 | 0.0 | 0 | 29 |
| xiaoji235-airport-v2ray-all | 0.109 | observe | 4 | 0.0 | 0 | 729 |
| SoliSpirit-all | 0.118 | downweight | 24 | 0.0 | 0 | 3000 |
| ninja-vless | 0.122 | downweight | 14 | 0.0 | 0 | 1791 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mfuu-v2ray | 0.063 | 17 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-we | 0.074 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-HighSpeed | 0.085 | 76 | 0.039 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.087 | 23 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.104 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.118 | 24 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.122 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.136 | 10 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-yudou | 0.137 | 21 | 0.095 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.148 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| abc-configs-readme-latest30 | 0.0 | 0 | 2 | 2 |
| ermaozi | 0.0 | 0 | 2 | 2 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 4 | 4 |
| Barabama-we | 0.0 | 0 | 5 | 5 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 6 | 6 |
| nscl5-all | 0.0 | 0 | 7 | 7 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 10 | 10 |
| ninja-vless | 0.0 | 0 | 14 | 14 |
| mfuu-v2ray | 0.0 | 0 | 17 | 17 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4660 | yes | 2.63 | 0 |
| mahdibland-V2RayAggregator | 4536 | yes | 1.29 | 0 |
| Surfboard-tg-mixed | 4225 | yes | 1.71 | 0 |
| Surfboard-tg-vless | 3224 | yes | 1.44 | 0 |
| Epodonios-all | 3000 | yes | 2.57 | 0 |
| SoliSpirit-all | 3000 | yes | 1.01 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 0.64 | 0 |
| mheidari-all | 2000 | yes | 2.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 0.85 | 0 |
| barry-far-vless | 2000 | yes | 0.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| shadowsocksr | 0.0 |
| tuic | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 840 |
| speed | 112 |
| sing-box exited 1 | 91 |
| geo | 42 |
| cn-block | 26 |
