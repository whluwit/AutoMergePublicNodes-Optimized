# AutoNodes 每日报告

生成时间：2026-09-14 21:31:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 89797 |
| 去重后节点数 | 25632 |
| TCP 可达数 | 3000 |
| 真测通过数 | 486 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25632 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 77.1 |
| geo | 1.4 |
| probe | 232.1 |
| real_test | 263.8 |
| tcp | 41.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 33 | 22 | 11 | 66.7% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 160 | 148 | 12 | 92.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 10 | 9 | 1 | 90.0% |
| vless | 360 | 281 | 79 | 78.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 24 |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 15 |
| 204:ProxyError | 12 |
| geo:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| speed:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5881 |
| ConnectionRefusedError | 947 |
| gaierror | 368 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | prefer | 309 | 0.906 | 1752 |
| mheidari-all | 0.875 | prefer | 71 | 0.803 | 21195 |
| DeltaKronecker-all | 0.818 | prefer | 63 | 0.746 | 5972 |
| Surfboard-tg-mixed | 0.77 | prefer | 114 | 0.693 | 7482 |
| ermaozi | 0.644 | observe | 33 | 0.636 | 393 |
| ermaozi-get_subscribe | 0.272 | observe | 1 | 1.0 | 427 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 135 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4914 |
| Epodonios-all | 0.255 | observe | 0 | None | 7941 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| ermaozi | 0.636 | 21 | 12 | 33 |
| Surfboard-tg-mixed | 0.693 | 79 | 35 | 114 |
| DeltaKronecker-all | 0.746 | 47 | 16 | 63 |
| mheidari-all | 0.803 | 57 | 14 | 71 |
| Au1rxx-base64 | 0.906 | 280 | 29 | 309 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21195 | yes | 3.65 | 0 |
| SoliSpirit-all | 8691 | yes | 2.63 | 0 |
| Epodonios-all | 7941 | yes | 4.25 | 0 |
| Surfboard-tg-mixed | 7482 | yes | 2.79 | 0 |
| barry-far-vless | 6284 | yes | 1.85 | 0 |
| Surfboard-tg-vless | 6061 | yes | 2.63 | 0 |
| DeltaKronecker-all | 5972 | yes | 3.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 2.38 | 0 |
| mahdibland-V2RayAggregator | 4099 | yes | 2.03 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.62 | 0 |

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
| geo | 35 |
| cn-block | 30 |
| 204 | 29 |
| speed | 13 |
