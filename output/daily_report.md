# AutoNodes 每日报告

生成时间：2026-06-07 09:01:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/10 |
| 清理建议：优先/观察 | 0/34 |
| 原始节点数 | 39804 |
| 去重后节点数 | 15391 |
| TCP 可达数 | 1500 |
| 真测通过数 | 245 |
| verified 输出数 | 245 |
| global 输出数 | 260 |
| all 输出数 | 15391 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 2.5 |
| generate | 24.8 |
| geo | 1.2 |
| real_test | 141.3 |
| tcp | 41.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 9 | 7 | 2 | 77.8% |
| hysteria2 | 14 | 1 | 13 | 7.1% |
| shadowsocks | 366 | 97 | 269 | 26.5% |
| shadowsocksr | 7 | 0 | 7 | 0.0% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 237 | 34 | 203 | 14.3% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 844 | 97 | 747 | 11.5% |
| vmess | 17 | 8 | 9 | 47.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 506 |
| 204:ClientOSError | 440 |
| 204:TimeoutError | 120 |
| geo:status | 37 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 35 |
| speed:ClientOSError | 27 |
| speed:TimeoutError | 19 |
| cn-block:TimeoutError | 17 |
| geo:status | 16 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 7 |
| cn-block:ClientOSError | 7 |
| geo:TimeoutError | 4 |
| geo:ProxyError | 2 |
| geo:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-vaof_k06/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-fgi2zc8e/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-fcjtu9ac/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: վ����N]k� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: � | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ��<���M���4�Ϛ׷~{�^�^ | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 2049 |
| ConnectionRefusedError | 439 |
| gaierror | 107 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| roosterkid-openproxylist-v2ray | 0.509 | observe | 14 | 0.643 | 150 |
| Au1rxx-base64 | 0.477 | observe | 55 | 0.473 | 84 |
| snakem982 | 0.452 | observe | 10 | 0.7 | 47 |
| mheidari-all | 0.311 | observe | 119 | 0.227 | 2000 |
| Surfboard-tg-mixed | 0.255 | observe | 719 | 0.174 | 4376 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3358 |
| DeltaKronecker-all | 0.221 | downweight | 275 | 0.138 | 4578 |
| barry-far-vless | 0.207 | observe | 1 | 0.0 | 2000 |
| Epodonios-all | 0.198 | downweight | 83 | 0.108 | 3000 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| moneyfly1-collectSub | 0.071 | downweight | 39 | 0.0 | 0 | 1164 |
| xiaoji235-airport-v2ray-all | 0.08 | downweight | 11 | 0.0 | 0 | 646 |
| nscl5-all | 0.082 | downweight | 94 | 0.032 | 0 | 1013 |
| Barabama-yudou | 0.102 | downweight | 17 | 0.059 | 0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.12 | downweight | 23 | 0.0 | 0 | 2000 |
| ninja-vless | 0.121 | downweight | 15 | 0.0 | 0 | 1791 |
| abc-configs-readme-latest30 | 0.128 | observe | 1 | 0.0 | 0 | 21 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| mahdibland-V2RayAggregator | 0.132 | downweight | 13 | 0.0 | 0 | 4612 |
| SoliSpirit-all | 0.138 | downweight | 9 | 0.0 | 0 | 3000 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | moneyfly1-collectSub | 0.071 | 39 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.08 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.082 | 94 | 0.032 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Barabama-yudou | 0.102 | 17 | 0.059 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.12 | 23 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.121 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.132 | 13 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.138 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Epodonios-all | 0.198 | 83 | 0.108 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.221 | 275 | 0.138 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.0 | 0 | 1 | 1 |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| barry-far-vless | 0.0 | 0 | 1 | 1 |
| SoliSpirit-all | 0.0 | 0 | 9 | 9 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 11 | 11 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 13 | 13 |
| ninja-vless | 0.0 | 0 | 15 | 15 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 23 | 23 |
| moneyfly1-collectSub | 0.0 | 0 | 39 | 39 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 4612 | yes | 1.12 | 0 |
| DeltaKronecker-all | 4578 | yes | 2.1 | 0 |
| Surfboard-tg-mixed | 4376 | yes | 1.4 | 0 |
| Surfboard-tg-vless | 3358 | yes | 1.23 | 0 |
| Epodonios-all | 3000 | yes | 2.23 | 0 |
| SoliSpirit-all | 3000 | yes | 1.48 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 0.71 | 0 |
| mheidari-all | 2000 | yes | 2.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 0.65 | 0 |
| barry-far-vless | 2000 | yes | 0.55 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| hysteria2 | 0.071 |
| shadowsocksr | 0.0 |
| tuic | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 1066 |
| geo | 61 |
| sing-box exited 1 | 56 |
| speed | 47 |
| cn-block | 25 |
