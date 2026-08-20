# AutoNodes 每日报告

生成时间：2026-08-20 06:44:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 93913 |
| 去重后节点数 | 25115 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1326 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25115 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 40.7 |
| geo | 0.6 |
| probe | 74.7 |
| real_test | 260.6 |
| tcp | 37.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 179 | 169 | 10 | 94.4% |
| socks | 7 | 3 | 4 | 42.9% |
| trojan | 815 | 796 | 19 | 97.7% |
| vless | 299 | 226 | 73 | 75.6% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 39 |
| speed:TimeoutError | 16 |
| geo:ClientOSError | 14 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 7 |
| 204:TimeoutError | 5 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| 204:ProxyError | 2 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46180: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4275 |
| ConnectionRefusedError | 989 |
| gaierror | 594 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 702 | 0.984 | 1789 |
| mheidari-all | 1.0 | prefer | 333 | 0.931 | 21143 |
| zhangkai | 0.997 | prefer | 113 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.872 | prefer | 262 | 0.794 | 6395 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5974 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| Epodonios-all | 0.255 | observe | 0 | None | 7111 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3984 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7230 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5079 |

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
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.247 | 22 | 0.136 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.136 | 3 | 19 | 22 |
| Surfboard-tg-mixed | 0.794 | 208 | 54 | 262 |
| mheidari-all | 0.931 | 310 | 23 | 333 |
| Au1rxx-base64 | 0.984 | 691 | 11 | 702 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21143 | yes | 5.14 | 0 |
| SoliSpirit-all | 7230 | yes | 5.08 | 0 |
| Epodonios-all | 7111 | yes | 5.32 | 0 |
| DeltaKronecker-all | 6781 | yes | 5.62 | 0 |
| Surfboard-tg-mixed | 6395 | yes | 3.35 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.66 | 0 |
| barry-far-vless | 5404 | yes | 1.26 | 0 |
| Surfboard-tg-vless | 5079 | yes | 3.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 3.05 | 0 |
| mahdibland-V2RayAggregator | 4586 | yes | 0.4 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 53 |
| speed | 23 |
| cn-block | 21 |
| 204 | 10 |
| sing-box exited 1 | 1 |
