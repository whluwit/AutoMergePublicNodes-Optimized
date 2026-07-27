# AutoNodes 每日报告

生成时间：2026-07-27 09:47:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84233 |
| 去重后节点数 | 22882 |
| TCP 可达数 | 3000 |
| 真测通过数 | 882 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22882 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 45.6 |
| geo | 1.5 |
| probe | 63.8 |
| real_test | 209.5 |
| tcp | 31.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 6 | 0 | 100.0% |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 127 | 98 | 29 | 77.2% |
| socks | 26 | 18 | 8 | 69.2% |
| trojan | 590 | 542 | 48 | 91.9% |
| vless | 414 | 131 | 283 | 31.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 149 |
| speed:ClientOSError | 67 |
| geo:ClientOSError | 40 |
| 204:ProxyError | 23 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 20 |
| speed:TimeoutError | 19 |
| cn-block:ClientOSError | 9 |
| cn-block:ProxyError | 7 |
| 204:ClientOSError | 7 |
| speed:ProxyError | 4 |
| geo:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4044 |
| ConnectionRefusedError | 724 |
| gaierror | 344 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 76 | 1.0 | 86 |
| Au1rxx-base64 | 0.963 | prefer | 429 | 0.909 | 1407 |
| mheidari-all | 0.906 | prefer | 240 | 0.829 | 19339 |
| Surfboard-tg-mixed | 0.549 | observe | 192 | 0.469 | 5483 |
| tg-oneclickvpnkeys | 0.482 | observe | 6 | 1.0 | 132 |
| DeltaKronecker-all | 0.478 | observe | 302 | 0.397 | 5643 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 3959 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4831 |
| Epodonios-all | 0.255 | observe | 0 | None | 6410 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.397 | 120 | 182 | 302 |
| Surfboard-tg-mixed | 0.469 | 90 | 102 | 192 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.829 | 199 | 41 | 240 |
| Au1rxx-base64 | 0.909 | 390 | 39 | 429 |
| tg-oneclickvpnkeys | 1.0 | 6 | 0 | 6 |
| zhangkai | 1.0 | 76 | 0 | 76 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19339 | yes | 4.58 | 0 |
| Epodonios-all | 6410 | yes | 2.47 | 0 |
| SoliSpirit-all | 6188 | yes | 4.04 | 0 |
| DeltaKronecker-all | 5643 | yes | 4.78 | 0 |
| Surfboard-tg-mixed | 5483 | yes | 2.81 | 0 |
| mahdibland-V2RayAggregator | 5017 | yes | 2.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 4831 | yes | 2.52 | 0 |
| barry-far-vless | 4692 | yes | 1.4 | 0 |
| Surfboard-tg-vless | 4173 | yes | 2.95 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 2.27 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 192 |
| speed | 90 |
| 204 | 52 |
| cn-block | 36 |
