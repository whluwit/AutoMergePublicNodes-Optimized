# AutoNodes 每日报告

生成时间：2026-08-17 06:49:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83055 |
| 去重后节点数 | 23057 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1350 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23057 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 34.1 |
| geo | 1.4 |
| probe | 75.2 |
| real_test | 246.1 |
| tcp | 34.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 140 | 132 | 8 | 94.3% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 780 | 766 | 14 | 98.2% |
| vless | 448 | 304 | 144 | 67.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 53 |
| cn-block:TimeoutError | 28 |
| speed:TimeoutError | 20 |
| 204:TimeoutError | 17 |
| geo:ClientOSError | 14 |
| speed:ClientOSError | 14 |
| 204:ClientOSError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4013 |
| ConnectionRefusedError | 807 |
| gaierror | 355 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 865 | 0.958 | 1991 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.904 | prefer | 72 | 0.833 | 5937 |
| mheidari-all | 0.896 | prefer | 395 | 0.818 | 17400 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 3043 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 150 |
| DeltaKronecker-all | 0.256 | observe | 49 | 0.163 | 6368 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1991 |
| Epodonios-all | 0.255 | observe | 0 | None | 6602 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-vless | 0.145 | downweight | 5 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.145 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 5 | 5 |
| DeltaKronecker-all | 0.163 | 8 | 41 | 49 |
| mheidari-all | 0.818 | 323 | 72 | 395 |
| Surfboard-tg-mixed | 0.833 | 60 | 12 | 72 |
| Au1rxx-base64 | 0.958 | 829 | 36 | 865 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17400 | yes | 4.94 | 0 |
| SoliSpirit-all | 7808 | yes | 3.64 | 0 |
| Epodonios-all | 6602 | yes | 5.12 | 0 |
| DeltaKronecker-all | 6368 | yes | 4.54 | 0 |
| Surfboard-tg-mixed | 5937 | yes | 4.17 | 0 |
| 10ium-ScrapeCategorize-Vless | 5085 | yes | 2.58 | 0 |
| barry-far-vless | 4994 | yes | 2.2 | 0 |
| Surfboard-tg-vless | 4658 | yes | 3.42 | 0 |
| mahdibland-V2RayAggregator | 4046 | yes | 1.46 | 0 |
| MatinGhanbari-all-sub | 3983 | yes | 2.28 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 67 |
| cn-block | 36 |
| speed | 34 |
| 204 | 30 |
