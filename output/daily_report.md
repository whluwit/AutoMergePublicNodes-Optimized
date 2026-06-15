# AutoNodes 每日报告

生成时间：2026-06-15 12:23:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/10 |
| 清理建议：优先/观察 | 1/33 |
| 原始节点数 | 40895 |
| 去重后节点数 | 15968 |
| TCP 可达数 | 1500 |
| 真测通过数 | 274 |
| verified 输出数 | 274 |
| global 输出数 | 299 |
| all 输出数 | 15968 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.0 |
| generate | 42.1 |
| geo | 1.3 |
| real_test | 225.0 |
| tcp | 39.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 15 | 2 | 13 | 13.3% |
| shadowsocks | 222 | 53 | 169 | 23.9% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 338 | 52 | 286 | 15.4% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 855 | 119 | 736 | 13.9% |
| vmess | 15 | 5 | 10 | 33.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 479 |
| 204:ProxyError | 358 |
| 204:TimeoutError | 120 |
| geo:status | 66 |
| geo:status | 51 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 42 |
| cn-block:TimeoutError | 35 |
| speed:ClientOSError | 16 |
| cn-block:ClientOSError | 11 |
| speed:TimeoutError | 9 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| geo:TimeoutError | 8 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: chacha20-poly1305 | 5 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 3 |
| geo:ClientOSError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-1bdox3x2/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-915gy8re/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-kj4k93t2/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: վ����N]k� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1994 |
| ConnectionRefusedError | 443 |
| gaierror | 155 |
| OSError | 26 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.919 | prefer | 46 | 0.935 | 52 |
| roosterkid-openproxylist-v2ray | 0.592 | observe | 27 | 0.593 | 150 |
| Au1rxx-base64 | 0.575 | observe | 68 | 0.574 | 99 |
| Epodonios-all | 0.265 | observe | 63 | 0.175 | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3447 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| mheidari-all | 0.24 | downweight | 98 | 0.153 | 2000 |
| Surfboard-tg-mixed | 0.233 | downweight | 794 | 0.152 | 4474 |
| barry-far-Sub2 | 0.195 | observe | 0 | None | 489 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.075 | downweight | 18 | 0.0 | 0 | 703 |
| moneyfly1-collectSub | 0.081 | downweight | 27 | 0.0 | 0 | 1164 |
| Barabama-yudou | 0.094 | downweight | 21 | 0.048 | 0 | 166 |
| ninja-vless | 0.113 | downweight | 22 | 0.0 | 0 | 1791 |
| abc-configs-readme-latest30 | 0.128 | observe | 1 | 0.0 | 0 | 16 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| nscl5-all | 0.13 | observe | 3 | 0.0 | 0 | 1019 |
| mahdibland-V2RayAggregator | 0.13 | downweight | 14 | 0.0 | 0 | 4500 |
| SoliSpirit-all | 0.138 | downweight | 9 | 0.0 | 0 | 3000 |
| 10ium-ScrapeCategorize-Vless | 0.153 | downweight | 5 | 0.0 | 0 | 2000 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.075 | 18 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.081 | 27 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-yudou | 0.094 | 21 | 0.048 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.113 | 22 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.13 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.138 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.182 | 282 | 0.099 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Surfboard-tg-mixed | 0.233 | 794 | 0.152 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mheidari-all | 0.24 | 98 | 0.153 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 5 | 5 |
| SoliSpirit-all | 0.0 | 0 | 9 | 9 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 14 | 14 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 18 | 18 |
| ninja-vless | 0.0 | 0 | 22 | 22 |
| moneyfly1-collectSub | 0.0 | 0 | 27 | 27 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 5458 | yes | 3.11 | 0 |
| mahdibland-V2RayAggregator | 4500 | yes | 1.54 | 0 |
| Surfboard-tg-mixed | 4474 | yes | 1.9 | 0 |
| Surfboard-tg-vless | 3447 | yes | 1.67 | 0 |
| Epodonios-all | 3000 | yes | 2.43 | 0 |
| SoliSpirit-all | 3000 | yes | 1.43 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.01 | 0 |
| mheidari-all | 2000 | yes | 2.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 0.94 | 0 |
| barry-far-vless | 2000 | yes | 0.79 | 0 |

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
| 204 | 957 |
| geo | 128 |
| sing-box exited 1 | 69 |
| cn-block | 46 |
| speed | 26 |
