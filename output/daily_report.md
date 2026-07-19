# AutoNodes 每日报告

生成时间：2026-07-19 19:04:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 86063 |
| 去重后节点数 | 23799 |
| TCP 可达数 | 3000 |
| 真测通过数 | 398 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23799 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 27.5 |
| geo | 1.3 |
| probe | 64.7 |
| real_test | 130.6 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 141 | 113 | 28 | 80.1% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 231 | 173 | 58 | 74.9% |
| vless | 370 | 64 | 306 | 17.3% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 200 |
| geo:TimeoutError | 75 |
| 204:TimeoutError | 37 |
| cn-block:TimeoutError | 33 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 13 |
| 204:ClientOSError | 10 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4916 |
| ConnectionRefusedError | 661 |
| gaierror | 418 |
| OSError | 215 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.86 | prefer | 233 | 0.82 | 1082 |
| Surfboard-tg-mixed | 0.445 | observe | 176 | 0.364 | 5352 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 4642 |
| mheidari-all | 0.418 | observe | 155 | 0.335 | 19340 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 2755 |
| DeltaKronecker-all | 0.339 | observe | 183 | 0.257 | 6235 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4478 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.257 | 47 | 136 | 183 |
| mheidari-all | 0.335 | 52 | 103 | 155 |
| Surfboard-tg-mixed | 0.364 | 64 | 112 | 176 |
| Au1rxx-base64 | 0.82 | 191 | 42 | 233 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19340 | yes | 4.34 | 0 |
| SoliSpirit-all | 7035 | yes | 2.03 | 0 |
| Epodonios-all | 6712 | yes | 8.64 | 0 |
| DeltaKronecker-all | 6235 | yes | 2.39 | 0 |
| Surfboard-tg-mixed | 5352 | yes | 2.48 | 0 |
| mahdibland-V2RayAggregator | 5229 | yes | 2.27 | 0 |
| barry-far-vless | 4995 | yes | 0.92 | 0 |
| xiaoji235-airport-v2ray-all | 4642 | yes | 0.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4478 | yes | 1.69 | 0 |
| Surfboard-tg-vless | 4199 | yes | 2.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 205 |
| geo | 89 |
| 204 | 60 |
| cn-block | 40 |
