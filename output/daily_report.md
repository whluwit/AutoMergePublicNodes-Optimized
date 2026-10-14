# AutoNodes 每日报告

生成时间：2026-10-14 21:25:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98749 |
| 去重后节点数 | 27376 |
| TCP 可达数 | 3000 |
| 真测通过数 | 331 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27376 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 52.5 |
| generate | 92.6 |
| geo | 1.5 |
| probe | 234.7 |
| real_test | 228.4 |
| tcp | 48.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 22 | 9 | 13 | 40.9% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 136 | 127 | 9 | 93.4% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 58 | 47 | 11 | 81.0% |
| vless | 175 | 137 | 38 | 78.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyConnectionError | 22 |
| cn-block:TimeoutError | 18 |
| geo:TimeoutError | 9 |
| 204:TimeoutError | 7 |
| speed:ClientOSError | 5 |
| 204:ProxyError | 4 |
| speed:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6892 |
| ConnectionRefusedError | 1046 |
| gaierror | 332 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.971 | prefer | 44 | 0.909 | 23828 |
| Au1rxx-base64 | 0.912 | prefer | 275 | 0.844 | 1761 |
| Surfboard-tg-mixed | 0.897 | prefer | 58 | 0.828 | 7197 |
| zhangkai | 0.441 | observe | 21 | 0.429 | 144 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 4803 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7716 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10189 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5754 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| zhangkai | 0.429 | 9 | 12 | 21 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.828 | 48 | 10 | 58 |
| Au1rxx-base64 | 0.844 | 232 | 43 | 275 |
| mheidari-all | 0.909 | 40 | 4 | 44 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23828 | yes | 5.8 | 0 |
| SoliSpirit-all | 10189 | yes | 1.53 | 0 |
| Epodonios-all | 7716 | yes | 8.01 | 0 |
| Surfboard-tg-mixed | 7197 | yes | 6.43 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.95 | 0 |
| barry-far-vless | 5978 | yes | 0.98 | 0 |
| Surfboard-tg-vless | 5754 | yes | 4.13 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 0.77 | 0 |
| DeltaKronecker-all | 4803 | yes | 5.06 | 0 |
| mahdibland-V2RayAggregator | 4271 | yes | 3.68 | 0 |

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
| 204 | 34 |
| cn-block | 21 |
| speed | 9 |
| geo | 9 |
