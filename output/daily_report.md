# AutoNodes 每日报告

生成时间：2026-10-17 15:03:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99144 |
| 去重后节点数 | 27584 |
| TCP 可达数 | 3000 |
| 真测通过数 | 432 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27584 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 85.1 |
| geo | 1.4 |
| probe | 294.8 |
| real_test | 322.7 |
| tcp | 48.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 23 | 18 | 5 | 78.3% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 152 | 140 | 12 | 92.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 40 | 29 | 11 | 72.5% |
| vless | 319 | 228 | 91 | 71.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 28 |
| 204:TimeoutError | 19 |
| 204:ProxyError | 15 |
| speed:ClientOSError | 14 |
| speed:TimeoutError | 12 |
| geo:TimeoutError | 9 |
| geo:ClientOSError | 8 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7112 |
| ConnectionRefusedError | 1033 |
| OSError | 236 |
| gaierror | 201 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.898 | prefer | 471 | 0.82 | 1993 |
| ermaozi | 0.817 | prefer | 22 | 0.818 | 623 |
| mheidari-all | 0.613 | observe | 43 | 0.535 | 23770 |
| Surfboard-tg-mixed | 0.361 | observe | 10 | 0.4 | 7171 |
| ermaozi-get_subscribe | 0.275 | observe | 1 | 1.0 | 510 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1993 |
| Epodonios-all | 0.255 | observe | 0 | None | 7678 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9904 |

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
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| Surfboard-tg-mixed | 0.4 | 4 | 6 | 10 |
| mheidari-all | 0.535 | 23 | 20 | 43 |
| ermaozi | 0.818 | 18 | 4 | 22 |
| Au1rxx-base64 | 0.82 | 386 | 85 | 471 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23770 | yes | 3.32 | 0 |
| SoliSpirit-all | 9904 | yes | 1.94 | 0 |
| Epodonios-all | 7678 | yes | 3.42 | 0 |
| Surfboard-tg-mixed | 7171 | yes | 3.54 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.69 | 0 |
| barry-far-vless | 5865 | yes | 2.83 | 0 |
| Surfboard-tg-vless | 5617 | yes | 2.29 | 0 |
| DeltaKronecker-all | 4999 | yes | 4.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 1.2 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 1.01 | 0 |

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
| 204 | 40 |
| cn-block | 36 |
| speed | 26 |
| geo | 19 |
