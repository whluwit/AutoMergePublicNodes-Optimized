# AutoNodes 每日报告

生成时间：2026-10-13 13:38:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 99040 |
| 去重后节点数 | 27275 |
| TCP 可达数 | 3000 |
| 真测通过数 | 390 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27275 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 84.3 |
| geo | 1.4 |
| probe | 343.5 |
| real_test | 366.0 |
| tcp | 47.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 5 | 0 | 100.0% |
| http | 27 | 13 | 14 | 48.1% |
| hysteria2 | 12 | 8 | 4 | 66.7% |
| shadowsocks | 145 | 128 | 17 | 88.3% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 117 | 92 | 25 | 78.6% |
| vless | 174 | 143 | 31 | 82.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 30 |
| 204:ProxyError | 15 |
| cn-block:TimeoutError | 15 |
| geo:TimeoutError | 13 |
| speed:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ProxyConnectionError | 4 |
| speed:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:44054: bind: address already in use | 1 |
| 204:ClientOSError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6996 |
| ConnectionRefusedError | 1014 |
| OSError | 235 |
| gaierror | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.959 | prefer | 323 | 0.892 | 1754 |
| mheidari-all | 0.813 | prefer | 28 | 0.75 | 24075 |
| Surfboard-tg-mixed | 0.796 | prefer | 65 | 0.723 | 7206 |
| zhangkai | 0.675 | observe | 13 | 0.923 | 144 |
| DeltaKronecker-all | 0.565 | observe | 31 | 0.484 | 5076 |
| ermaozi-get_subscribe | 0.344 | observe | 19 | 0.316 | 534 |
| ermaozi | 0.257 | observe | 1 | 1.0 | 60 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5086 |
| Epodonios-all | 0.255 | observe | 0 | None | 7717 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.316 | 6 | 13 | 19 |
| DeltaKronecker-all | 0.484 | 15 | 16 | 31 |
| Surfboard-tg-mixed | 0.723 | 47 | 18 | 65 |
| mheidari-all | 0.75 | 21 | 7 | 28 |
| Au1rxx-base64 | 0.892 | 288 | 35 | 323 |
| zhangkai | 0.923 | 12 | 1 | 13 |
| ermaozi | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24075 | yes | 5.36 | 0 |
| SoliSpirit-all | 9931 | yes | 2.38 | 0 |
| Epodonios-all | 7717 | yes | 5.63 | 0 |
| Surfboard-tg-mixed | 7206 | yes | 4.3 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.67 | 0 |
| barry-far-vless | 5973 | yes | 1.05 | 0 |
| Surfboard-tg-vless | 5725 | yes | 4.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 5086 | yes | 0.84 | 0 |
| DeltaKronecker-all | 5076 | yes | 4.58 | 0 |
| mahdibland-V2RayAggregator | 4312 | yes | 2.72 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 50 |
| cn-block | 20 |
| geo | 14 |
| speed | 8 |
| sing-box exited 1 | 1 |
