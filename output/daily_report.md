# AutoNodes 每日报告

生成时间：2026-07-16 13:44:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79344 |
| 去重后节点数 | 24507 |
| TCP 可达数 | 3000 |
| 真测通过数 | 476 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24507 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 35.0 |
| geo | 1.0 |
| probe | 50.4 |
| real_test | 118.9 |
| tcp | 33.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 113 | 103 | 10 | 91.2% |
| socks | 8 | 6 | 2 | 75.0% |
| trojan | 322 | 291 | 31 | 90.4% |
| vless | 205 | 34 | 171 | 16.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 97 |
| geo:TimeoutError | 58 |
| geo:ClientOSError | 16 |
| cn-block:TimeoutError | 11 |
| 204:TimeoutError | 7 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:49901: bind: address already in use | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4501 |
| ConnectionRefusedError | 668 |
| gaierror | 281 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.912 | prefer | 126 | 0.913 | 150 |
| Surfboard-tg-mixed | 0.82 | prefer | 98 | 0.745 | 5430 |
| DeltaKronecker-all | 0.673 | observe | 411 | 0.594 | 8462 |
| mheidari-all | 0.46 | observe | 17 | 0.412 | 16416 |
| xiaoji235-airport-v2ray-all | 0.325 | observe | 1 | 1.0 | 1757 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4470 |
| Epodonios-all | 0.255 | observe | 0 | None | 6545 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7282 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.412 | 7 | 10 | 17 |
| DeltaKronecker-all | 0.594 | 244 | 167 | 411 |
| Surfboard-tg-mixed | 0.745 | 73 | 25 | 98 |
| Au1rxx-base64 | 0.913 | 115 | 11 | 126 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16416 | yes | 3.0 | 0 |
| DeltaKronecker-all | 8462 | yes | 3.48 | 0 |
| SoliSpirit-all | 7282 | yes | 1.8 | 0 |
| Epodonios-all | 6545 | yes | 0.82 | 0 |
| Surfboard-tg-mixed | 5430 | yes | 1.91 | 0 |
| mahdibland-V2RayAggregator | 5262 | yes | 0.42 | 0 |
| barry-far-vless | 4817 | yes | 0.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 4470 | yes | 0.92 | 0 |
| Surfboard-tg-vless | 4211 | yes | 2.03 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 105 |
| geo | 74 |
| cn-block | 20 |
| 204 | 14 |
| sing-box exited 1 | 1 |
