# AutoNodes 每日报告

生成时间：2026-08-28 21:44:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77037 |
| 去重后节点数 | 20866 |
| TCP 可达数 | 3000 |
| 真测通过数 | 517 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 20866 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 40.3 |
| geo | 1.4 |
| probe | 53.4 |
| real_test | 110.8 |
| tcp | 34.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 28 | 0 | 100.0% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 160 | 140 | 20 | 87.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 29 | 22 | 7 | 75.9% |
| vless | 380 | 300 | 80 | 78.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 23 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 18 |
| geo:ClientOSError | 17 |
| cn-block:ClientOSError | 10 |
| 204:ClientOSError | 6 |
| speed:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| speed:TimeoutError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4630 |
| ConnectionRefusedError | 896 |
| gaierror | 437 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Au1rxx-base64 | 0.961 | prefer | 342 | 0.892 | 1776 |
| mheidari-all | 0.905 | prefer | 78 | 0.833 | 14493 |
| Surfboard-tg-mixed | 0.737 | prefer | 167 | 0.659 | 6713 |
| DeltaKronecker-all | 0.586 | observe | 10 | 0.8 | 4065 |
| tg-oneclickvpnkeys | 0.445 | observe | 5 | 1.0 | 140 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4725 |
| Epodonios-all | 0.255 | observe | 0 | None | 6861 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7878 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.659 | 110 | 57 | 167 |
| DeltaKronecker-all | 0.8 | 8 | 2 | 10 |
| mheidari-all | 0.833 | 65 | 13 | 78 |
| Au1rxx-base64 | 0.892 | 305 | 37 | 342 |
| tg-oneclickvpnkeys | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14493 | yes | 4.6 | 0 |
| SoliSpirit-all | 7878 | yes | 4.34 | 0 |
| Epodonios-all | 6861 | yes | 0.35 | 0 |
| Surfboard-tg-mixed | 6713 | yes | 4.18 | 0 |
| Surfboard-tg-vless | 5540 | yes | 3.75 | 0 |
| barry-far-vless | 5468 | yes | 2.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 4725 | yes | 2.93 | 0 |
| mahdibland-V2RayAggregator | 4081 | yes | 0.16 | 0 |
| DeltaKronecker-all | 4065 | yes | 4.94 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.73 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 47 |
| cn-block | 31 |
| geo | 23 |
| speed | 9 |
