# AutoNodes 每日报告

生成时间：2026-06-11 23:54:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/7 |
| 清理建议：优先/观察 | 1/36 |
| 原始节点数 | 39955 |
| 去重后节点数 | 15027 |
| TCP 可达数 | 1500 |
| 真测通过数 | 280 |
| verified 输出数 | 280 |
| global 输出数 | 284 |
| all 输出数 | 15027 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.0 |
| generate | 25.2 |
| geo | 1.2 |
| real_test | 136.9 |
| tcp | 35.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 8 | 1 | 7 | 12.5% |
| shadowsocks | 353 | 81 | 272 | 22.9% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 28 | 20 | 8 | 71.4% |
| trojan | 358 | 14 | 344 | 3.9% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 684 | 115 | 569 | 16.8% |
| vmess | 16 | 7 | 9 | 43.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 517 |
| 204:ProxyError | 359 |
| geo:status | 145 |
| 204:TimeoutError | 62 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 51 |
| geo:status | 32 |
| cn-block:ClientOSError | 11 |
| cn-block:TimeoutError | 9 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| speed:ClientOSError | 6 |
| speed:TimeoutError | 4 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-poh3xm1p/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-id3kpisk/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-w_amhs5o/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �o | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ٭���7��v�� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: վ����N]k� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1889 |
| ConnectionRefusedError | 426 |
| gaierror | 172 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | prefer | 43 | 0.977 | 52 |
| Au1rxx-base64 | 0.565 | observe | 71 | 0.563 | 88 |
| roosterkid-openproxylist-v2ray | 0.296 | observe | 29 | 0.276 | 150 |
| mheidari-all | 0.291 | observe | 93 | 0.204 | 2000 |
| Surfboard-tg-mixed | 0.29 | observe | 694 | 0.209 | 4225 |
| Epodonios-all | 0.255 | observe | 0 | None | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3224 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| Barabama-yudou | 0.214 | observe | 2 | 0.5 | 166 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.093 | downweight | 7 | 0.0 | 0 | 729 |
| moneyfly1-collectSub | 0.103 | downweight | 10 | 0.0 | 0 | 1164 |
| ninja-vless | 0.115 | downweight | 21 | 0.0 | 0 | 1791 |
| nscl5-all | 0.119 | observe | 4 | 0.0 | 0 | 984 |
| abc-configs-readme-latest30 | 0.128 | observe | 1 | 0.0 | 0 | 24 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.128 | downweight | 17 | 0.0 | 0 | 2000 |
| SoliSpirit-all | 0.129 | downweight | 15 | 0.0 | 0 | 3000 |
| mahdibland-V2RayAggregator | 0.132 | downweight | 13 | 0.0 | 0 | 4536 |
| DeltaKronecker-all | 0.134 | downweight | 479 | 0.052 | 0 | 4660 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.093 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.103 | 10 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.115 | 21 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.128 | 17 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.129 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.134 | 479 | 0.052 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 4 | 4 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 7 | 7 |
| moneyfly1-collectSub | 0.0 | 0 | 10 | 10 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 13 | 13 |
| SoliSpirit-all | 0.0 | 0 | 15 | 15 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 17 | 17 |
| ninja-vless | 0.0 | 0 | 21 | 21 |
| DeltaKronecker-all | 0.052 | 25 | 454 | 479 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4660 | yes | 2.77 | 0 |
| mahdibland-V2RayAggregator | 4536 | yes | 0.17 | 0 |
| Surfboard-tg-mixed | 4225 | yes | 1.8 | 0 |
| Surfboard-tg-vless | 3224 | yes | 1.59 | 0 |
| Epodonios-all | 3000 | yes | 3.08 | 0 |
| SoliSpirit-all | 3000 | yes | 1.83 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.43 | 0 |
| mheidari-all | 2000 | yes | 2.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.59 | 0 |
| barry-far-vless | 2000 | yes | 1.35 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| trojan | 0.039 |
| shadowsocksr | 0.0 |
| tuic | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 938 |
| geo | 177 |
| sing-box exited 1 | 74 |
| cn-block | 21 |
| speed | 10 |
