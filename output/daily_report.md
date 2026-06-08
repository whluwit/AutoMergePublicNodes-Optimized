# AutoNodes 每日报告

生成时间：2026-06-08 15:59:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/12 |
| 清理建议：优先/观察 | 1/31 |
| 原始节点数 | 39237 |
| 去重后节点数 | 15304 |
| TCP 可达数 | 1500 |
| 真测通过数 | 273 |
| verified 输出数 | 273 |
| global 输出数 | 281 |
| all 输出数 | 15304 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 2.7 |
| generate | 24.9 |
| geo | 1.2 |
| real_test | 149.5 |
| tcp | 35.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 35 | 33 | 2 | 94.3% |
| hysteria2 | 10 | 1 | 9 | 10.0% |
| shadowsocks | 363 | 87 | 276 | 24.0% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 195 | 34 | 161 | 17.4% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 866 | 108 | 758 | 12.5% |
| vmess | 19 | 10 | 9 | 52.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 463 |
| 204:ClientOSError | 428 |
| 204:TimeoutError | 105 |
| geo:status | 62 |
| speed:TimeoutError | 48 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 41 |
| speed:ClientOSError | 16 |
| cn-block:TimeoutError | 11 |
| geo:status | 10 |
| cn-block:ClientOSError | 9 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: i�s���G�k� | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-vk37mqse/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-y7zzm9dx/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-y1c_i1dp/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ݽ5k����^�� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: chacha20-poly1305 | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: � | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1759 |
| ConnectionRefusedError | 421 |
| gaierror | 189 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.747 | prefer | 45 | 0.756 | 62 |
| roosterkid-openproxylist-v2ray | 0.614 | observe | 18 | 0.667 | 150 |
| Au1rxx-base64 | 0.462 | observe | 81 | 0.457 | 93 |
| mheidari-all | 0.347 | observe | 99 | 0.263 | 2000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3067 |
| Surfboard-tg-mixed | 0.244 | downweight | 771 | 0.163 | 3888 |
| chromego_merge | 0.21 | observe | 2 | 0.5 | 55 |
| 10ium-HighSpeed | 0.209 | observe | 0 | None | 839 |
| Epodonios-all | 0.207 | observe | 1 | 0.0 | 3000 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ts-sf | 0.053 | downweight | 14 | 0.0 | 0 | 68 |
| Barabama-we | 0.065 | downweight | 7 | 0.0 | 0 | 23 |
| xiaoji235-airport-v2ray-all | 0.084 | downweight | 8 | 0.0 | 0 | 584 |
| moneyfly1-collectSub | 0.088 | downweight | 22 | 0.0 | 0 | 1164 |
| Barabama-yudou | 0.098 | downweight | 20 | 0.05 | 0 | 166 |
| nscl5-all | 0.102 | downweight | 7 | 0.0 | 0 | 957 |
| ninja-vless | 0.119 | downweight | 17 | 0.0 | 0 | 1791 |
| SoliSpirit-all | 0.123 | downweight | 21 | 0.0 | 0 | 3000 |
| Pawdroid | 0.128 | observe | 1 | 0.0 | 0 | 12 |
| abc-configs-readme-latest30 | 0.128 | observe | 1 | 0.0 | 0 | 10 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ts-sf | 0.053 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-we | 0.065 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.084 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.088 | 22 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-yudou | 0.098 | 20 | 0.05 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.102 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.119 | 17 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.123 | 21 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.13 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.134 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| barry-far-vless | 0.0 | 0 | 1 | 1 |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| Epodonios-all | 0.0 | 0 | 1 | 1 |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| barry-far-Sub2 | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 7 | 7 |
| Barabama-we | 0.0 | 0 | 7 | 7 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 8 | 8 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 11 | 11 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4760 | yes | 2.46 | 0 |
| mahdibland-V2RayAggregator | 4533 | yes | 1.19 | 0 |
| Surfboard-tg-mixed | 3888 | yes | 1.35 | 0 |
| Surfboard-tg-vless | 3067 | yes | 1.46 | 0 |
| Epodonios-all | 3000 | yes | 2.17 | 0 |
| SoliSpirit-all | 3000 | yes | 1.54 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.14 | 0 |
| mheidari-all | 2000 | yes | 2.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.34 | 0 |
| barry-far-vless | 2000 | yes | 0.58 | 0 |

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
| 204 | 996 |
| sing-box exited 1 | 74 |
| geo | 73 |
| speed | 64 |
| cn-block | 20 |
