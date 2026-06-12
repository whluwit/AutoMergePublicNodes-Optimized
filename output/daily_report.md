# AutoNodes 每日报告

生成时间：2026-06-12 00:34:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/6 |
| 清理建议：优先/观察 | 1/37 |
| 原始节点数 | 40038 |
| 去重后节点数 | 15021 |
| TCP 可达数 | 1500 |
| 真测通过数 | 389 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15021 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.1 |
| generate | 18.5 |
| geo | 1.2 |
| real_test | 187.2 |
| tcp | 34.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 42 | 2 | 95.5% |
| hysteria2 | 5 | 1 | 4 | 20.0% |
| shadowsocks | 357 | 100 | 257 | 28.0% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 32 | 25 | 7 | 78.1% |
| trojan | 143 | 45 | 98 | 31.5% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 895 | 169 | 726 | 18.9% |
| vmess | 15 | 7 | 8 | 46.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 338 |
| 204:ProxyError | 327 |
| speed:TimeoutError | 122 |
| speed:ClientOSError | 104 |
| 204:TimeoutError | 83 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 53 |
| geo:status | 32 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 11 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 5 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-i0ijnaa6/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-n39i8m7w/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-thyixjia/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ٭���7��v�� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ٽv��{��u�� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o���mu����� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �o | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ݽ5k����^�� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1808 |
| ConnectionRefusedError | 426 |
| gaierror | 170 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | prefer | 43 | 0.977 | 52 |
| Au1rxx-base64 | 0.469 | observe | 95 | 0.463 | 129 |
| Surfboard-tg-mixed | 0.379 | observe | 750 | 0.299 | 4225 |
| mheidari-all | 0.322 | observe | 89 | 0.236 | 2000 |
| roosterkid-openproxylist-v2ray | 0.306 | observe | 28 | 0.286 | 150 |
| Epodonios-all | 0.287 | observe | 2 | 0.5 | 3000 |
| Barabama-yudou | 0.275 | observe | 3 | 0.667 | 166 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3224 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| moneyfly1-collectSub | 0.105 | downweight | 9 | 0.0 | 0 | 1164 |
| xiaoji235-airport-v2ray-all | 0.109 | observe | 4 | 0.0 | 0 | 729 |
| 10ium-HighSpeed | 0.114 | observe | 4 | 0.0 | 0 | 839 |
| ninja-vless | 0.118 | downweight | 18 | 0.0 | 0 | 1791 |
| abc-configs-readme-latest30 | 0.128 | observe | 1 | 0.0 | 0 | 24 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| SoliSpirit-all | 0.128 | downweight | 17 | 0.0 | 0 | 3000 |
| 10ium-ScrapeCategorize-Vless | 0.132 | downweight | 13 | 0.0 | 0 | 2000 |
| mahdibland-V2RayAggregator | 0.132 | downweight | 13 | 0.0 | 0 | 4536 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | moneyfly1-collectSub | 0.105 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.118 | 18 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.128 | 17 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.195 | 406 | 0.113 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 4 | 4 |
| 10ium-HighSpeed | 0.0 | 0 | 4 | 4 |
| moneyfly1-collectSub | 0.0 | 0 | 9 | 9 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 13 | 13 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 13 | 13 |
| SoliSpirit-all | 0.0 | 0 | 17 | 17 |
| ninja-vless | 0.0 | 0 | 18 | 18 |
| DeltaKronecker-all | 0.113 | 46 | 360 | 406 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4660 | yes | 3.21 | 0 |
| mahdibland-V2RayAggregator | 4536 | yes | 0.62 | 0 |
| Surfboard-tg-mixed | 4225 | yes | 0.27 | 0 |
| Surfboard-tg-vless | 3224 | yes | 1.83 | 0 |
| Epodonios-all | 3000 | yes | 3.01 | 0 |
| SoliSpirit-all | 3000 | yes | 1.55 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 0.94 | 0 |
| mheidari-all | 2000 | yes | 2.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.73 | 0 |
| barry-far-vless | 2000 | yes | 0.87 | 0 |

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
| 204 | 748 |
| speed | 226 |
| sing-box exited 1 | 78 |
| geo | 36 |
| cn-block | 23 |
