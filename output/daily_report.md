# AutoNodes 每日报告

生成时间：2026-10-21 16:38:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96605 |
| 去重后节点数 | 26896 |
| TCP 可达数 | 3000 |
| 真测通过数 | 309 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26896 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 77.2 |
| geo | 1.4 |
| probe | 211.0 |
| real_test | 187.3 |
| tcp | 44.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 41 | 13 | 28 | 31.7% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 150 | 131 | 19 | 87.3% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 36 | 27 | 9 | 75.0% |
| vless | 177 | 125 | 52 | 70.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 31 |
| cn-block:TimeoutError | 21 |
| 204:TimeoutError | 18 |
| speed:TimeoutError | 9 |
| speed:ClientOSError | 8 |
| geo:ClientOSError | 6 |
| cn-block:ClientOSError | 6 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:33700: bind: address already in use | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6610 |
| ConnectionRefusedError | 1057 |
| OSError | 235 |
| gaierror | 213 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.858 | prefer | 52 | 0.788 | 7070 |
| Au1rxx-base64 | 0.853 | prefer | 236 | 0.792 | 1568 |
| mheidari-all | 0.833 | prefer | 87 | 0.759 | 24102 |
| zhangkai | 0.484 | observe | 27 | 0.481 | 31 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| Epodonios-all | 0.255 | observe | 0 | None | 7559 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10165 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5554 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.068 | 12 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.0 | 0 | 12 | 12 |
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| zhangkai | 0.481 | 13 | 14 | 27 |
| mheidari-all | 0.759 | 66 | 21 | 87 |
| Surfboard-tg-mixed | 0.788 | 41 | 11 | 52 |
| Au1rxx-base64 | 0.792 | 187 | 49 | 236 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24102 | yes | 4.76 | 0 |
| SoliSpirit-all | 10165 | yes | 3.22 | 0 |
| Epodonios-all | 7559 | yes | 3.86 | 0 |
| Surfboard-tg-mixed | 7070 | yes | 3.01 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.75 | 0 |
| barry-far-vless | 5768 | yes | 1.77 | 0 |
| Surfboard-tg-vless | 5554 | yes | 2.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 1.63 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 0.94 | 0 |
| DeltaKronecker-all | 4067 | yes | 7.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 53 |
| cn-block | 30 |
| speed | 18 |
| geo | 11 |
| sing-box exited 1 | 1 |
