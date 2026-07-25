# AutoNodes 每日报告

生成时间：2026-07-25 08:06:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78504 |
| 去重后节点数 | 21833 |
| TCP 可达数 | 3000 |
| 真测通过数 | 892 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21833 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 51.1 |
| geo | 1.1 |
| probe | 68.7 |
| real_test | 196.7 |
| tcp | 30.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 29 | 7 | 80.6% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 136 | 108 | 28 | 79.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 627 | 577 | 50 | 92.0% |
| vless | 437 | 174 | 263 | 39.8% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 155 |
| speed:ClientOSError | 47 |
| cn-block:TimeoutError | 32 |
| 204:ProxyError | 26 |
| 204:TimeoutError | 24 |
| geo:ClientOSError | 21 |
| speed:TimeoutError | 15 |
| cn-block:ClientOSError | 13 |
| cn-block:ProxyError | 7 |
| speed:ProxyError | 5 |
| 204:ClientOSError | 5 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 3924 |
| ConnectionRefusedError | 688 |
| gaierror | 347 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.979 | prefer | 413 | 0.901 | 16592 |
| Au1rxx-base64 | 0.83 | prefer | 126 | 0.817 | 432 |
| zhangkai | 0.792 | prefer | 36 | 0.806 | 61 |
| Surfboard-tg-mixed | 0.679 | observe | 302 | 0.599 | 5473 |
| DeltaKronecker-all | 0.653 | observe | 359 | 0.574 | 5838 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4879 |
| Epodonios-all | 0.255 | observe | 0 | None | 6614 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6714 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4256 |

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
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.574 | 206 | 153 | 359 |
| Surfboard-tg-mixed | 0.599 | 181 | 121 | 302 |
| zhangkai | 0.806 | 29 | 7 | 36 |
| Au1rxx-base64 | 0.817 | 103 | 23 | 126 |
| mheidari-all | 0.901 | 372 | 41 | 413 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16592 | yes | 2.56 | 0 |
| SoliSpirit-all | 6714 | yes | 7.97 | 0 |
| Epodonios-all | 6614 | yes | 3.28 | 0 |
| DeltaKronecker-all | 5838 | yes | 3.4 | 0 |
| Surfboard-tg-mixed | 5473 | yes | 2.74 | 0 |
| mahdibland-V2RayAggregator | 5009 | yes | 1.61 | 0 |
| barry-far-vless | 4927 | yes | 8.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 4879 | yes | 1.45 | 0 |
| Surfboard-tg-vless | 4256 | yes | 1.95 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 1.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 177 |
| speed | 67 |
| 204 | 55 |
| cn-block | 52 |
