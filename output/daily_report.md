# AutoNodes 每日报告

生成时间：2026-08-16 01:07:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79369 |
| 去重后节点数 | 22340 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1142 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22340 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 36.6 |
| geo | 0.7 |
| probe | 68.9 |
| real_test | 249.8 |
| tcp | 33.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 144 | 140 | 4 | 97.2% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 623 | 610 | 13 | 97.9% |
| vless | 475 | 247 | 228 | 52.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 82 |
| speed:TimeoutError | 69 |
| geo:ClientOSError | 28 |
| cn-block:TimeoutError | 27 |
| speed:ClientOSError | 14 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 8 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4148 |
| ConnectionRefusedError | 806 |
| gaierror | 391 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 745 | 0.976 | 1996 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.838 | prefer | 184 | 0.761 | 5693 |
| mheidari-all | 0.584 | observe | 266 | 0.504 | 16315 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 2601 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5113 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 145 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1996 |
| Epodonios-all | 0.255 | observe | 0 | None | 6340 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3985 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.161 | 10 | 52 | 62 |
| mheidari-all | 0.504 | 134 | 132 | 266 |
| Surfboard-tg-mixed | 0.761 | 140 | 44 | 184 |
| Au1rxx-base64 | 0.976 | 727 | 18 | 745 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16315 | yes | 4.92 | 0 |
| SoliSpirit-all | 7319 | yes | 1.93 | 0 |
| Epodonios-all | 6340 | yes | 2.71 | 0 |
| DeltaKronecker-all | 5773 | yes | 5.08 | 0 |
| Surfboard-tg-mixed | 5693 | yes | 5.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 5113 | yes | 1.31 | 0 |
| barry-far-vless | 4782 | yes | 1.48 | 0 |
| Surfboard-tg-vless | 4439 | yes | 2.98 | 0 |
| MatinGhanbari-all-sub | 3985 | yes | 1.57 | 0 |
| mahdibland-V2RayAggregator | 3935 | yes | 2.48 | 0 |

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
| geo | 110 |
| speed | 83 |
| cn-block | 36 |
| 204 | 18 |
