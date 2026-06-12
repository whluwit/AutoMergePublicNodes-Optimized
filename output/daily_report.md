# AutoNodes 每日报告

生成时间：2026-06-12 00:40:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/8 |
| 清理建议：优先/观察 | 1/35 |
| 原始节点数 | 40038 |
| 去重后节点数 | 15021 |
| TCP 可达数 | 1500 |
| 真测通过数 | 386 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15021 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.2 |
| generate | 25.5 |
| geo | 1.2 |
| real_test | 191.1 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 7 | 2 | 5 | 28.6% |
| shadowsocks | 355 | 103 | 252 | 29.0% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 32 | 26 | 6 | 81.2% |
| trojan | 122 | 40 | 82 | 32.8% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 916 | 166 | 750 | 18.1% |
| vmess | 15 | 7 | 8 | 46.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 348 |
| 204:ClientOSError | 314 |
| speed:TimeoutError | 129 |
| speed:ClientOSError | 114 |
| 204:TimeoutError | 73 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 53 |
| geo:status | 34 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 10 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 4 |
| geo:TimeoutError | 4 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-eioaiysl/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-klbshtsa/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-fov11t9r/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o���mu����� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ٽv��{��u�� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ݽ5k����^�� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: chacha20-poly1305 | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1928 |
| ConnectionRefusedError | 415 |
| gaierror | 139 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | prefer | 43 | 0.977 | 52 |
| Au1rxx-base64 | 0.5 | observe | 95 | 0.495 | 129 |
| Surfboard-tg-mixed | 0.392 | observe | 719 | 0.312 | 4225 |
| mheidari-all | 0.333 | observe | 85 | 0.247 | 2000 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.316 | observe | 27 | 0.296 | 150 |
| Epodonios-all | 0.287 | observe | 2 | 0.5 | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3224 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.078 | downweight | 15 | 0.0 | 0 | 729 |
| moneyfly1-collectSub | 0.093 | downweight | 19 | 0.0 | 0 | 1164 |
| nscl5-all | 0.107 | downweight | 6 | 0.0 | 0 | 984 |
| 10ium-ScrapeCategorize-Vless | 0.11 | downweight | 31 | 0.0 | 0 | 2000 |
| 10ium-HighSpeed | 0.114 | observe | 4 | 0.0 | 0 | 839 |
| ninja-vless | 0.122 | downweight | 14 | 0.0 | 0 | 1791 |
| abc-configs-readme-latest30 | 0.128 | observe | 1 | 0.0 | 0 | 24 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| mahdibland-V2RayAggregator | 0.132 | downweight | 13 | 0.0 | 0 | 4536 |
| SoliSpirit-all | 0.141 | downweight | 8 | 0.0 | 0 | 3000 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.078 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | moneyfly1-collectSub | 0.093 | 19 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.107 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.11 | 31 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.122 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.141 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.181 | 415 | 0.099 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 4 | 4 |
| nscl5-all | 0.0 | 0 | 6 | 6 |
| SoliSpirit-all | 0.0 | 0 | 8 | 8 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 13 | 13 |
| ninja-vless | 0.0 | 0 | 14 | 14 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 15 | 15 |
| moneyfly1-collectSub | 0.0 | 0 | 19 | 19 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 31 | 31 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4660 | yes | 2.92 | 0 |
| mahdibland-V2RayAggregator | 4536 | yes | 1.39 | 0 |
| Surfboard-tg-mixed | 4225 | yes | 1.88 | 0 |
| Surfboard-tg-vless | 3224 | yes | 2.0 | 0 |
| Epodonios-all | 3000 | yes | 2.98 | 0 |
| SoliSpirit-all | 3000 | yes | 1.47 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 0.76 | 0 |
| mheidari-all | 2000 | yes | 2.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.27 | 0 |
| barry-far-vless | 2000 | yes | 0.45 | 0 |

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
| 204 | 735 |
| speed | 243 |
| sing-box exited 1 | 74 |
| geo | 39 |
| cn-block | 23 |
