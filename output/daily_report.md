# AutoNodes 每日报告

生成时间：2026-08-12 01:31:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 80666 |
| 去重后节点数 | 22917 |
| TCP 可达数 | 3000 |
| 真测通过数 | 698 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22917 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 21.6 |
| geo | 1.3 |
| probe | 61.7 |
| real_test | 172.8 |
| tcp | 33.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 26 | 25 | 1 | 96.2% |
| shadowsocks | 178 | 164 | 14 | 92.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 153 | 127 | 26 | 83.0% |
| vless | 756 | 251 | 505 | 33.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 261 |
| geo:ClientOSError | 122 |
| speed:TimeoutError | 68 |
| speed:ClientOSError | 67 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 3 |
| cn-block:TimeoutError | 2 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4161 |
| ConnectionRefusedError | 777 |
| gaierror | 405 |
| OSError | 24 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.94 | prefer | 465 | 0.875 | 1659 |
| Surfboard-tg-mixed | 0.64 | observe | 23 | 0.565 | 6013 |
| mheidari-all | 0.455 | observe | 22 | 0.364 | 16697 |
| nscl5-all | 0.328 | observe | 3 | 0.667 | 1481 |
| DeltaKronecker-all | 0.315 | observe | 599 | 0.234 | 5522 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5419 |
| Epodonios-all | 0.255 | observe | 0 | None | 6635 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7384 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.234 | 140 | 459 | 599 |
| mheidari-all | 0.364 | 8 | 14 | 22 |
| Surfboard-tg-mixed | 0.565 | 13 | 10 | 23 |
| nscl5-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.875 | 407 | 58 | 465 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16697 | yes | 4.5 | 0 |
| SoliSpirit-all | 7384 | yes | 4.34 | 0 |
| Epodonios-all | 6635 | yes | 2.78 | 0 |
| Surfboard-tg-mixed | 6013 | yes | 3.6 | 0 |
| DeltaKronecker-all | 5522 | yes | 4.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 5419 | yes | 2.42 | 0 |
| barry-far-vless | 5220 | yes | 1.57 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 2.87 | 0 |
| Surfboard-tg-vless | 4913 | yes | 3.79 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 384 |
| speed | 135 |
| 204 | 17 |
| cn-block | 11 |
