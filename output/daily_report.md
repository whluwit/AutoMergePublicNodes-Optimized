# AutoNodes 每日报告

生成时间：2026-08-09 06:51:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82780 |
| 去重后节点数 | 23009 |
| TCP 可达数 | 3000 |
| 真测通过数 | 491 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23009 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 34.7 |
| geo | 1.3 |
| probe | 49.4 |
| real_test | 96.7 |
| tcp | 34.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 23 | 20 | 3 | 87.0% |
| shadowsocks | 146 | 141 | 5 | 96.6% |
| socks | 3 | 3 | 0 | 100.0% |
| trojan | 157 | 135 | 22 | 86.0% |
| vless | 305 | 168 | 137 | 55.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 56 |
| geo:ClientOSError | 22 |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 18 |
| speed:TimeoutError | 18 |
| speed:ClientOSError | 14 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4570 |
| ConnectionRefusedError | 809 |
| gaierror | 345 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 393 | 0.924 | 1640 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.761 | prefer | 114 | 0.684 | 6448 |
| mheidari-all | 0.344 | observe | 12 | 0.333 | 17626 |
| tg-oneclickvpnkeys | 0.318 | observe | 2 | 1.0 | 171 |
| DeltaKronecker-all | 0.283 | observe | 116 | 0.198 | 4998 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5505 |
| Epodonios-all | 0.255 | observe | 0 | None | 7052 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.198 | 23 | 93 | 116 |
| mheidari-all | 0.333 | 4 | 8 | 12 |
| Surfboard-tg-mixed | 0.684 | 78 | 36 | 114 |
| Au1rxx-base64 | 0.924 | 363 | 30 | 393 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17626 | yes | 4.78 | 0 |
| SoliSpirit-all | 7616 | yes | 3.89 | 0 |
| Epodonios-all | 7052 | yes | 2.83 | 0 |
| Surfboard-tg-mixed | 6448 | yes | 3.63 | 0 |
| barry-far-vless | 5569 | yes | 1.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 5505 | yes | 3.03 | 0 |
| Surfboard-tg-vless | 5252 | yes | 3.17 | 0 |
| mahdibland-V2RayAggregator | 5130 | yes | 2.49 | 0 |
| DeltaKronecker-all | 4998 | yes | 4.64 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 79 |
| speed | 34 |
| 204 | 33 |
| cn-block | 21 |
