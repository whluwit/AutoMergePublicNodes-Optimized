# AutoNodes 每日报告

生成时间：2026-06-11 04:11:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/10 |
| 清理建议：优先/观察 | 1/33 |
| 原始节点数 | 39899 |
| 去重后节点数 | 15156 |
| TCP 可达数 | 1500 |
| 真测通过数 | 403 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15156 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.0 |
| generate | 26.3 |
| geo | 1.2 |
| real_test | 166.0 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 1 | 3 | 25.0% |
| http | 58 | 56 | 2 | 96.6% |
| hysteria2 | 13 | 2 | 11 | 15.4% |
| shadowsocks | 367 | 91 | 276 | 24.8% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 124 | 34 | 90 | 27.4% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 910 | 213 | 697 | 23.4% |
| vmess | 13 | 4 | 9 | 30.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 397 |
| 204:ProxyError | 391 |
| 204:TimeoutError | 92 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 45 |
| geo:status | 37 |
| speed:TimeoutError | 37 |
| speed:ClientOSError | 17 |
| geo:status | 13 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 9 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 4 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o���mu����� | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unsupported flow: xtls-rprx-vision-udp443 | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: i�s���G�k� | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �׺m����k� | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-x_sd5cyd/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1796 |
| ConnectionRefusedError | 414 |
| gaierror | 173 |
| OSError | 24 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.924 | prefer | 61 | 0.934 | 75 |
| roosterkid-openproxylist-v2ray | 0.688 | observe | 20 | 0.7 | 150 |
| Au1rxx-base64 | 0.505 | observe | 88 | 0.5 | 124 |
| Surfboard-tg-mixed | 0.416 | observe | 689 | 0.335 | 4159 |
| Epodonios-all | 0.287 | observe | 2 | 0.5 | 3000 |
| mheidari-all | 0.278 | observe | 99 | 0.192 | 2000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3321 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| barry-far-Sub2 | 0.195 | observe | 0 | None | 500 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| 10ium-HighSpeed | 0.061 | downweight | 71 | 0.014 | 0 | 839 |
| Barabama-we | 0.074 | downweight | 5 | 0.0 | 0 | 23 |
| moneyfly1-collectSub | 0.099 | downweight | 12 | 0.0 | 0 | 1164 |
| ermaozi | 0.105 | observe | 2 | 0.0 | 0 | 29 |
| ninja-vless | 0.109 | downweight | 25 | 0.0 | 0 | 1791 |
| SoliSpirit-all | 0.11 | downweight | 31 | 0.0 | 0 | 3000 |
| nscl5-all | 0.122 | downweight | 95 | 0.074 | 0 | 984 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.128 | downweight | 17 | 0.0 | 0 | 2000 |
| mahdibland-V2RayAggregator | 0.13 | downweight | 14 | 0.0 | 0 | 4508 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-HighSpeed | 0.061 | 71 | 0.014 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-we | 0.074 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.099 | 12 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.109 | 25 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.11 | 31 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.122 | 95 | 0.074 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.128 | 17 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.13 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.174 | 16 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.188 | 248 | 0.105 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| Au1rxx-clash | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.0 | 0 | 2 | 2 |
| Barabama-we | 0.0 | 0 | 5 | 5 |
| moneyfly1-collectSub | 0.0 | 0 | 12 | 12 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 14 | 14 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 17 | 17 |
| ninja-vless | 0.0 | 0 | 25 | 25 |
| SoliSpirit-all | 0.0 | 0 | 31 | 31 |
| 10ium-HighSpeed | 0.014 | 1 | 70 | 71 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4616 | yes | 3.18 | 0 |
| mahdibland-V2RayAggregator | 4508 | yes | 1.57 | 0 |
| Surfboard-tg-mixed | 4159 | yes | 1.97 | 0 |
| Surfboard-tg-vless | 3321 | yes | 1.8 | 0 |
| Epodonios-all | 3000 | yes | 1.51 | 0 |
| SoliSpirit-all | 3000 | yes | 1.29 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.09 | 0 |
| mheidari-all | 2000 | yes | 2.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 0.85 | 0 |
| barry-far-vless | 2000 | yes | 0.99 | 0 |

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
| 204 | 880 |
| sing-box exited 1 | 86 |
| speed | 54 |
| geo | 53 |
| cn-block | 24 |
