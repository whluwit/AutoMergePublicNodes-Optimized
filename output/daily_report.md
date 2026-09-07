# AutoNodes 每日报告

生成时间：2026-09-07 17:12:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 89384 |
| 去重后节点数 | 25034 |
| TCP 可达数 | 3000 |
| 真测通过数 | 579 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25034 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 39.1 |
| geo | 1.4 |
| probe | 89.9 |
| real_test | 143.0 |
| tcp | 42.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 6 | 0 | 100.0% |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 27 | 26 | 1 | 96.3% |
| shadowsocks | 157 | 146 | 11 | 93.0% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 29 | 24 | 5 | 82.8% |
| vless | 500 | 351 | 149 | 70.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 67 |
| geo:ClientOSError | 35 |
| cn-block:ClientOSError | 19 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 5 |
| 204:ProxyError | 5 |
| geo:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 4 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 2 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5799 |
| ConnectionRefusedError | 1008 |
| gaierror | 269 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 316 | 0.953 | 1785 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.826 | prefer | 175 | 0.749 | 7406 |
| mheidari-all | 0.602 | observe | 224 | 0.522 | 21150 |
| tg-oneclickvpnkeys | 0.484 | observe | 6 | 1.0 | 181 |
| DeltaKronecker-all | 0.391 | observe | 2 | 1.0 | 6417 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4650 |
| Epodonios-all | 0.255 | observe | 0 | None | 7870 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8891 |

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
| mheidari-all | 0.522 | 117 | 107 | 224 |
| Surfboard-tg-mixed | 0.749 | 131 | 44 | 175 |
| Au1rxx-base64 | 0.953 | 301 | 15 | 316 |
| DeltaKronecker-all | 1.0 | 2 | 0 | 2 |
| tg-oneclickvpnkeys | 1.0 | 6 | 0 | 6 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21150 | yes | 4.44 | 0 |
| SoliSpirit-all | 8891 | yes | 2.48 | 0 |
| Epodonios-all | 7870 | yes | 4.76 | 0 |
| Surfboard-tg-mixed | 7406 | yes | 4.98 | 0 |
| DeltaKronecker-all | 6417 | yes | 4.94 | 0 |
| barry-far-vless | 6314 | yes | 1.91 | 0 |
| Surfboard-tg-vless | 6099 | yes | 3.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 1.72 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 0.54 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.55 | 0 |

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
| 204 | 75 |
| cn-block | 41 |
| geo | 40 |
| speed | 11 |
