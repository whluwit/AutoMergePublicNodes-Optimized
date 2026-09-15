# AutoNodes 每日报告

生成时间：2026-09-15 20:57:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 84749 |
| 去重后节点数 | 23096 |
| TCP 可达数 | 3000 |
| 真测通过数 | 438 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23096 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 84.1 |
| geo | 1.5 |
| probe | 224.1 |
| real_test | 209.1 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 42 | 32 | 10 | 76.2% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 158 | 146 | 12 | 92.4% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 35 | 11 | 24 | 31.4% |
| vless | 298 | 232 | 66 | 77.9% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 24 |
| geo:ClientOSError | 19 |
| cn-block:TimeoutError | 18 |
| cn-block:ClientOSError | 17 |
| 204:ProxyError | 10 |
| speed:ClientOSError | 9 |
| 204:ProxyConnectionError | 7 |
| 204:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| speed:TimeoutError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4928 |
| ConnectionRefusedError | 840 |
| gaierror | 425 |
| OSError | 27 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | prefer | 303 | 0.884 | 1553 |
| DeltaKronecker-all | 0.772 | prefer | 37 | 0.703 | 5932 |
| mheidari-all | 0.765 | prefer | 52 | 0.692 | 15952 |
| ermaozi | 0.748 | prefer | 39 | 0.744 | 406 |
| Surfboard-tg-mixed | 0.713 | prefer | 118 | 0.636 | 7516 |
| ermaozi-get_subscribe | 0.328 | observe | 2 | 1.0 | 422 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 148 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 7982 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| Surfboard-tg-mixed | 0.636 | 75 | 43 | 118 |
| mheidari-all | 0.692 | 36 | 16 | 52 |
| DeltaKronecker-all | 0.703 | 26 | 11 | 37 |
| ermaozi | 0.744 | 29 | 10 | 39 |
| Au1rxx-base64 | 0.884 | 268 | 35 | 303 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15952 | yes | 4.95 | 0 |
| SoliSpirit-all | 8946 | yes | 2.11 | 0 |
| Epodonios-all | 7982 | yes | 5.49 | 0 |
| Surfboard-tg-mixed | 7516 | yes | 3.61 | 0 |
| barry-far-vless | 6289 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 6065 | yes | 3.87 | 0 |
| DeltaKronecker-all | 5932 | yes | 5.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.26 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 0.53 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.35 | 0 |

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
| 204 | 45 |
| cn-block | 35 |
| geo | 24 |
| speed | 12 |
