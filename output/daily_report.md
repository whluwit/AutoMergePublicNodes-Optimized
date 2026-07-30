# AutoNodes 每日报告

生成时间：2026-07-30 19:23:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78345 |
| 去重后节点数 | 22956 |
| TCP 可达数 | 3000 |
| 真测通过数 | 580 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22956 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 34.5 |
| geo | 1.4 |
| probe | 59.5 |
| real_test | 150.8 |
| tcp | 32.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 130 | 104 | 26 | 80.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 20 | 17 | 3 | 85.0% |
| vless | 522 | 334 | 188 | 64.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 50 |
| cn-block:TimeoutError | 35 |
| 204:TimeoutError | 31 |
| 204:ProxyError | 25 |
| geo:ClientOSError | 19 |
| speed:TimeoutError | 17 |
| cn-block:ProxyError | 14 |
| speed:ClientOSError | 11 |
| speed:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42160: bind: address already in use | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4401 |
| ConnectionRefusedError | 753 |
| gaierror | 298 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | prefer | 113 | 1.0 | 129 |
| Au1rxx-base64 | 0.866 | prefer | 270 | 0.811 | 1430 |
| Surfboard-tg-mixed | 0.677 | observe | 117 | 0.598 | 5345 |
| DeltaKronecker-all | 0.674 | observe | 291 | 0.595 | 5759 |
| mheidari-all | 0.373 | observe | 5 | 0.6 | 16222 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5342 |
| Epodonios-all | 0.255 | observe | 0 | None | 6090 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.595 | 173 | 118 | 291 |
| Surfboard-tg-mixed | 0.598 | 70 | 47 | 117 |
| mheidari-all | 0.6 | 3 | 2 | 5 |
| Au1rxx-base64 | 0.811 | 219 | 51 | 270 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16222 | yes | 4.61 | 0 |
| SoliSpirit-all | 6594 | yes | 2.58 | 0 |
| Epodonios-all | 6090 | yes | 3.38 | 0 |
| DeltaKronecker-all | 5759 | yes | 3.02 | 0 |
| Surfboard-tg-mixed | 5345 | yes | 2.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 5342 | yes | 1.32 | 0 |
| mahdibland-V2RayAggregator | 5047 | yes | 2.42 | 0 |
| barry-far-vless | 4589 | yes | 0.9 | 0 |
| Surfboard-tg-vless | 4215 | yes | 2.67 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 70 |
| 204 | 60 |
| cn-block | 54 |
| speed | 34 |
| sing-box exited 1 | 1 |
