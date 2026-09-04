# AutoNodes 每日报告

生成时间：2026-09-04 15:44:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 84293 |
| 去重后节点数 | 23430 |
| TCP 可达数 | 3000 |
| 真测通过数 | 579 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23430 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 40.3 |
| geo | 1.5 |
| probe | 91.2 |
| real_test | 126.7 |
| tcp | 38.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 27 | 0 | 100.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 147 | 132 | 15 | 89.8% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 37 | 24 | 13 | 64.9% |
| vless | 464 | 379 | 85 | 81.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 29 |
| 204:TimeoutError | 25 |
| geo:ClientOSError | 14 |
| cn-block:ClientOSError | 11 |
| geo:TimeoutError | 10 |
| speed:TimeoutError | 9 |
| 204:ClientOSError | 5 |
| 204:ProxyError | 5 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5618 |
| ConnectionRefusedError | 882 |
| gaierror | 245 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 351 | 0.897 | 1751 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.872 | prefer | 147 | 0.796 | 7209 |
| mheidari-all | 0.802 | prefer | 142 | 0.725 | 15927 |
| DeltaKronecker-all | 0.734 | prefer | 24 | 0.667 | 7089 |
| tg-oneclickvpnkeys | 0.481 | observe | 6 | 1.0 | 104 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4810 |
| Epodonios-all | 0.255 | observe | 0 | None | 7667 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8718 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.667 | 16 | 8 | 24 |
| mheidari-all | 0.725 | 103 | 39 | 142 |
| Surfboard-tg-mixed | 0.796 | 117 | 30 | 147 |
| Au1rxx-base64 | 0.897 | 315 | 36 | 351 |
| tg-oneclickvpnkeys | 1.0 | 6 | 0 | 6 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15927 | yes | 4.89 | 0 |
| SoliSpirit-all | 8718 | yes | 4.95 | 0 |
| Epodonios-all | 7667 | yes | 1.65 | 0 |
| Surfboard-tg-mixed | 7209 | yes | 3.85 | 0 |
| DeltaKronecker-all | 7089 | yes | 6.08 | 0 |
| barry-far-vless | 6339 | yes | 2.91 | 0 |
| Surfboard-tg-vless | 6091 | yes | 4.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4810 | yes | 5.16 | 0 |
| mahdibland-V2RayAggregator | 4123 | yes | 3.45 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.0 | 0 |

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
| cn-block | 42 |
| 204 | 35 |
| geo | 24 |
| speed | 13 |
