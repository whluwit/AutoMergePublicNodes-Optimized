# AutoNodes 每日报告

生成时间：2026-09-15 03:24:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 90207 |
| 去重后节点数 | 25720 |
| TCP 可达数 | 3000 |
| 真测通过数 | 501 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25720 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 83.2 |
| geo | 1.5 |
| probe | 410.8 |
| real_test | 652.1 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 43 | 24 | 19 | 55.8% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 106 | 102 | 4 | 96.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 24 | 8 | 16 | 33.3% |
| vless | 933 | 343 | 590 | 36.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 251 |
| speed:TimeoutError | 100 |
| geo:ClientOSError | 84 |
| cn-block:ClientOSError | 67 |
| speed:ClientOSError | 59 |
| cn-block:TimeoutError | 29 |
| 204:ProxyError | 23 |
| 204:TimeoutError | 13 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5902 |
| ConnectionRefusedError | 954 |
| gaierror | 390 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.912 | prefer | 294 | 0.85 | 1600 |
| Surfboard-tg-mixed | 0.622 | observe | 15 | 0.667 | 7572 |
| ermaozi | 0.56 | observe | 33 | 0.545 | 425 |
| DeltaKronecker-all | 0.402 | observe | 19 | 0.316 | 5972 |
| ermaozi-get_subscribe | 0.368 | observe | 9 | 0.556 | 447 |
| mheidari-all | 0.358 | observe | 760 | 0.278 | 21540 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 120 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4914 |
| Epodonios-all | 0.255 | observe | 0 | None | 8044 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| mheidari-all | 0.278 | 211 | 549 | 760 |
| DeltaKronecker-all | 0.316 | 6 | 13 | 19 |
| ermaozi | 0.545 | 18 | 15 | 33 |
| ermaozi-get_subscribe | 0.556 | 5 | 4 | 9 |
| Surfboard-tg-mixed | 0.667 | 10 | 5 | 15 |
| Au1rxx-base64 | 0.85 | 250 | 44 | 294 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21540 | yes | 6.82 | 0 |
| SoliSpirit-all | 8768 | yes | 4.04 | 0 |
| Epodonios-all | 8044 | yes | 4.23 | 0 |
| Surfboard-tg-mixed | 7572 | yes | 5.48 | 0 |
| barry-far-vless | 6333 | yes | 3.13 | 0 |
| Surfboard-tg-vless | 6105 | yes | 5.7 | 0 |
| DeltaKronecker-all | 5972 | yes | 4.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 2.81 | 0 |
| mahdibland-V2RayAggregator | 4099 | yes | 0.6 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.91 | 0 |

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
| geo | 335 |
| speed | 160 |
| cn-block | 97 |
| 204 | 39 |
