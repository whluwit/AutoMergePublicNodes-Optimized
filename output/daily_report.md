# AutoNodes 每日报告

生成时间：2026-09-15 16:17:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 90723 |
| 去重后节点数 | 25700 |
| TCP 可达数 | 3000 |
| 真测通过数 | 402 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25700 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 94.6 |
| geo | 1.6 |
| probe | 267.1 |
| real_test | 250.3 |
| tcp | 43.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 41 | 32 | 9 | 78.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 164 | 150 | 14 | 91.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 6 | 6 | 0 | 100.0% |
| vless | 331 | 195 | 136 | 58.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 43 |
| geo:ClientOSError | 32 |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 14 |
| speed:ClientOSError | 11 |
| speed:TimeoutError | 8 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:TimeoutError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6189 |
| ConnectionRefusedError | 932 |
| gaierror | 316 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.927 | prefer | 280 | 0.868 | 1551 |
| Surfboard-tg-mixed | 0.805 | prefer | 67 | 0.731 | 7516 |
| ermaozi | 0.766 | prefer | 38 | 0.763 | 406 |
| mheidari-all | 0.521 | observe | 168 | 0.44 | 21913 |
| DeltaKronecker-all | 0.337 | observe | 7 | 0.429 | 5932 |
| ermaozi-get_subscribe | 0.328 | observe | 2 | 1.0 | 422 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 149 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 8076 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.429 | 3 | 4 | 7 |
| mheidari-all | 0.44 | 74 | 94 | 168 |
| Surfboard-tg-mixed | 0.731 | 49 | 18 | 67 |
| ermaozi | 0.763 | 29 | 9 | 38 |
| Au1rxx-base64 | 0.868 | 243 | 37 | 280 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21913 | yes | 3.93 | 0 |
| SoliSpirit-all | 8810 | yes | 3.39 | 0 |
| Epodonios-all | 8076 | yes | 3.5 | 0 |
| Surfboard-tg-mixed | 7516 | yes | 2.99 | 0 |
| barry-far-vless | 6401 | yes | 2.28 | 0 |
| Surfboard-tg-vless | 6065 | yes | 3.31 | 0 |
| DeltaKronecker-all | 5932 | yes | 4.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.85 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 0.93 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.71 | 0 |

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
| cn-block | 65 |
| 204 | 44 |
| geo | 35 |
| speed | 19 |
