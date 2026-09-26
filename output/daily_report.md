# AutoNodes 每日报告

生成时间：2026-09-26 15:46:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96601 |
| 去重后节点数 | 26419 |
| TCP 可达数 | 3000 |
| 真测通过数 | 353 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26419 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 89.4 |
| geo | 1.4 |
| probe | 223.6 |
| real_test | 183.7 |
| tcp | 43.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 19 | 9 | 10 | 47.4% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 102 | 98 | 4 | 96.1% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 18 | 15 | 3 | 83.3% |
| vless | 309 | 210 | 99 | 68.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 31 |
| 204:TimeoutError | 28 |
| cn-block:TimeoutError | 18 |
| speed:TimeoutError | 12 |
| geo:TimeoutError | 12 |
| 204:ProxyError | 10 |
| speed:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| geo:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6037 |
| ConnectionRefusedError | 962 |
| gaierror | 366 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.905 | prefer | 278 | 0.842 | 1642 |
| Surfboard-tg-mixed | 0.863 | prefer | 19 | 0.842 | 7263 |
| mheidari-all | 0.69 | observe | 152 | 0.612 | 22417 |
| ermaozi | 0.439 | observe | 17 | 0.471 | 296 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7742 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8947 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5823 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| ermaozi | 0.471 | 8 | 9 | 17 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.612 | 93 | 59 | 152 |
| Surfboard-tg-mixed | 0.842 | 16 | 3 | 19 |
| Au1rxx-base64 | 0.842 | 234 | 44 | 278 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22417 | yes | 4.37 | 0 |
| SoliSpirit-all | 8947 | yes | 3.26 | 0 |
| Epodonios-all | 7742 | yes | 2.35 | 0 |
| Surfboard-tg-mixed | 7263 | yes | 2.94 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.34 | 0 |
| barry-far-vless | 6056 | yes | 0.67 | 0 |
| Surfboard-tg-vless | 5823 | yes | 2.59 | 0 |
| DeltaKronecker-all | 5512 | yes | 4.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 1.54 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 2.13 | 0 |

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
| cn-block | 50 |
| 204 | 40 |
| speed | 16 |
| geo | 14 |
