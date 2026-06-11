# AutoNodes 每日报告

生成时间：2026-06-11 23:38:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/8 |
| 清理建议：优先/观察 | 1/35 |
| 原始节点数 | 39955 |
| 去重后节点数 | 15027 |
| TCP 可达数 | 1500 |
| 真测通过数 | 316 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15027 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.2 |
| generate | 24.8 |
| geo | 1.2 |
| real_test | 136.4 |
| tcp | 36.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 9 | 1 | 8 | 11.1% |
| shadowsocks | 228 | 60 | 168 | 26.3% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 32 | 20 | 12 | 62.5% |
| trojan | 455 | 78 | 377 | 17.1% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 707 | 108 | 599 | 15.3% |
| vmess | 16 | 7 | 9 | 43.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 557 |
| 204:ProxyError | 317 |
| geo:status | 114 |
| 204:TimeoutError | 62 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 52 |
| geo:status | 25 |
| cn-block:ClientOSError | 12 |
| cn-block:TimeoutError | 11 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| speed:ClientOSError | 6 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 3 |
| speed:TimeoutError | 3 |
| geo:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-ersjev1s/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-xju01anp/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-u54pd9j1/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �o | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ٭���7��v�� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: վ����N]k� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1905 |
| ConnectionRefusedError | 429 |
| gaierror | 163 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | prefer | 43 | 0.977 | 52 |
| Au1rxx-base64 | 0.551 | observe | 71 | 0.549 | 88 |
| roosterkid-openproxylist-v2ray | 0.329 | observe | 29 | 0.31 | 150 |
| Surfboard-tg-mixed | 0.286 | observe | 737 | 0.205 | 4225 |
| mheidari-all | 0.259 | observe | 93 | 0.172 | 2000 |
| Epodonios-all | 0.255 | observe | 0 | None | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3224 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| DeltaKronecker-all | 0.213 | downweight | 441 | 0.132 | 4660 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.09 | downweight | 8 | 0.0 | 0 | 729 |
| moneyfly1-collectSub | 0.111 | downweight | 7 | 0.0 | 0 | 1164 |
| nscl5-all | 0.113 | downweight | 5 | 0.0 | 0 | 984 |
| ninja-vless | 0.118 | downweight | 19 | 0.0 | 0 | 1791 |
| abc-configs-readme-latest30 | 0.128 | observe | 1 | 0.0 | 0 | 24 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| SoliSpirit-all | 0.128 | downweight | 16 | 0.0 | 0 | 3000 |
| ts-sf | 0.131 | observe | 1 | 0.0 | 0 | 88 |
| mahdibland-V2RayAggregator | 0.132 | downweight | 13 | 0.0 | 0 | 4536 |
| 10ium-ScrapeCategorize-Vless | 0.133 | downweight | 12 | 0.0 | 0 | 2000 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.09 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.111 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.113 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.118 | 19 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.128 | 16 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.133 | 12 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.213 | 441 | 0.132 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ts-sf | 0.0 | 0 | 1 | 1 |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 5 | 5 |
| moneyfly1-collectSub | 0.0 | 0 | 7 | 7 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 8 | 8 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 12 | 12 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 13 | 13 |
| SoliSpirit-all | 0.0 | 0 | 16 | 16 |
| ninja-vless | 0.0 | 0 | 19 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4660 | yes | 2.83 | 0 |
| mahdibland-V2RayAggregator | 4536 | yes | 0.58 | 0 |
| Surfboard-tg-mixed | 4225 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 3224 | yes | 1.64 | 0 |
| Epodonios-all | 3000 | yes | 2.89 | 0 |
| SoliSpirit-all | 3000 | yes | 0.98 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 0.78 | 0 |
| mheidari-all | 2000 | yes | 2.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 0.55 | 0 |
| barry-far-vless | 2000 | yes | 0.67 | 0 |

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
| 204 | 936 |
| geo | 141 |
| sing-box exited 1 | 74 |
| cn-block | 24 |
| speed | 9 |
