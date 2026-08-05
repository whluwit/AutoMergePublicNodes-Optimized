# AutoNodes 每日报告

生成时间：2026-08-05 19:27:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 87797 |
| 去重后节点数 | 24099 |
| TCP 可达数 | 3000 |
| 真测通过数 | 480 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24099 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 41.5 |
| geo | 1.4 |
| probe | 47.8 |
| real_test | 103.5 |
| tcp | 36.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 145 | 128 | 17 | 88.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 158 | 153 | 5 | 96.8% |
| vless | 239 | 156 | 83 | 65.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 34 |
| geo:ClientOSError | 20 |
| 204:ProxyError | 17 |
| 204:TimeoutError | 14 |
| speed:TimeoutError | 9 |
| cn-block:TimeoutError | 8 |
| cn-block:ClientOSError | 2 |
| speed:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4933 |
| ConnectionRefusedError | 828 |
| gaierror | 287 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.996 | prefer | 405 | 0.936 | 1563 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.639 | observe | 100 | 0.56 | 5930 |
| mheidari-all | 0.483 | observe | 60 | 0.4 | 20396 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 5316 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5260 |
| Epodonios-all | 0.255 | observe | 0 | None | 6540 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7160 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4758 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.4 | 24 | 36 | 60 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.56 | 56 | 44 | 100 |
| Au1rxx-base64 | 0.936 | 379 | 26 | 405 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20396 | yes | 4.52 | 0 |
| SoliSpirit-all | 7160 | yes | 2.97 | 0 |
| Epodonios-all | 6540 | yes | 4.77 | 0 |
| Surfboard-tg-mixed | 5930 | yes | 2.56 | 0 |
| DeltaKronecker-all | 5316 | yes | 4.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 5260 | yes | 2.6 | 0 |
| mahdibland-V2RayAggregator | 5206 | yes | 2.04 | 0 |
| barry-far-vless | 5072 | yes | 1.62 | 0 |
| Surfboard-tg-vless | 4758 | yes | 4.04 | 0 |
| xiaoji235-airport-v2ray-all | 4655 | yes | 2.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 55 |
| 204 | 31 |
| speed | 12 |
| cn-block | 11 |
