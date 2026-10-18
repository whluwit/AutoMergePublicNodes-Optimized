# AutoNodes 每日报告

生成时间：2026-10-18 10:28:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 98758 |
| 去重后节点数 | 27646 |
| TCP 可达数 | 3000 |
| 真测通过数 | 455 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27646 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 86.3 |
| geo | 1.4 |
| probe | 286.2 |
| real_test | 322.2 |
| tcp | 48.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 101 | 52 | 49 | 51.5% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 145 | 128 | 17 | 88.3% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 75 | 40 | 35 | 53.3% |
| vless | 300 | 214 | 86 | 71.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 60 |
| 204:ProxyError | 54 |
| cn-block:TimeoutError | 20 |
| geo:ClientOSError | 15 |
| speed:ClientOSError | 11 |
| speed:TimeoutError | 9 |
| 204:ClientOSError | 6 |
| geo:TimeoutError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7018 |
| ConnectionRefusedError | 1066 |
| gaierror | 246 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.902 | prefer | 456 | 0.827 | 1920 |
| ermaozi | 0.553 | observe | 101 | 0.525 | 710 |
| Surfboard-tg-mixed | 0.445 | observe | 50 | 0.36 | 7093 |
| mheidari-all | 0.352 | observe | 6 | 0.5 | 23769 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| Epodonios-all | 0.255 | observe | 0 | None | 7561 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10015 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5669 |
| barry-far-vless | 0.255 | observe | 0 | None | 5830 |

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
| downweight | DeltaKronecker-all | 0.213 | 28 | 0.107 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.107 | 3 | 25 | 28 |
| Surfboard-tg-mixed | 0.36 | 18 | 32 | 50 |
| tg-LonUp_M | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.5 | 3 | 3 | 6 |
| ermaozi | 0.525 | 53 | 48 | 101 |
| Au1rxx-base64 | 0.827 | 377 | 79 | 456 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23769 | yes | 2.73 | 0 |
| SoliSpirit-all | 10015 | yes | 2.63 | 0 |
| Epodonios-all | 7561 | yes | 2.88 | 0 |
| Surfboard-tg-mixed | 7093 | yes | 2.28 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.37 | 0 |
| barry-far-vless | 5830 | yes | 1.3 | 0 |
| Surfboard-tg-vless | 5669 | yes | 1.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 1.2 | 0 |
| DeltaKronecker-all | 4750 | yes | 6.69 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 1.03 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 120 |
| cn-block | 27 |
| geo | 22 |
| speed | 20 |
