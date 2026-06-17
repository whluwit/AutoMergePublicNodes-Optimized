# AutoNodes 每日报告

生成时间：2026-06-17 16:26:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/8 |
| 清理建议：优先/观察 | 0/36 |
| 原始节点数 | 43524 |
| 去重后节点数 | 18049 |
| TCP 可达数 | 1500 |
| 真测通过数 | 236 |
| verified 输出数 | 236 |
| global 输出数 | 249 |
| all 输出数 | 18049 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.4 |
| generate | 28.5 |
| geo | 1.3 |
| real_test | 233.3 |
| tcp | 46.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 27 | 25 | 2 | 92.6% |
| hysteria2 | 9 | 1 | 8 | 11.1% |
| shadowsocks | 234 | 55 | 179 | 23.5% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 247 | 17 | 230 | 6.9% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 957 | 132 | 825 | 13.8% |
| vmess | 15 | 6 | 9 | 40.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 398 |
| 204:ClientOSError | 357 |
| geo:status | 158 |
| 204:TimeoutError | 131 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 69 |
| geo:status | 50 |
| speed:ClientOSError | 46 |
| cn-block:TimeoutError | 20 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| cn-block:ClientOSError | 8 |
| speed:TimeoutError | 6 |
| geo:TimeoutError | 5 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-kheixbdt/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-x3vin418/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-pgle6o6v/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| geo:ClientOSError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: chacha20-poly1305 | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 2157 |
| ConnectionRefusedError | 464 |
| gaierror | 168 |
| OSError | 39 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.528 | observe | 59 | 0.525 | 73 |
| roosterkid-openproxylist-v2ray | 0.486 | observe | 23 | 0.478 | 150 |
| Au1rxx-base64 | 0.47 | observe | 84 | 0.464 | 116 |
| Surfboard-tg-vless | 0.386 | observe | 60 | 0.3 | 3561 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| mheidari-all | 0.249 | downweight | 87 | 0.161 | 2000 |
| ninja-vless | 0.218 | downweight | 5 | 0.2 | 1791 |
| SoliSpirit-all | 0.207 | observe | 1 | 0.0 | 3000 |
| barry-far-Sub2 | 0.195 | observe | 0 | None | 497 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| moneyfly1-collectSub | 0.088 | downweight | 22 | 0.0 | 0 | 1164 |
| xiaoji235-airport-v2ray-all | 0.092 | downweight | 6 | 0.0 | 0 | 588 |
| Barabama-yudou | 0.098 | downweight | 20 | 0.05 | 0 | 166 |
| 10ium-HighSpeed | 0.123 | observe | 3 | 0.0 | 0 | 839 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| mahdibland-V2RayAggregator | 0.128 | downweight | 17 | 0.0 | 0 | 4516 |
| nscl5-all | 0.142 | observe | 2 | 0.0 | 0 | 967 |
| Epodonios-all | 0.16 | observe | 4 | 0.0 | 0 | 3000 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| tonykong-base64 | 0.175 | observe | 0 | None | 0 | 5 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | moneyfly1-collectSub | 0.088 | 22 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.092 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-yudou | 0.098 | 20 | 0.05 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.128 | 17 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.18 | 217 | 0.097 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Surfboard-tg-mixed | 0.193 | 884 | 0.112 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.218 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mheidari-all | 0.249 | 87 | 0.161 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| SoliSpirit-all | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| 10ium-HighSpeed | 0.0 | 0 | 3 | 3 |
| Epodonios-all | 0.0 | 0 | 4 | 4 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 6 | 6 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 17 | 17 |
| moneyfly1-collectSub | 0.0 | 0 | 22 | 22 |
| Barabama-yudou | 0.05 | 1 | 19 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 7763 | yes | 3.5 | 0 |
| Surfboard-tg-mixed | 4665 | yes | 2.44 | 0 |
| mahdibland-V2RayAggregator | 4516 | yes | 1.53 | 0 |
| Surfboard-tg-vless | 3561 | yes | 1.96 | 0 |
| Epodonios-all | 3000 | yes | 2.23 | 0 |
| SoliSpirit-all | 3000 | yes | 2.24 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.86 | 0 |
| mheidari-all | 2000 | yes | 3.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.4 | 0 |
| barry-far-vless | 2000 | yes | 1.24 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| trojan | 0.069 |
| tuic | 0.0 |
| shadowsocksr | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 886 |
| geo | 215 |
| sing-box exited 1 | 81 |
| speed | 52 |
| cn-block | 30 |
