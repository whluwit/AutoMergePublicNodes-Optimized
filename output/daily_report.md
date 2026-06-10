# AutoNodes 每日报告

生成时间：2026-06-10 15:46:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 43/44 |
| 清理建议：禁用/降权 | 0/10 |
| 清理建议：优先/观察 | 2/32 |
| 原始节点数 | 39788 |
| 去重后节点数 | 15169 |
| TCP 可达数 | 1500 |
| 真测通过数 | 317 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15169 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 2.8 |
| generate | 30.0 |
| geo | 1.3 |
| real_test | 159.3 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 66 | 64 | 2 | 97.0% |
| hysteria2 | 5 | 1 | 4 | 20.0% |
| shadowsocks | 381 | 80 | 301 | 21.0% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 183 | 27 | 156 | 14.8% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 840 | 142 | 698 | 16.9% |
| vmess | 12 | 3 | 9 | 25.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 450 |
| 204:ClientOSError | 417 |
| 204:TimeoutError | 98 |
| geo:status | 65 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 39 |
| geo:status | 27 |
| cn-block:TimeoutError | 14 |
| cn-block:ClientOSError | 13 |
| speed:ClientOSError | 11 |
| speed:TimeoutError | 10 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-1lak6qyd/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-mefxbpn7/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-mf8xz_ua/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o���mu����� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���s�F�������>�m�s� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �o | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1963 |
| ConnectionRefusedError | 424 |
| gaierror | 159 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.817 | prefer | 52 | 0.827 | 61 |
| zhangkai | 0.789 | prefer | 26 | 0.808 | 75 |
| Au1rxx-base64 | 0.489 | observe | 66 | 0.485 | 100 |
| roosterkid-openproxylist-v2ray | 0.315 | observe | 13 | 0.385 | 150 |
| mheidari-all | 0.293 | observe | 106 | 0.208 | 2000 |
| Surfboard-tg-mixed | 0.287 | observe | 786 | 0.206 | 4228 |
| Pawdroid | 0.255 | observe | 1 | 1.0 | 12 |
| Epodonios-all | 0.255 | observe | 0 | None | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3348 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| moneyfly1-collectSub | 0.064 | downweight | 56 | 0.0 | 0 | 1164 |
| Barabama-we | 0.069 | downweight | 6 | 0.0 | 0 | 23 |
| xiaoji235-airport-v2ray-all | 0.101 | downweight | 5 | 0.0 | 0 | 689 |
| ermaozi | 0.105 | observe | 2 | 0.0 | 0 | 29 |
| ts-sf | 0.108 | downweight | 12 | 0.083 | 0 | 63 |
| Barabama-yudou | 0.11 | observe | 2 | 0.0 | 0 | 166 |
| SoliSpirit-all | 0.116 | downweight | 26 | 0.0 | 0 | 3000 |
| 10ium-HighSpeed | 0.123 | observe | 3 | 0.0 | 0 | 839 |
| ninja-vless | 0.126 | downweight | 11 | 0.0 | 0 | 1791 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | moneyfly1-collectSub | 0.064 | 56 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-we | 0.069 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.101 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ts-sf | 0.108 | 12 | 0.083 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.116 | 26 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.126 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.129 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.13 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.162 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.183 | 288 | 0.101 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 2 | 2 |
| ermaozi | 0.0 | 0 | 2 | 2 |
| 10ium-HighSpeed | 0.0 | 0 | 3 | 3 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 5 | 5 |
| Barabama-we | 0.0 | 0 | 6 | 6 |
| ninja-vless | 0.0 | 0 | 11 | 11 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 14 | 14 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 15 | 15 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4616 | yes | 2.44 | 0 |
| mahdibland-V2RayAggregator | 4516 | yes | 1.32 | 0 |
| Surfboard-tg-mixed | 4228 | yes | 1.87 | 0 |
| Surfboard-tg-vless | 3348 | yes | 1.49 | 0 |
| Epodonios-all | 3000 | yes | 1.77 | 0 |
| SoliSpirit-all | 3000 | yes | 1.66 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.11 | 0 |
| mheidari-all | 2000 | yes | 3.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.05 | 0 |
| barry-far-vless | 2000 | yes | 0.73 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| shadowsocksr | 0.0 |
| tuic | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 965 |
| geo | 95 |
| sing-box exited 1 | 74 |
| cn-block | 28 |
| speed | 21 |
