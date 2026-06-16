# AutoNodes 每日报告

生成时间：2026-06-16 04:25:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/10 |
| 清理建议：优先/观察 | 1/33 |
| 原始节点数 | 42116 |
| 去重后节点数 | 16921 |
| TCP 可达数 | 1500 |
| 真测通过数 | 393 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 16921 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.0 |
| generate | 22.3 |
| geo | 1.2 |
| real_test | 161.2 |
| tcp | 40.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 15 | 2 | 13 | 13.3% |
| shadowsocks | 235 | 65 | 170 | 27.7% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 362 | 74 | 288 | 20.4% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 816 | 205 | 611 | 25.1% |
| vmess | 14 | 3 | 11 | 21.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 490 |
| 204:ProxyError | 311 |
| 204:TimeoutError | 79 |
| geo:status | 57 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 56 |
| speed:ClientOSError | 27 |
| speed:TimeoutError | 24 |
| cn-block:ClientOSError | 14 |
| cn-block:TimeoutError | 11 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| geo:status | 8 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 3 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-94fb1vn3/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-ca6fg5k9/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-71ivo9cw/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: 랛o�4�v�k�;{��>�~� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���ӧ\�^���5�߽�o>�~�w��w� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ݽ5k����^�� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1952 |
| ConnectionRefusedError | 428 |
| gaierror | 154 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.917 | prefer | 45 | 0.933 | 52 |
| Au1rxx-base64 | 0.5 | observe | 95 | 0.495 | 128 |
| roosterkid-openproxylist-v2ray | 0.477 | observe | 32 | 0.469 | 150 |
| Surfboard-tg-mixed | 0.365 | observe | 858 | 0.284 | 4433 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| mfuu-v2ray | 0.263 | observe | 1 | 1.0 | 203 |
| Pawdroid | 0.256 | observe | 1 | 1.0 | 13 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3404 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| moneyfly1-collectSub | 0.073 | downweight | 36 | 0.0 | 0 | 1164 |
| xiaoji235-airport-v2ray-all | 0.077 | downweight | 16 | 0.0 | 0 | 729 |
| ts-sf | 0.104 | downweight | 14 | 0.071 | 0 | 79 |
| ninja-vless | 0.121 | downweight | 15 | 0.0 | 0 | 1791 |
| Barabama-we | 0.128 | observe | 1 | 0.0 | 0 | 23 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| mahdibland-V2RayAggregator | 0.132 | downweight | 13 | 0.0 | 0 | 4560 |
| SoliSpirit-all | 0.134 | downweight | 11 | 0.0 | 0 | 3000 |
| 10ium-ScrapeCategorize-Vless | 0.138 | downweight | 9 | 0.0 | 0 | 2000 |
| 10ium-HighSpeed | 0.161 | observe | 1 | 0.0 | 0 | 839 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | moneyfly1-collectSub | 0.073 | 36 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.077 | 16 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ts-sf | 0.104 | 14 | 0.071 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.121 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.134 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.138 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.187 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mheidari-all | 0.188 | 72 | 0.097 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.201 | 270 | 0.119 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| Barabama-we | 0.0 | 0 | 1 | 1 |
| Epodonios-all | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 9 | 9 |
| SoliSpirit-all | 0.0 | 0 | 11 | 11 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 13 | 13 |
| ninja-vless | 0.0 | 0 | 15 | 15 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 16 | 16 |
| moneyfly1-collectSub | 0.0 | 0 | 36 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 6499 | yes | 2.88 | 0 |
| mahdibland-V2RayAggregator | 4560 | yes | 1.18 | 0 |
| Surfboard-tg-mixed | 4433 | yes | 1.12 | 0 |
| Surfboard-tg-vless | 3404 | yes | 1.86 | 0 |
| Epodonios-all | 3000 | yes | 1.65 | 0 |
| SoliSpirit-all | 3000 | yes | 1.55 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.21 | 0 |
| mheidari-all | 2000 | yes | 2.76 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.36 | 0 |
| barry-far-vless | 2000 | yes | 1.12 | 0 |

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
| 204 | 880 |
| sing-box exited 1 | 79 |
| geo | 68 |
| speed | 52 |
| cn-block | 28 |
