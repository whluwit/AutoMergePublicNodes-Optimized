# AutoNodes 每日报告

生成时间：2026-07-21 08:24:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 81681 |
| 去重后节点数 | 22850 |
| TCP 可达数 | 3000 |
| 真测通过数 | 524 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22850 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.8 |
| generate | 28.2 |
| geo | 1.3 |
| probe | 62.0 |
| real_test | 139.5 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 133 | 106 | 27 | 79.7% |
| socks | 9 | 6 | 3 | 66.7% |
| trojan | 360 | 293 | 67 | 81.4% |
| vless | 368 | 79 | 289 | 21.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 126 |
| geo:TimeoutError | 121 |
| cn-block:TimeoutError | 65 |
| geo:ClientOSError | 20 |
| 204:TimeoutError | 15 |
| speed:TimeoutError | 14 |
| 204:ProxyError | 11 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4536 |
| ConnectionRefusedError | 666 |
| gaierror | 221 |
| OSError | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.754 | prefer | 157 | 0.745 | 290 |
| Surfboard-tg-mixed | 0.697 | observe | 262 | 0.618 | 5320 |
| DeltaKronecker-all | 0.563 | observe | 230 | 0.483 | 5415 |
| mheidari-all | 0.523 | observe | 219 | 0.443 | 19339 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 4304 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4482 |
| Epodonios-all | 0.255 | observe | 0 | None | 6403 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6715 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.443 | 97 | 122 | 219 |
| DeltaKronecker-all | 0.483 | 111 | 119 | 230 |
| Surfboard-tg-mixed | 0.618 | 162 | 100 | 262 |
| Au1rxx-base64 | 0.745 | 117 | 40 | 157 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19339 | yes | 2.68 | 0 |
| SoliSpirit-all | 6715 | yes | 1.66 | 0 |
| Epodonios-all | 6403 | yes | 0.78 | 0 |
| DeltaKronecker-all | 5415 | yes | 2.92 | 0 |
| Surfboard-tg-mixed | 5320 | yes | 2.02 | 0 |
| mahdibland-V2RayAggregator | 5247 | yes | 1.51 | 0 |
| barry-far-vless | 4688 | yes | 1.0 | 0 |
| 10ium-ScrapeCategorize-Vless | 4482 | yes | 1.13 | 0 |
| xiaoji235-airport-v2ray-all | 4304 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 4054 | yes | 1.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 142 |
| geo | 141 |
| cn-block | 73 |
| 204 | 30 |
