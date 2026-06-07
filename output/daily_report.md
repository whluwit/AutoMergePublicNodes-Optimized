# AutoNodes 每日报告

生成时间：2026-06-07 00:36:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/9 |
| 清理建议：优先/观察 | 1/34 |
| 原始节点数 | 39697 |
| 去重后节点数 | 15354 |
| TCP 可达数 | 1500 |
| 真测通过数 | 402 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 15354 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 2.5 |
| generate | 13.8 |
| geo | 1.1 |
| real_test | 144.1 |
| tcp | 36.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 23 | 7 | 16 | 30.4% |
| hysteria2 | 18 | 3 | 15 | 16.7% |
| shadowsocks | 353 | 115 | 238 | 32.6% |
| shadowsocksr | 8 | 0 | 8 | 0.0% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 204 | 57 | 147 | 27.9% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 871 | 212 | 659 | 24.3% |
| vmess | 16 | 7 | 9 | 43.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 433 |
| 204:ClientOSError | 420 |
| 204:TimeoutError | 87 |
| speed:TimeoutError | 50 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | 23 |
| speed:ClientOSError | 22 |
| geo:status | 17 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | 8 |
| cn-block:ClientOSError | 8 |
| cn-block:TimeoutError | 7 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unsupported flow: xtls-rprx-vision-udp443 | 4 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ݽ5k����^�� | 2 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-ieyzd5ax/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-fqu0fvdr/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] decode config at /tmp/sb-zs2f53gq/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: վ����N]k� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ߾��ε�g��� | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: ���������� | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 1745 |
| ConnectionRefusedError | 450 |
| gaierror | 204 |
| OSError | 28 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| roosterkid-openproxylist-v2ray | 0.71 | prefer | 25 | 0.72 | 150 |
| Au1rxx-base64 | 0.553 | observe | 58 | 0.552 | 84 |
| mheidari-all | 0.465 | observe | 102 | 0.382 | 2000 |
| Surfboard-tg-mixed | 0.383 | observe | 852 | 0.303 | 4296 |
| snakem982 | 0.298 | observe | 25 | 0.28 | 47 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3300 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |
| DeltaKronecker-all | 0.235 | downweight | 243 | 0.152 | 4517 |
| 10ium-HighSpeed | 0.209 | observe | 0 | None | 839 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| moneyfly1-collectSub | 0.07 | downweight | 41 | 0.0 | 0 | 1164 |
| ninja-vless | 0.122 | downweight | 14 | 0.0 | 0 | 1791 |
| xiaoji235-airport-v2ray-all | 0.125 | downweight | 15 | 0.067 | 0 | 661 |
| 10ium-ScrapeCategorize-Vless | 0.126 | downweight | 19 | 0.0 | 0 | 2000 |
| ninja-tuic | 0.128 | observe | 1 | 0.0 | 0 | 1 |
| mahdibland-V2RayAggregator | 0.13 | downweight | 14 | 0.0 | 0 | 4642 |
| SoliSpirit-all | 0.144 | downweight | 7 | 0.0 | 0 | 3000 |
| nscl5-all | 0.163 | downweight | 39 | 0.103 | 0 | 1018 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | moneyfly1-collectSub | 0.07 | 41 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.122 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | xiaoji235-airport-v2ray-all | 0.125 | 15 | 0.067 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.126 | 19 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mahdibland-V2RayAggregator | 0.13 | 14 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | SoliSpirit-all | 0.144 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | nscl5-all | 0.163 | 39 | 0.103 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | Epodonios-all | 0.202 | 39 | 0.103 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.235 | 243 | 0.152 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-tuic | 0.0 | 0 | 1 | 1 |
| SoliSpirit-all | 0.0 | 0 | 7 | 7 |
| ninja-vless | 0.0 | 0 | 14 | 14 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 14 | 14 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 19 | 19 |
| moneyfly1-collectSub | 0.0 | 0 | 41 | 41 |
| xiaoji235-airport-v2ray-all | 0.067 | 1 | 14 | 15 |
| Epodonios-all | 0.103 | 4 | 35 | 39 |
| nscl5-all | 0.103 | 4 | 35 | 39 |
| DeltaKronecker-all | 0.152 | 37 | 206 | 243 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 4642 | yes | 0.35 | 0 |
| DeltaKronecker-all | 4517 | yes | 2.31 | 0 |
| Surfboard-tg-mixed | 4296 | yes | 1.74 | 0 |
| Surfboard-tg-vless | 3300 | yes | 0.44 | 0 |
| Epodonios-all | 3000 | yes | 2.4 | 0 |
| SoliSpirit-all | 3000 | yes | 1.98 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.26 | 0 |
| mheidari-all | 2000 | yes | 2.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.07 | 0 |
| barry-far-vless | 2000 | yes | 1.05 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |
| tuic | 0.0 |
| shadowsocksr | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 940 |
| speed | 75 |
| sing-box exited 1 | 48 |
| geo | 18 |
| cn-block | 17 |
