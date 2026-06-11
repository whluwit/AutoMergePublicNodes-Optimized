# AutoNodes 每日报告

生成时间：2026-06-11 16:09:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/11 |
| 清理建议：优先/观察 | 1/32 |
| 原始节点数 | 39877 |
| 去重后节点数 | 15187 |
| TCP 可达数 | 1500 |
| 真测通过数 | 259 |
| verified 输出数 | 259 |
| global 输出数 | 264 |
| all 输出数 | 15187 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.5 |
| generate | 26.3 |
| geo | 1.3 |
| real_test | 174.4 |
| tcp | 35.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 39 | 5 | 88.6% |
| hysteria2 | 6 | 1 | 5 | 16.7% |
| shadowsocks | 490 | 76 | 414 | 15.5% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 139 | 26 | 113 | 18.7% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 796 | 112 | 684 | 14.1% |
| vmess | 14 | 5 | 9 | 35.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 397 |
| 204:ClientOSError | 357 |
| 204:TimeoutError | 217 |
| geo:status | 68 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 55 |
| geo:status | 30 |
| geo:status | 29 |
| speed:ClientOSError | 17 |
| cn-block:TimeoutError | 14 |
| cn-block:ClientOSError | 10 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| speed:TimeoutError | 8 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 6 |
| geo:TimeoutError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o���mu����� | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-eqr9t55h/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-yjfbbemh/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-y4cokxk_/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1882 |
| ConnectionRefusedError | 421 |
| gaierror | 172 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.872 | prefer | 44 | 0.886 | 52 |
| Au1rxx-base64 | 0.45 | observe | 63 | 0.444 | 95 |
| roosterkid-openproxylist-v2ray | 0.338 | observe | 17 | 0.353 | 150 |
| mheidari-all | 0.302 | observe | 106 | 0.217 | 2000 |
| Epodonios-all | 0.255 | observe | 0 | None | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3273 |
| Surfboard-tg-mixed | 0.253 | observe | 750 | 0.172 | 4180 |
| barry-far-Sub1 | 0.226 | observe | 2 | 0.5 | 474 |
| Pawdroid | 0.208 | observe | 2 | 0.5 | 8 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| moneyfly1-collectSub | 0.054 | downweight | 139 | 0.0 | 0 | 1164 |
| Barabama-we | 0.074 | downweight | 5 | 0.0 | 0 | 23 |
| 10ium-HighSpeed | 0.083 | downweight | 15 | 0.0 | 0 | 839 |
| xiaoji235-airport-v2ray-all | 0.102 | downweight | 5 | 0.0 | 0 | 729 |
| nscl5-all | 0.104 | downweight | 7 | 0.0 | 0 | 984 |
| ermaozi | 0.105 | observe | 2 | 0.0 | 0 | 29 |
| ninja-vless | 0.112 | downweight | 23 | 0.0 | 0 | 1791 |
| SoliSpirit-all | 0.117 | downweight | 25 | 0.0 | 0 | 3000 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| mahdibland-V2RayAggregator | 0.129 | downweight | 15 | 0.0 | 0 | 4508 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | moneyfly1-collectSub | 0.054 | 139 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-we | 0.074 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-HighSpeed | 0.083 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.102 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.104 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.112 | 23 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.117 | 25 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.129 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.133 | 12 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | barry-far-vless | 0.186 | 12 | 0.083 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ts-sf | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.0 | 0 | 2 | 2 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 5 | 5 |
| Barabama-we | 0.0 | 0 | 5 | 5 |
| nscl5-all | 0.0 | 0 | 7 | 7 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 12 | 12 |
| 10ium-HighSpeed | 0.0 | 0 | 15 | 15 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 15 | 15 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4660 | yes | 3.14 | 0 |
| mahdibland-V2RayAggregator | 4508 | yes | 1.58 | 0 |
| Surfboard-tg-mixed | 4180 | yes | 1.97 | 0 |
| Surfboard-tg-vless | 3273 | yes | 1.51 | 0 |
| Epodonios-all | 3000 | yes | 2.91 | 0 |
| SoliSpirit-all | 3000 | yes | 1.6 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.37 | 0 |
| mheidari-all | 2000 | yes | 2.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.77 | 0 |
| barry-far-vless | 2000 | yes | 1.18 | 0 |

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
| 204 | 971 |
| geo | 133 |
| sing-box exited 1 | 86 |
| cn-block | 26 |
| speed | 25 |
