# AutoNodes 每日报告

生成时间：2026-09-02 15:55:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 82533 |
| 去重后节点数 | 23511 |
| TCP 可达数 | 3000 |
| 真测通过数 | 590 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23511 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.7 |
| generate | 31.1 |
| geo | 1.5 |
| probe | 67.4 |
| real_test | 119.9 |
| tcp | 38.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 159 | 149 | 10 | 93.7% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 25 | 17 | 8 | 68.0% |
| vless | 462 | 381 | 81 | 82.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 21 |
| 204:TimeoutError | 17 |
| geo:ClientOSError | 16 |
| cn-block:ClientOSError | 14 |
| speed:TimeoutError | 8 |
| speed:ClientOSError | 7 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5035 |
| ConnectionRefusedError | 918 |
| gaierror | 320 |
| OSError | 24 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | prefer | 353 | 0.909 | 1740 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| mheidari-all | 0.926 | prefer | 121 | 0.851 | 15532 |
| DeltaKronecker-all | 0.813 | prefer | 28 | 0.75 | 7295 |
| Surfboard-tg-mixed | 0.811 | prefer | 165 | 0.733 | 7112 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 103 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4765 |
| Epodonios-all | 0.255 | observe | 0 | None | 7553 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.733 | 121 | 44 | 165 |
| DeltaKronecker-all | 0.75 | 21 | 7 | 28 |
| mheidari-all | 0.851 | 103 | 18 | 121 |
| Au1rxx-base64 | 0.909 | 321 | 32 | 353 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15532 | yes | 2.52 | 0 |
| SoliSpirit-all | 7750 | yes | 1.89 | 0 |
| Epodonios-all | 7553 | yes | 2.66 | 0 |
| DeltaKronecker-all | 7295 | yes | 2.98 | 0 |
| Surfboard-tg-mixed | 7112 | yes | 3.15 | 0 |
| barry-far-vless | 6200 | yes | 2.09 | 0 |
| Surfboard-tg-vless | 5992 | yes | 1.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 4765 | yes | 1.27 | 0 |
| mahdibland-V2RayAggregator | 4066 | yes | 0.89 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.14 | 0 |

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
| cn-block | 38 |
| 204 | 29 |
| geo | 21 |
| speed | 15 |
