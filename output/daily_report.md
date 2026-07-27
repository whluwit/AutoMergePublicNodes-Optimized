# AutoNodes 每日报告

生成时间：2026-07-27 14:28:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 85424 |
| 去重后节点数 | 22965 |
| TCP 可达数 | 3000 |
| 真测通过数 | 873 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22965 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 41.7 |
| geo | 1.3 |
| probe | 72.7 |
| real_test | 201.1 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 4 | 0 | 100.0% |
| http | 59 | 59 | 0 | 100.0% |
| hysteria2 | 10 | 8 | 2 | 80.0% |
| shadowsocks | 153 | 134 | 19 | 87.6% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 514 | 489 | 25 | 95.1% |
| vless | 402 | 177 | 225 | 44.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 123 |
| speed:ClientOSError | 59 |
| geo:ClientOSError | 24 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 15 |
| 204:ProxyError | 12 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 8 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4204 |
| ConnectionRefusedError | 722 |
| gaierror | 351 |
| OSError | 223 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.991 | prefer | 399 | 0.935 | 1456 |
| zhangkai | 0.987 | prefer | 59 | 1.0 | 74 |
| Surfboard-tg-mixed | 0.822 | prefer | 64 | 0.75 | 5641 |
| DeltaKronecker-all | 0.808 | prefer | 101 | 0.733 | 5643 |
| mheidari-all | 0.689 | observe | 515 | 0.61 | 19227 |
| tg-oneclickvpnkeys | 0.405 | observe | 4 | 1.0 | 131 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 3959 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4831 |
| Epodonios-all | 0.255 | observe | 0 | None | 6520 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3968 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.61 | 314 | 201 | 515 |
| DeltaKronecker-all | 0.733 | 74 | 27 | 101 |
| Surfboard-tg-mixed | 0.75 | 48 | 16 | 64 |
| Au1rxx-base64 | 0.935 | 373 | 26 | 399 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 59 | 0 | 59 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19227 | yes | 4.37 | 0 |
| SoliSpirit-all | 6628 | yes | 2.46 | 0 |
| Epodonios-all | 6520 | yes | 1.65 | 0 |
| DeltaKronecker-all | 5643 | yes | 3.83 | 0 |
| Surfboard-tg-mixed | 5641 | yes | 2.36 | 0 |
| mahdibland-V2RayAggregator | 5017 | yes | 2.15 | 0 |
| barry-far-vless | 4866 | yes | 1.17 | 0 |
| 10ium-ScrapeCategorize-Vless | 4831 | yes | 1.38 | 0 |
| Surfboard-tg-vless | 4484 | yes | 3.02 | 0 |
| MatinGhanbari-all-sub | 3968 | yes | 1.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 148 |
| speed | 70 |
| 204 | 30 |
| cn-block | 26 |
