# AutoNodes 每日报告

生成时间：2026-08-29 12:15:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 77950 |
| 去重后节点数 | 21150 |
| TCP 可达数 | 3000 |
| 真测通过数 | 599 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21150 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 50.2 |
| geo | 1.4 |
| probe | 59.5 |
| real_test | 135.6 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 26 | 26 | 0 | 100.0% |
| hysteria2 | 26 | 24 | 2 | 92.3% |
| shadowsocks | 166 | 150 | 16 | 90.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 28 | 23 | 5 | 82.1% |
| vless | 477 | 372 | 105 | 78.0% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 32 |
| geo:TimeoutError | 22 |
| 204:TimeoutError | 21 |
| geo:ClientOSError | 15 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 8 |
| speed:TimeoutError | 6 |
| speed:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4717 |
| ConnectionRefusedError | 840 |
| gaierror | 340 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 22 | 1.0 | 14706 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.951 | prefer | 403 | 0.881 | 1806 |
| Surfboard-tg-mixed | 0.795 | prefer | 121 | 0.719 | 6733 |
| DeltaKronecker-all | 0.783 | prefer | 153 | 0.706 | 4926 |
| tg-oneclickvpnkeys | 0.364 | observe | 3 | 1.0 | 141 |
| Au1rxx-clash | 0.328 | observe | 1 | 1.0 | 1817 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4635 |
| Epodonios-all | 0.255 | observe | 0 | None | 7153 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.706 | 108 | 45 | 153 |
| Surfboard-tg-mixed | 0.719 | 87 | 34 | 121 |
| Au1rxx-base64 | 0.881 | 355 | 48 | 403 |
| Au1rxx-clash | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |
| mheidari-all | 1.0 | 22 | 0 | 22 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14706 | yes | 4.9 | 0 |
| SoliSpirit-all | 7260 | yes | 2.81 | 0 |
| Epodonios-all | 7153 | yes | 3.22 | 0 |
| Surfboard-tg-mixed | 6733 | yes | 4.07 | 0 |
| barry-far-vless | 5723 | yes | 1.54 | 0 |
| Surfboard-tg-vless | 5530 | yes | 4.26 | 0 |
| DeltaKronecker-all | 4926 | yes | 3.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 4635 | yes | 1.37 | 0 |
| mahdibland-V2RayAggregator | 4012 | yes | 3.02 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.86 | 0 |

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
| cn-block | 43 |
| geo | 40 |
| 204 | 35 |
| speed | 11 |
