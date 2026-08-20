# AutoNodes 每日报告

生成时间：2026-08-20 01:03:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 91268 |
| 去重后节点数 | 23525 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1285 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23525 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 37.9 |
| geo | 0.7 |
| probe | 76.6 |
| real_test | 226.9 |
| tcp | 37.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 111 | 1 | 99.1% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 168 | 162 | 6 | 96.4% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 724 | 711 | 13 | 98.2% |
| vless | 429 | 284 | 145 | 66.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 51 |
| speed:TimeoutError | 44 |
| geo:ClientOSError | 33 |
| cn-block:TimeoutError | 11 |
| speed:ClientOSError | 9 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5082 |
| ConnectionRefusedError | 949 |
| gaierror | 438 |
| OSError | 224 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 732 | 0.986 | 1789 |
| zhangkai | 0.988 | prefer | 113 | 0.991 | 144 |
| Surfboard-tg-mixed | 0.869 | prefer | 264 | 0.792 | 6465 |
| mheidari-all | 0.808 | prefer | 329 | 0.729 | 20672 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5974 |
| Epodonios-all | 0.255 | observe | 0 | None | 7184 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7380 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5081 |
| barry-far-vless | 0.255 | observe | 0 | None | 5402 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| nscl5-all | 0.17 | observe | 3 | 0.0 | 0 | 2418 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| nscl5-all | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.729 | 240 | 89 | 329 |
| Surfboard-tg-mixed | 0.792 | 209 | 55 | 264 |
| Au1rxx-base64 | 0.986 | 722 | 10 | 732 |
| zhangkai | 0.991 | 112 | 1 | 113 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20672 | yes | 4.03 | 0 |
| SoliSpirit-all | 7380 | yes | 3.28 | 0 |
| Epodonios-all | 7184 | yes | 5.96 | 0 |
| Surfboard-tg-mixed | 6465 | yes | 4.91 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 0.82 | 0 |
| barry-far-vless | 5402 | yes | 2.4 | 0 |
| Surfboard-tg-vless | 5081 | yes | 4.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5067 | yes | 3.96 | 0 |
| DeltaKronecker-all | 4713 | yes | 3.91 | 0 |
| mahdibland-V2RayAggregator | 4086 | yes | 0.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 84 |
| speed | 53 |
| cn-block | 17 |
| 204 | 12 |
