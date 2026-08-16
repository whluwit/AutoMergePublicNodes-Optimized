# AutoNodes 每日报告

生成时间：2026-08-16 12:35:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79014 |
| 去重后节点数 | 21913 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1111 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21913 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 30.0 |
| geo | 0.9 |
| probe | 66.2 |
| real_test | 209.1 |
| tcp | 33.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 140 | 134 | 6 | 95.7% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 613 | 609 | 4 | 99.3% |
| vless | 304 | 222 | 82 | 73.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 18 |
| speed:TimeoutError | 18 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 14 |
| 204:TimeoutError | 11 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4274 |
| ConnectionRefusedError | 805 |
| gaierror | 356 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 800 | 0.961 | 1994 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.885 | prefer | 172 | 0.808 | 16375 |
| Surfboard-tg-mixed | 0.853 | prefer | 86 | 0.779 | 5800 |
| DeltaKronecker-all | 0.444 | observe | 20 | 0.35 | 5092 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 2601 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1994 |
| Epodonios-all | 0.255 | observe | 0 | None | 6483 |

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
| DeltaKronecker-all | 0.35 | 7 | 13 | 20 |
| Surfboard-tg-mixed | 0.779 | 67 | 19 | 86 |
| mheidari-all | 0.808 | 139 | 33 | 172 |
| Au1rxx-base64 | 0.961 | 769 | 31 | 800 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16375 | yes | 3.88 | 0 |
| SoliSpirit-all | 7383 | yes | 3.91 | 0 |
| Epodonios-all | 6483 | yes | 4.31 | 0 |
| Surfboard-tg-mixed | 5800 | yes | 3.47 | 0 |
| DeltaKronecker-all | 5092 | yes | 4.18 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 3.31 | 0 |
| barry-far-vless | 4839 | yes | 2.46 | 0 |
| Surfboard-tg-vless | 4502 | yes | 3.1 | 0 |
| MatinGhanbari-all-sub | 3986 | yes | 2.52 | 0 |
| mahdibland-V2RayAggregator | 3950 | yes | 0.86 | 0 |

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
| geo | 32 |
| speed | 25 |
| cn-block | 21 |
| 204 | 18 |
