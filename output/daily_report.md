# AutoNodes 每日报告

生成时间：2026-10-16 20:36:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99390 |
| 去重后节点数 | 27653 |
| TCP 可达数 | 3000 |
| 真测通过数 | 397 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27653 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 90.1 |
| geo | 1.5 |
| probe | 252.9 |
| real_test | 253.9 |
| tcp | 48.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 58 | 23 | 35 | 39.7% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 146 | 126 | 20 | 86.3% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 37 | 31 | 6 | 83.8% |
| vless | 293 | 202 | 91 | 68.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 38 |
| 204:TimeoutError | 38 |
| speed:ClientOSError | 16 |
| speed:TimeoutError | 16 |
| cn-block:TimeoutError | 15 |
| 204:ClientOSError | 6 |
| geo:TimeoutError | 6 |
| 204:ProxyConnectionError | 5 |
| geo:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 1 |
| geo:parse | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6644 |
| ConnectionRefusedError | 1084 |
| gaierror | 294 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.859 | prefer | 460 | 0.78 | 1995 |
| mheidari-all | 0.538 | observe | 22 | 0.455 | 23910 |
| ermaozi | 0.415 | observe | 57 | 0.386 | 618 |
| Surfboard-tg-mixed | 0.4 | observe | 4 | 0.75 | 7222 |
| ermaozi-get_subscribe | 0.274 | observe | 1 | 1.0 | 484 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 88 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7598 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| ermaozi | 0.386 | 22 | 35 | 57 |
| mheidari-all | 0.455 | 10 | 12 | 22 |
| Surfboard-tg-mixed | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.78 | 359 | 101 | 460 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23910 | yes | 6.02 | 0 |
| SoliSpirit-all | 10077 | yes | 3.73 | 0 |
| Epodonios-all | 7598 | yes | 6.39 | 0 |
| Surfboard-tg-mixed | 7222 | yes | 4.0 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.28 | 0 |
| barry-far-vless | 5818 | yes | 1.58 | 0 |
| Surfboard-tg-vless | 5648 | yes | 4.18 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 2.09 | 0 |
| DeltaKronecker-all | 4946 | yes | 6.47 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 2.9 | 0 |

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
| 204 | 87 |
| speed | 32 |
| cn-block | 21 |
| geo | 13 |
