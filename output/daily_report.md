# AutoNodes 每日报告

生成时间：2026-08-19 18:33:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 93094 |
| 去重后节点数 | 24443 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1229 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24443 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 28.5 |
| geo | 0.7 |
| probe | 71.4 |
| real_test | 220.4 |
| tcp | 37.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 94 | 91 | 3 | 96.8% |
| socks | 9 | 6 | 3 | 66.7% |
| trojan | 795 | 788 | 7 | 99.1% |
| vless | 308 | 215 | 93 | 69.8% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 43 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 13 |
| speed:TimeoutError | 12 |
| geo:TimeoutError | 8 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:43760: bind: address already in use | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4327 |
| ConnectionRefusedError | 1007 |
| gaierror | 609 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 654 | 0.983 | 1890 |
| zhangkai | 0.988 | prefer | 113 | 0.991 | 144 |
| Surfboard-tg-mixed | 0.978 | prefer | 57 | 0.912 | 6336 |
| mheidari-all | 0.904 | prefer | 508 | 0.825 | 20423 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 3330 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 6390 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5067 |
| Epodonios-all | 0.255 | observe | 0 | None | 7060 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.825 | 419 | 89 | 508 |
| Surfboard-tg-mixed | 0.912 | 52 | 5 | 57 |
| Au1rxx-base64 | 0.983 | 643 | 11 | 654 |
| zhangkai | 0.991 | 112 | 1 | 113 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20423 | yes | 5.25 | 0 |
| SoliSpirit-all | 7318 | yes | 4.09 | 0 |
| Epodonios-all | 7060 | yes | 4.69 | 0 |
| DeltaKronecker-all | 6390 | yes | 5.47 | 0 |
| Surfboard-tg-mixed | 6336 | yes | 3.54 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 3.01 | 0 |
| barry-far-vless | 5325 | yes | 2.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 5067 | yes | 2.49 | 0 |
| Surfboard-tg-vless | 5003 | yes | 3.26 | 0 |
| mahdibland-V2RayAggregator | 4086 | yes | 1.56 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 51 |
| speed | 21 |
| 204 | 18 |
| cn-block | 18 |
| sing-box exited 1 | 1 |
