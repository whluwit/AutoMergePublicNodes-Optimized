# AutoNodes 每日报告

生成时间：2026-08-17 01:04:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 80840 |
| 去重后节点数 | 22199 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1315 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22199 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 25.5 |
| geo | 0.9 |
| probe | 67.8 |
| real_test | 229.2 |
| tcp | 33.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 26 | 23 | 3 | 88.5% |
| shadowsocks | 127 | 123 | 4 | 96.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 682 | 662 | 20 | 97.1% |
| vless | 548 | 374 | 174 | 68.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 74 |
| speed:TimeoutError | 32 |
| cn-block:TimeoutError | 26 |
| geo:ClientOSError | 24 |
| speed:ClientOSError | 19 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4345 |
| ConnectionRefusedError | 806 |
| gaierror | 328 |
| OSError | 14 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 911 | 0.955 | 1994 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.84 | prefer | 169 | 0.763 | 17074 |
| Surfboard-tg-mixed | 0.814 | prefer | 242 | 0.736 | 5936 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4990 |
| nscl5-all | 0.32 | observe | 4 | 0.5 | 3043 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 129 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1994 |
| Epodonios-all | 0.255 | observe | 0 | None | 6595 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.209 | 60 | 0.117 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.117 | 7 | 53 | 60 |
| nscl5-all | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.736 | 178 | 64 | 242 |
| mheidari-all | 0.763 | 129 | 40 | 169 |
| Au1rxx-base64 | 0.955 | 870 | 41 | 911 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17074 | yes | 4.67 | 0 |
| SoliSpirit-all | 7537 | yes | 5.05 | 0 |
| Epodonios-all | 6595 | yes | 5.16 | 0 |
| Surfboard-tg-mixed | 5936 | yes | 3.79 | 0 |
| DeltaKronecker-all | 5092 | yes | 5.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 4.11 | 0 |
| barry-far-vless | 4890 | yes | 3.34 | 0 |
| Surfboard-tg-vless | 4561 | yes | 3.95 | 0 |
| mahdibland-V2RayAggregator | 4025 | yes | 2.64 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 3.43 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 98 |
| speed | 52 |
| cn-block | 34 |
| 204 | 18 |
