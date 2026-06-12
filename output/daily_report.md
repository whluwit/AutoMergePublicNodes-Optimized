# AutoNodes 每日报告

生成时间：2026-06-12 00:12:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/7 |
| 清理建议：优先/观察 | 1/36 |
| 原始节点数 | 39955 |
| 去重后节点数 | 15028 |
| TCP 可达数 | 1500 |
| 真测通过数 | 420 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15028 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.1 |
| generate | 26.8 |
| geo | 1.2 |
| real_test | 161.5 |
| tcp | 35.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 7 | 1 | 6 | 14.3% |
| shadowsocks | 355 | 104 | 251 | 29.3% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 32 | 27 | 5 | 84.4% |
| trojan | 285 | 68 | 217 | 23.9% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 752 | 171 | 581 | 22.7% |
| vmess | 16 | 7 | 9 | 43.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 466 |
| 204:ProxyError | 334 |
| 204:TimeoutError | 77 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 55 |
| geo:status | 38 |
| speed:TimeoutError | 33 |
| speed:ClientOSError | 32 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 11 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-2m9bkwx2/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-69d3e3tv/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-hrp7tnh4/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: վ����N]k� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ٭���7��v�� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ߾��ε�g��� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: i�s���G�k� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1812 |
| ConnectionRefusedError | 430 |
| gaierror | 172 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | prefer | 43 | 0.977 | 52 |
| Au1rxx-base64 | 0.62 | observe | 71 | 0.62 | 88 |
| Surfboard-tg-mixed | 0.387 | observe | 763 | 0.307 | 4225 |
| mheidari-all | 0.357 | observe | 92 | 0.272 | 2000 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.316 | observe | 27 | 0.296 | 150 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3224 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| DeltaKronecker-all | 0.245 | downweight | 399 | 0.163 | 4660 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.081 | downweight | 13 | 0.0 | 0 | 729 |
| moneyfly1-collectSub | 0.09 | downweight | 21 | 0.0 | 0 | 1164 |
| ninja-vless | 0.117 | downweight | 20 | 0.0 | 0 | 1791 |
| nscl5-all | 0.119 | observe | 4 | 0.0 | 0 | 984 |
| 10ium-ScrapeCategorize-Vless | 0.127 | downweight | 18 | 0.0 | 0 | 2000 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| mahdibland-V2RayAggregator | 0.13 | downweight | 14 | 0.0 | 0 | 4536 |
| SoliSpirit-all | 0.138 | downweight | 9 | 0.0 | 0 | 3000 |
| 10ium-HighSpeed | 0.161 | observe | 1 | 0.0 | 0 | 839 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.081 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.09 | 21 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.117 | 20 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.127 | 18 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.13 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.138 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.245 | 399 | 0.163 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| Epodonios-all | 0.0 | 0 | 2 | 2 |
| nscl5-all | 0.0 | 0 | 4 | 4 |
| SoliSpirit-all | 0.0 | 0 | 9 | 9 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 13 | 13 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 14 | 14 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 18 | 18 |
| ninja-vless | 0.0 | 0 | 20 | 20 |
| moneyfly1-collectSub | 0.0 | 0 | 21 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4660 | yes | 2.87 | 0 |
| mahdibland-V2RayAggregator | 4536 | yes | 1.21 | 0 |
| Surfboard-tg-mixed | 4225 | yes | 1.63 | 0 |
| Surfboard-tg-vless | 3224 | yes | 1.73 | 0 |
| Epodonios-all | 3000 | yes | 2.85 | 0 |
| SoliSpirit-all | 3000 | yes | 1.18 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.24 | 0 |
| mheidari-all | 2000 | yes | 2.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 0.95 | 0 |
| barry-far-vless | 2000 | yes | 0.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| tuic | 0.0 |
| shadowsocksr | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 877 |
| sing-box exited 1 | 76 |
| speed | 65 |
| geo | 39 |
| cn-block | 23 |
