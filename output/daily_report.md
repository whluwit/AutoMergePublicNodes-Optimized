# AutoNodes 每日报告

生成时间：2026-08-07 12:57:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 82494 |
| 去重后节点数 | 23342 |
| TCP 可达数 | 3000 |
| 真测通过数 | 476 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23342 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 37.0 |
| geo | 1.4 |
| probe | 55.2 |
| real_test | 117.3 |
| tcp | 35.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 159 | 145 | 14 | 91.2% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 149 | 144 | 5 | 96.6% |
| vless | 258 | 144 | 114 | 55.8% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 40 |
| geo:TimeoutError | 27 |
| geo:ClientOSError | 17 |
| 204:TimeoutError | 16 |
| cn-block:TimeoutError | 13 |
| speed:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4911 |
| ConnectionRefusedError | 794 |
| gaierror | 242 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 343 | 0.959 | 1509 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| DeltaKronecker-all | 0.598 | observe | 226 | 0.518 | 5326 |
| mheidari-all | 0.418 | observe | 10 | 0.5 | 17690 |
| Surfboard-tg-mixed | 0.344 | observe | 12 | 0.333 | 6339 |
| nscl5-all | 0.326 | observe | 1 | 1.0 | 1772 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5282 |
| Epodonios-all | 0.255 | observe | 0 | None | 6987 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7526 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.333 | 4 | 8 | 12 |
| mheidari-all | 0.5 | 5 | 5 | 10 |
| DeltaKronecker-all | 0.518 | 117 | 109 | 226 |
| Au1rxx-base64 | 0.959 | 329 | 14 | 343 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17690 | yes | 4.18 | 0 |
| SoliSpirit-all | 7526 | yes | 4.2 | 0 |
| Epodonios-all | 6987 | yes | 4.56 | 0 |
| Surfboard-tg-mixed | 6339 | yes | 3.65 | 0 |
| barry-far-vless | 5458 | yes | 2.64 | 0 |
| DeltaKronecker-all | 5326 | yes | 5.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 5282 | yes | 2.5 | 0 |
| mahdibland-V2RayAggregator | 5247 | yes | 2.76 | 0 |
| Surfboard-tg-vless | 5136 | yes | 4.36 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.76 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 60 |
| geo | 44 |
| cn-block | 18 |
| speed | 15 |
