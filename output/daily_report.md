# AutoNodes 每日报告

生成时间：2026-06-09 03:43:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/9 |
| 清理建议：优先/观察 | 0/35 |
| 原始节点数 | 39687 |
| 去重后节点数 | 15301 |
| TCP 可达数 | 1500 |
| 真测通过数 | 374 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15301 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.0 |
| generate | 26.7 |
| geo | 1.3 |
| real_test | 150.5 |
| tcp | 33.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 35 | 29 | 6 | 82.9% |
| hysteria2 | 15 | 3 | 12 | 20.0% |
| shadowsocks | 340 | 106 | 234 | 31.2% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 157 | 38 | 119 | 24.2% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 923 | 187 | 736 | 20.3% |
| vmess | 18 | 9 | 9 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 447 |
| 204:ClientOSError | 401 |
| 204:TimeoutError | 78 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 50 |
| speed:TimeoutError | 48 |
| geo:status | 29 |
| speed:ClientOSError | 24 |
| geo:status | 18 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| cn-block:ClientOSError | 6 |
| cn-block:TimeoutError | 5 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unsupported flow: xtls-rprx-vision-udp443 | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-0ro6xpzm/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-t375jnw8/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-fz1vkt3z/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: of�o���� | ��7���]>kO | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o���mu����� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ݽ5k����^�� | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1547 |
| ConnectionRefusedError | 435 |
| gaierror | 217 |
| OSError | 35 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.676 | observe | 44 | 0.682 | 62 |
| Au1rxx-base64 | 0.515 | observe | 88 | 0.511 | 106 |
| roosterkid-openproxylist-v2ray | 0.441 | observe | 21 | 0.429 | 150 |
| mheidari-all | 0.364 | observe | 93 | 0.28 | 2000 |
| Surfboard-tg-mixed | 0.351 | observe | 827 | 0.271 | 4056 |
| Epodonios-all | 0.255 | observe | 0 | None | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3189 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| DeltaKronecker-all | 0.201 | downweight | 303 | 0.119 | 4760 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| moneyfly1-collectSub | 0.093 | downweight | 18 | 0.0 | 0 | 1164 |
| 10ium-ScrapeCategorize-Vless | 0.109 | downweight | 33 | 0.0 | 0 | 2000 |
| 10ium-HighSpeed | 0.114 | observe | 4 | 0.0 | 0 | 839 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| ts-sf | 0.13 | observe | 1 | 0.0 | 0 | 52 |
| mahdibland-V2RayAggregator | 0.13 | downweight | 14 | 0.0 | 0 | 4521 |
| ninja-vless | 0.133 | downweight | 8 | 0.0 | 0 | 1791 |
| xiaoji235-airport-v2ray-all | 0.133 | downweight | 12 | 0.083 | 0 | 678 |
| Barabama-yudou | 0.137 | downweight | 21 | 0.095 | 0 | 166 |
| SoliSpirit-all | 0.144 | downweight | 7 | 0.0 | 0 | 3000 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | moneyfly1-collectSub | 0.093 | 18 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.109 | 33 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.13 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.133 | 12 | 0.083 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.133 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-yudou | 0.137 | 21 | 0.095 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.144 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.187 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.201 | 303 | 0.119 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| ts-sf | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 4 | 4 |
| SoliSpirit-all | 0.0 | 0 | 7 | 7 |
| ninja-vless | 0.0 | 0 | 8 | 8 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 14 | 14 |
| moneyfly1-collectSub | 0.0 | 0 | 18 | 18 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 33 | 33 |
| xiaoji235-airport-v2ray-all | 0.083 | 1 | 11 | 12 |
| Barabama-yudou | 0.095 | 2 | 19 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4760 | yes | 2.88 | 0 |
| mahdibland-V2RayAggregator | 4521 | yes | 1.33 | 0 |
| Surfboard-tg-mixed | 4056 | yes | 1.75 | 0 |
| Surfboard-tg-vless | 3189 | yes | 1.52 | 0 |
| Epodonios-all | 3000 | yes | 2.67 | 0 |
| SoliSpirit-all | 3000 | yes | 2.52 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.69 | 0 |
| mheidari-all | 2000 | yes | 2.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.57 | 0 |
| barry-far-vless | 2000 | yes | 0.88 | 0 |

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
| 204 | 926 |
| speed | 72 |
| sing-box exited 1 | 69 |
| geo | 47 |
| cn-block | 12 |
