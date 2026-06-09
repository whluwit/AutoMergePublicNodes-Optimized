# AutoNodes 每日报告

生成时间：2026-06-09 09:51:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/10 |
| 清理建议：优先/观察 | 0/34 |
| 原始节点数 | 39508 |
| 去重后节点数 | 15239 |
| TCP 可达数 | 1500 |
| 真测通过数 | 241 |
| verified 输出数 | 241 |
| global 输出数 | 250 |
| all 输出数 | 15239 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 2.7 |
| generate | 28.6 |
| geo | 1.2 |
| real_test | 158.1 |
| tcp | 41.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 35 | 28 | 7 | 80.0% |
| hysteria2 | 14 | 2 | 12 | 14.3% |
| shadowsocks | 348 | 87 | 261 | 25.0% |
| shadowsocksr | 1 | 0 | 1 | 0.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 336 | 21 | 315 | 6.2% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 745 | 94 | 651 | 12.6% |
| vmess | 18 | 9 | 9 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 526 |
| 204:ProxyError | 434 |
| 204:TimeoutError | 131 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 42 |
| geo:status | 37 |
| geo:status | 17 |
| cn-block:TimeoutError | 14 |
| cn-block:ClientOSError | 12 |
| geo:TimeoutError | 10 |
| speed:TimeoutError | 7 |
| speed:ClientOSError | 6 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-w8avtp3o/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-rqgkm759/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-6icgbqb5/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o���mu����� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: chacha20-poly1305 | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �o | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 2107 |
| ConnectionRefusedError | 403 |
| gaierror | 160 |
| OSError | 33 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.655 | observe | 44 | 0.659 | 62 |
| Au1rxx-base64 | 0.503 | observe | 72 | 0.5 | 86 |
| roosterkid-openproxylist-v2ray | 0.4 | observe | 15 | 0.467 | 150 |
| mheidari-all | 0.291 | observe | 93 | 0.204 | 2000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3126 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| Surfboard-tg-mixed | 0.246 | downweight | 661 | 0.165 | 3983 |
| Epodonios-all | 0.225 | downweight | 60 | 0.133 | 3000 |
| 10ium-HighSpeed | 0.209 | observe | 0 | None | 839 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| moneyfly1-collectSub | 0.066 | downweight | 50 | 0.0 | 0 | 1164 |
| abc-configs-readme-latest30 | 0.081 | observe | 4 | 0.0 | 0 | 21 |
| xiaoji235-airport-v2ray-all | 0.082 | downweight | 11 | 0.0 | 0 | 678 |
| Barabama-yudou | 0.087 | observe | 4 | 0.0 | 0 | 166 |
| ninja-vless | 0.117 | downweight | 20 | 0.0 | 0 | 1791 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.132 | downweight | 13 | 0.0 | 0 | 2000 |
| SoliSpirit-all | 0.141 | downweight | 8 | 0.0 | 0 | 3000 |
| mahdibland-V2RayAggregator | 0.141 | downweight | 8 | 0.0 | 0 | 4536 |
| nscl5-all | 0.147 | downweight | 12 | 0.083 | 0 | 1026 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | moneyfly1-collectSub | 0.066 | 50 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.082 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.117 | 20 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.141 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.141 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.147 | 12 | 0.083 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.157 | 424 | 0.075 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Epodonios-all | 0.225 | 60 | 0.133 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Surfboard-tg-mixed | 0.246 | 661 | 0.165 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 4 | 4 |
| abc-configs-readme-latest30 | 0.0 | 0 | 4 | 4 |
| SoliSpirit-all | 0.0 | 0 | 8 | 8 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 8 | 8 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 11 | 11 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 13 | 13 |
| ninja-vless | 0.0 | 0 | 20 | 20 |
| moneyfly1-collectSub | 0.0 | 0 | 50 | 50 |
| DeltaKronecker-all | 0.075 | 32 | 392 | 424 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 4700 | yes | 2.25 | 0 |
| mahdibland-V2RayAggregator | 4536 | yes | 1.29 | 0 |
| Surfboard-tg-mixed | 3983 | yes | 1.9 | 0 |
| Surfboard-tg-vless | 3126 | yes | 1.44 | 0 |
| Epodonios-all | 3000 | yes | 2.46 | 0 |
| SoliSpirit-all | 3000 | yes | 2.15 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.05 | 0 |
| mheidari-all | 2000 | yes | 2.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 0.89 | 0 |
| barry-far-vless | 2000 | yes | 0.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| trojan | 0.062 |
| tuic | 0.0 |
| shadowsocksr | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 1091 |
| geo | 68 |
| sing-box exited 1 | 59 |
| cn-block | 28 |
| speed | 13 |
