# AutoNodes 每日报告

生成时间：2026-10-21 21:19:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96058 |
| 去重后节点数 | 26884 |
| TCP 可达数 | 3000 |
| 真测通过数 | 365 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26884 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 82.8 |
| geo | 1.5 |
| probe | 235.4 |
| real_test | 197.1 |
| tcp | 44.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 31 | 15 | 16 | 48.4% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 152 | 140 | 12 | 92.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 77 | 67 | 10 | 87.0% |
| vless | 198 | 132 | 66 | 66.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 21 |
| 204:TimeoutError | 14 |
| speed:ClientOSError | 13 |
| speed:TimeoutError | 11 |
| geo:ClientOSError | 8 |
| geo:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6588 |
| ConnectionRefusedError | 1058 |
| OSError | 236 |
| gaierror | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.91 | prefer | 86 | 0.837 | 23903 |
| Au1rxx-base64 | 0.864 | prefer | 253 | 0.802 | 1598 |
| Surfboard-tg-mixed | 0.846 | prefer | 92 | 0.772 | 7007 |
| zhangkai | 0.518 | observe | 27 | 0.519 | 31 |
| DeltaKronecker-all | 0.401 | observe | 7 | 0.571 | 4067 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| Epodonios-all | 0.255 | observe | 0 | None | 7500 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10005 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5519 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 2 | 2 |
| tg-oneclickvpnkeys | 0.333 | 1 | 2 | 3 |
| zhangkai | 0.519 | 14 | 13 | 27 |
| DeltaKronecker-all | 0.571 | 4 | 3 | 7 |
| Surfboard-tg-mixed | 0.772 | 71 | 21 | 92 |
| Au1rxx-base64 | 0.802 | 203 | 50 | 253 |
| mheidari-all | 0.837 | 72 | 14 | 86 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23903 | yes | 6.18 | 0 |
| SoliSpirit-all | 10005 | yes | 6.99 | 0 |
| Epodonios-all | 7500 | yes | 5.44 | 0 |
| Surfboard-tg-mixed | 7007 | yes | 4.23 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 4.45 | 0 |
| barry-far-vless | 5734 | yes | 3.02 | 0 |
| Surfboard-tg-vless | 5519 | yes | 4.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 3.25 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 3.38 | 0 |
| DeltaKronecker-all | 4067 | yes | 6.97 | 0 |

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
| 204 | 37 |
| cn-block | 30 |
| speed | 24 |
| geo | 15 |
