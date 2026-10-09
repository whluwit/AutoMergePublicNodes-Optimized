# AutoNodes 每日报告

生成时间：2026-10-09 12:42:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 98196 |
| 去重后节点数 | 27443 |
| TCP 可达数 | 3000 |
| 真测通过数 | 445 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27443 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 82.6 |
| geo | 1.8 |
| probe | 338.0 |
| real_test | 375.7 |
| tcp | 48.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 59 | 26 | 33 | 44.1% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 153 | 140 | 13 | 91.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 124 | 104 | 20 | 83.9% |
| vless | 210 | 157 | 53 | 74.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 35 |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 20 |
| geo:ClientOSError | 12 |
| speed:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:39242: bind: address already in use | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7318 |
| ConnectionRefusedError | 979 |
| OSError | 233 |
| gaierror | 96 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.989 | prefer | 334 | 0.919 | 1810 |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| mheidari-all | 0.92 | prefer | 48 | 0.854 | 23165 |
| Surfboard-tg-mixed | 0.701 | prefer | 93 | 0.624 | 7139 |
| DeltaKronecker-all | 0.494 | observe | 27 | 0.407 | 5154 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| Epodonios-all | 0.255 | observe | 0 | None | 7541 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10038 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5578 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.195 | 39 | 0.154 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.154 | 6 | 33 | 39 |
| DeltaKronecker-all | 0.407 | 11 | 16 | 27 |
| Surfboard-tg-mixed | 0.624 | 58 | 35 | 93 |
| mheidari-all | 0.854 | 41 | 7 | 48 |
| Au1rxx-base64 | 0.919 | 307 | 27 | 334 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23165 | yes | 3.43 | 0 |
| SoliSpirit-all | 10038 | yes | 1.95 | 0 |
| Epodonios-all | 7541 | yes | 2.03 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 2.55 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.19 | 0 |
| barry-far-vless | 5830 | yes | 0.39 | 0 |
| Surfboard-tg-vless | 5578 | yes | 2.65 | 0 |
| DeltaKronecker-all | 5154 | yes | 3.98 | 0 |
| 10ium-ScrapeCategorize-Vless | 4984 | yes | 0.55 | 0 |
| mahdibland-V2RayAggregator | 4362 | yes | 1.89 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 61 |
| cn-block | 27 |
| geo | 17 |
| speed | 15 |
| sing-box exited 1 | 1 |
