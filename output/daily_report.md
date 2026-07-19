# AutoNodes 每日报告

生成时间：2026-07-19 02:18:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 88373 |
| 去重后节点数 | 23423 |
| TCP 可达数 | 3000 |
| 真测通过数 | 950 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23423 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 27.0 |
| geo | 0.8 |
| probe | 73.5 |
| real_test | 235.4 |
| tcp | 33.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 139 | 125 | 14 | 89.9% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 662 | 642 | 20 | 97.0% |
| vless | 742 | 138 | 604 | 18.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 351 |
| geo:TimeoutError | 111 |
| geo:ClientOSError | 104 |
| speed:TimeoutError | 32 |
| cn-block:TimeoutError | 24 |
| cn-block:ClientOSError | 6 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4535 |
| ConnectionRefusedError | 679 |
| gaierror | 273 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.888 | prefer | 134 | 0.888 | 149 |
| mheidari-all | 0.701 | prefer | 850 | 0.621 | 20024 |
| Surfboard-tg-mixed | 0.697 | observe | 371 | 0.617 | 5481 |
| xiaoji235-airport-v2ray-all | 0.373 | observe | 5 | 0.6 | 4642 |
| SoliSpirit-all | 0.335 | observe | 1 | 1.0 | 6933 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| nscl5-all | 0.259 | observe | 3 | 0.333 | 2755 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4371 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.168 | 31 | 154 | 185 |
| nscl5-all | 0.333 | 1 | 2 | 3 |
| xiaoji235-airport-v2ray-all | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.617 | 229 | 142 | 371 |
| mheidari-all | 0.621 | 528 | 322 | 850 |
| Au1rxx-base64 | 0.888 | 119 | 15 | 134 |
| SoliSpirit-all | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20024 | yes | 2.98 | 0 |
| DeltaKronecker-all | 9946 | yes | 3.39 | 0 |
| SoliSpirit-all | 6933 | yes | 2.2 | 0 |
| Epodonios-all | 6663 | yes | 1.51 | 0 |
| Surfboard-tg-mixed | 5481 | yes | 2.11 | 0 |
| mahdibland-V2RayAggregator | 5340 | yes | 1.18 | 0 |
| barry-far-vless | 4859 | yes | 1.24 | 0 |
| xiaoji235-airport-v2ray-all | 4642 | yes | 0.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 4371 | yes | 1.68 | 0 |
| Surfboard-tg-vless | 4222 | yes | 1.97 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 383 |
| geo | 216 |
| cn-block | 32 |
| 204 | 10 |
