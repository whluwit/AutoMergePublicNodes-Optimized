# AutoNodes 每日报告

生成时间：2026-06-12 15:22:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/10 |
| 清理建议：优先/观察 | 1/33 |
| 原始节点数 | 40369 |
| 去重后节点数 | 14971 |
| TCP 可达数 | 1500 |
| 真测通过数 | 273 |
| verified 输出数 | 273 |
| global 输出数 | 281 |
| all 输出数 | 14971 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.2 |
| generate | 26.9 |
| geo | 1.2 |
| real_test | 150.6 |
| tcp | 36.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 11 | 1 | 10 | 9.1% |
| shadowsocks | 357 | 79 | 278 | 22.1% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 340 | 16 | 324 | 4.7% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 722 | 129 | 593 | 17.9% |
| vmess | 15 | 6 | 9 | 40.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 500 |
| 204:ProxyError | 403 |
| 204:TimeoutError | 84 |
| geo:status | 72 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 51 |
| geo:status | 27 |
| cn-block:ClientOSError | 11 |
| cn-block:TimeoutError | 11 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| cn-block:ProxyError | 8 |
| speed:TimeoutError | 6 |
| geo:TimeoutError | 6 |
| geo:ProxyError | 5 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: i�s���G�k� | 4 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �Z׮|�� | 3 |
| speed:ClientOSError | 2 |
| geo:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-jthrju9b/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-0alknww3/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1893 |
| ConnectionRefusedError | 438 |
| gaierror | 157 |
| OSError | 33 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | prefer | 43 | 0.977 | 52 |
| roosterkid-openproxylist-v2ray | 0.506 | observe | 32 | 0.5 | 150 |
| Au1rxx-base64 | 0.471 | observe | 73 | 0.466 | 108 |
| mheidari-all | 0.298 | observe | 76 | 0.211 | 2000 |
| Surfboard-tg-mixed | 0.289 | observe | 663 | 0.208 | 4226 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3230 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| 10ium-HighSpeed | 0.209 | observe | 0 | None | 839 |
| barry-far-Sub2 | 0.195 | observe | 0 | None | 495 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| ts-sf | 0.051 | downweight | 18 | 0.0 | 0 | 111 |
| xiaoji235-airport-v2ray-all | 0.089 | downweight | 9 | 0.0 | 0 | 774 |
| moneyfly1-collectSub | 0.093 | downweight | 19 | 0.0 | 0 | 1164 |
| Barabama-yudou | 0.094 | downweight | 21 | 0.048 | 0 | 166 |
| chromego_merge | 0.106 | observe | 2 | 0.0 | 0 | 49 |
| nscl5-all | 0.106 | downweight | 9 | 0.0 | 0 | 1178 |
| SoliSpirit-all | 0.113 | downweight | 28 | 0.0 | 0 | 3000 |
| ninja-vless | 0.117 | downweight | 20 | 0.0 | 0 | 1791 |
| Barabama-we | 0.128 | observe | 1 | 0.0 | 0 | 23 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ts-sf | 0.051 | 18 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.089 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.093 | 19 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-yudou | 0.094 | 21 | 0.048 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.106 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.113 | 28 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.117 | 20 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.128 | 16 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.129 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.139 | 452 | 0.058 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| Barabama-we | 0.0 | 0 | 1 | 1 |
| Epodonios-all | 0.0 | 0 | 2 | 2 |
| chromego_merge | 0.0 | 0 | 2 | 2 |
| nscl5-all | 0.0 | 0 | 9 | 9 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 9 | 9 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 15 | 15 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 16 | 16 |
| ts-sf | 0.0 | 0 | 18 | 18 |
| moneyfly1-collectSub | 0.0 | 0 | 19 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4706 | yes | 3.24 | 0 |
| mahdibland-V2RayAggregator | 4561 | yes | 0.54 | 0 |
| Surfboard-tg-mixed | 4226 | yes | 1.81 | 0 |
| Surfboard-tg-vless | 3230 | yes | 1.69 | 0 |
| Epodonios-all | 3000 | yes | 0.48 | 0 |
| SoliSpirit-all | 3000 | yes | 1.04 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 0.84 | 0 |
| mheidari-all | 2000 | yes | 2.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 0.63 | 0 |
| barry-far-vless | 2000 | yes | 0.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| trojan | 0.047 |
| hysteria2 | 0.091 |
| shadowsocksr | 0.0 |
| tuic | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 987 |
| geo | 112 |
| sing-box exited 1 | 89 |
| cn-block | 30 |
| speed | 9 |
