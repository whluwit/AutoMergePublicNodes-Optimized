# AutoNodes 每日报告

生成时间：2026-06-11 23:58:45

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
| 真测通过数 | 316 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15027 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.0 |
| generate | 26.3 |
| geo | 1.2 |
| real_test | 144.0 |
| tcp | 34.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 7 | 1 | 6 | 14.3% |
| shadowsocks | 349 | 78 | 271 | 22.3% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 28 | 20 | 8 | 71.4% |
| trojan | 299 | 60 | 239 | 20.1% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 748 | 108 | 640 | 14.4% |
| vmess | 16 | 7 | 9 | 43.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 492 |
| 204:ProxyError | 378 |
| geo:status | 86 |
| 204:TimeoutError | 85 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 52 |
| geo:status | 37 |
| cn-block:ClientOSError | 10 |
| cn-block:TimeoutError | 9 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| speed:ClientOSError | 6 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 3 |
| speed:TimeoutError | 3 |
| geo:TimeoutError | 3 |
| geo:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-devq_q95/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-zocpq3ne/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-rajjgwzi/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: վ����N]k� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ٭���7��v�� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: վ����N]k� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1766 |
| ConnectionRefusedError | 430 |
| gaierror | 183 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | prefer | 43 | 0.977 | 52 |
| Au1rxx-base64 | 0.524 | observe | 71 | 0.521 | 88 |
| mheidari-all | 0.303 | observe | 92 | 0.217 | 2000 |
| roosterkid-openproxylist-v2ray | 0.296 | observe | 29 | 0.276 | 150 |
| Surfboard-tg-mixed | 0.28 | observe | 752 | 0.199 | 4225 |
| Epodonios-all | 0.255 | observe | 0 | None | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3224 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| DeltaKronecker-all | 0.218 | downweight | 426 | 0.136 | 4660 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.097 | downweight | 6 | 0.0 | 0 | 729 |
| nscl5-all | 0.113 | downweight | 5 | 0.0 | 0 | 984 |
| ninja-vless | 0.113 | downweight | 22 | 0.0 | 0 | 1791 |
| moneyfly1-collectSub | 0.127 | observe | 4 | 0.0 | 0 | 1164 |
| 10ium-ScrapeCategorize-Vless | 0.127 | downweight | 18 | 0.0 | 0 | 2000 |
| Barabama-we | 0.128 | observe | 1 | 0.0 | 0 | 23 |
| abc-configs-readme-latest30 | 0.128 | observe | 1 | 0.0 | 0 | 24 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| SoliSpirit-all | 0.132 | downweight | 13 | 0.0 | 0 | 3000 |
| mahdibland-V2RayAggregator | 0.132 | downweight | 13 | 0.0 | 0 | 4536 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.097 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.113 | 22 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.113 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.127 | 18 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.218 | 426 | 0.136 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| Barabama-we | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| moneyfly1-collectSub | 0.0 | 0 | 4 | 4 |
| nscl5-all | 0.0 | 0 | 5 | 5 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 6 | 6 |
| SoliSpirit-all | 0.0 | 0 | 13 | 13 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 13 | 13 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 18 | 18 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4660 | yes | 3.2 | 0 |
| mahdibland-V2RayAggregator | 4536 | yes | 1.53 | 0 |
| Surfboard-tg-mixed | 4225 | yes | 1.94 | 0 |
| Surfboard-tg-vless | 3224 | yes | 1.1 | 0 |
| Epodonios-all | 3000 | yes | 2.87 | 0 |
| SoliSpirit-all | 3000 | yes | 1.85 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.63 | 0 |
| mheidari-all | 2000 | yes | 2.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.56 | 0 |
| barry-far-vless | 2000 | yes | 1.19 | 0 |

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
| 204 | 955 |
| geo | 128 |
| sing-box exited 1 | 73 |
| cn-block | 19 |
| speed | 9 |
