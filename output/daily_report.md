# AutoNodes 每日报告

生成时间：2026-08-15 06:36:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78114 |
| 去重后节点数 | 22180 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1205 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22180 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 42.6 |
| geo | 1.0 |
| probe | 80.3 |
| real_test | 259.4 |
| tcp | 33.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 126 | 1 | 99.2% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 97 | 90 | 7 | 92.8% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 558 | 542 | 16 | 97.1% |
| vless | 850 | 427 | 423 | 50.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 195 |
| geo:ClientOSError | 80 |
| speed:TimeoutError | 51 |
| speed:ClientOSError | 41 |
| cn-block:TimeoutError | 23 |
| 204:TimeoutError | 22 |
| 204:ProxyError | 20 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4550 |
| ConnectionRefusedError | 779 |
| gaierror | 306 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 814 | 0.953 | 1975 |
| zhangkai | 0.991 | prefer | 126 | 0.992 | 159 |
| Surfboard-tg-mixed | 0.965 | prefer | 24 | 0.917 | 5665 |
| DeltaKronecker-all | 0.487 | observe | 671 | 0.407 | 5773 |
| nscl5-all | 0.438 | observe | 3 | 1.0 | 2081 |
| mheidari-all | 0.314 | observe | 9 | 0.333 | 15492 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 162 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5113 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.333 | 3 | 6 | 9 |
| DeltaKronecker-all | 0.407 | 273 | 398 | 671 |
| Surfboard-tg-mixed | 0.917 | 22 | 2 | 24 |
| Au1rxx-base64 | 0.953 | 776 | 38 | 814 |
| zhangkai | 0.992 | 125 | 1 | 126 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15492 | yes | 4.36 | 0 |
| SoliSpirit-all | 7671 | yes | 4.02 | 0 |
| Epodonios-all | 6322 | yes | 3.68 | 0 |
| DeltaKronecker-all | 5773 | yes | 3.55 | 0 |
| Surfboard-tg-mixed | 5665 | yes | 3.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 5113 | yes | 3.62 | 0 |
| barry-far-vless | 4707 | yes | 2.25 | 0 |
| Surfboard-tg-vless | 4367 | yes | 3.14 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.12 | 0 |
| mahdibland-V2RayAggregator | 3935 | yes | 1.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 276 |
| speed | 93 |
| 204 | 46 |
| cn-block | 33 |
