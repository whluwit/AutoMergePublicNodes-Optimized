# AutoNodes 每日报告

生成时间：2026-10-13 22:24:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 98450 |
| 去重后节点数 | 27350 |
| TCP 可达数 | 3000 |
| 真测通过数 | 476 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27350 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 70.2 |
| geo | 1.4 |
| probe | 250.7 |
| real_test | 286.1 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 4 | 0 | 100.0% |
| http | 25 | 23 | 2 | 92.0% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 150 | 138 | 12 | 92.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 80 | 79 | 1 | 98.8% |
| vless | 264 | 219 | 45 | 83.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 12 |
| cn-block:ClientOSError | 9 |
| speed:ClientOSError | 7 |
| speed:TimeoutError | 6 |
| 204:ProxyError | 3 |
| geo:ClientOSError | 3 |
| geo:TimeoutError | 2 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6900 |
| ConnectionRefusedError | 1052 |
| gaierror | 299 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.992 | prefer | 100 | 0.92 | 23973 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.965 | prefer | 362 | 0.895 | 1816 |
| Surfboard-tg-mixed | 0.785 | prefer | 42 | 0.714 | 7123 |
| ermaozi-get_subscribe | 0.362 | observe | 6 | 0.667 | 534 |
| Au1rxx-clash | 0.327 | observe | 1 | 1.0 | 1806 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 5076 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5086 |
| Epodonios-all | 0.255 | observe | 0 | None | 7631 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| ermaozi-get_subscribe | 0.667 | 4 | 2 | 6 |
| Surfboard-tg-mixed | 0.714 | 30 | 12 | 42 |
| Au1rxx-base64 | 0.895 | 324 | 38 | 362 |
| mheidari-all | 0.92 | 92 | 8 | 100 |
| Au1rxx-clash | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23973 | yes | 2.91 | 0 |
| SoliSpirit-all | 9832 | yes | 3.14 | 0 |
| Epodonios-all | 7631 | yes | 3.08 | 0 |
| Surfboard-tg-mixed | 7123 | yes | 3.31 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.74 | 0 |
| barry-far-vless | 5929 | yes | 0.88 | 0 |
| Surfboard-tg-vless | 5683 | yes | 2.03 | 0 |
| 10ium-ScrapeCategorize-Vless | 5086 | yes | 1.01 | 0 |
| DeltaKronecker-all | 5076 | yes | 2.76 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 1.7 | 0 |

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
| cn-block | 27 |
| 204 | 17 |
| speed | 15 |
| geo | 5 |
