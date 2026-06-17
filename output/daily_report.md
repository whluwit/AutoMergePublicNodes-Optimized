# AutoNodes 每日报告

生成时间：2026-06-17 15:40:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/9 |
| 清理建议：优先/观察 | 0/35 |
| 原始节点数 | 43522 |
| 去重后节点数 | 18053 |
| TCP 可达数 | 1500 |
| 真测通过数 | 257 |
| verified 输出数 | 257 |
| global 输出数 | 270 |
| all 输出数 | 18053 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.6 |
| generate | 29.3 |
| geo | 1.2 |
| real_test | 200.8 |
| tcp | 39.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 27 | 25 | 2 | 92.6% |
| hysteria2 | 11 | 2 | 9 | 18.2% |
| shadowsocks | 361 | 69 | 292 | 19.1% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 183 | 33 | 150 | 18.0% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 893 | 123 | 770 | 13.8% |
| vmess | 15 | 5 | 10 | 33.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 456 |
| 204:ClientOSError | 373 |
| geo:status | 140 |
| 204:TimeoutError | 70 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 60 |
| geo:status | 60 |
| cn-block:TimeoutError | 21 |
| speed:ClientOSError | 12 |
| speed:TimeoutError | 9 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| cn-block:ClientOSError | 7 |
| geo:ProxyError | 4 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 3 |
| speed:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| geo:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-jknq79uy/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-bq1hl5b5/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-v3qgpgr2/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: {� | צ����� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1959 |
| ConnectionRefusedError | 447 |
| gaierror | 180 |
| OSError | 39 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.544 | observe | 59 | 0.542 | 73 |
| roosterkid-openproxylist-v2ray | 0.544 | observe | 24 | 0.542 | 150 |
| Au1rxx-base64 | 0.454 | observe | 87 | 0.448 | 116 |
| Surfboard-tg-vless | 0.342 | observe | 63 | 0.254 | 3561 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Pawdroid | 0.255 | observe | 1 | 1.0 | 8 |
| Epodonios-all | 0.255 | observe | 0 | None | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| mheidari-all | 0.226 | downweight | 87 | 0.138 | 2000 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.08 | downweight | 10 | 0.0 | 0 | 588 |
| moneyfly1-collectSub | 0.085 | downweight | 24 | 0.0 | 0 | 1164 |
| ninja-vless | 0.118 | downweight | 18 | 0.0 | 0 | 1791 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.128 | downweight | 16 | 0.0 | 0 | 2000 |
| mahdibland-V2RayAggregator | 0.129 | downweight | 15 | 0.0 | 0 | 4516 |
| SoliSpirit-all | 0.13 | downweight | 14 | 0.0 | 0 | 3000 |
| nscl5-all | 0.142 | observe | 2 | 0.0 | 0 | 967 |
| 10ium-HighSpeed | 0.161 | observe | 1 | 0.0 | 0 | 839 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.08 | 10 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.085 | 24 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.118 | 18 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.128 | 16 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.129 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.13 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.194 | 262 | 0.111 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Surfboard-tg-mixed | 0.221 | 815 | 0.14 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mheidari-all | 0.226 | 87 | 0.138 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 2 | 2 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 10 | 10 |
| SoliSpirit-all | 0.0 | 0 | 14 | 14 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 15 | 15 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 16 | 16 |
| ninja-vless | 0.0 | 0 | 18 | 18 |
| moneyfly1-collectSub | 0.0 | 0 | 24 | 24 |
| DeltaKronecker-all | 0.111 | 29 | 233 | 262 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 7763 | yes | 3.88 | 0 |
| Surfboard-tg-mixed | 4665 | yes | 0.26 | 0 |
| mahdibland-V2RayAggregator | 4516 | yes | 1.67 | 0 |
| Surfboard-tg-vless | 3561 | yes | 1.8 | 0 |
| Epodonios-all | 3000 | yes | 2.2 | 0 |
| SoliSpirit-all | 3000 | yes | 2.44 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.7 | 0 |
| mheidari-all | 2000 | yes | 2.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.62 | 0 |
| barry-far-vless | 2000 | yes | 1.35 | 0 |

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
| 204 | 899 |
| geo | 207 |
| sing-box exited 1 | 83 |
| cn-block | 30 |
| speed | 24 |
