# AutoNodes 每日报告

生成时间：2026-07-28 02:11:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 86135 |
| 去重后节点数 | 23123 |
| TCP 可达数 | 3000 |
| 真测通过数 | 964 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23123 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 21.8 |
| geo | 1.4 |
| probe | 70.0 |
| real_test | 223.8 |
| tcp | 32.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 59 | 59 | 0 | 100.0% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 164 | 159 | 5 | 97.0% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 486 | 465 | 21 | 95.7% |
| vless | 719 | 263 | 456 | 36.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 174 |
| speed:ClientOSError | 145 |
| geo:ClientOSError | 61 |
| speed:TimeoutError | 46 |
| cn-block:TimeoutError | 24 |
| 204:ClientOSError | 12 |
| 204:TimeoutError | 10 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| 204:ProxyError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4557 |
| ConnectionRefusedError | 739 |
| OSError | 222 |
| gaierror | 170 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 522 | 0.958 | 1410 |
| zhangkai | 0.987 | prefer | 59 | 1.0 | 74 |
| DeltaKronecker-all | 0.68 | observe | 158 | 0.601 | 5643 |
| mheidari-all | 0.52 | observe | 685 | 0.439 | 19690 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3959 |
| Surfboard-tg-mixed | 0.337 | observe | 13 | 0.308 | 5636 |
| MatinGhanbari-all-sub | 0.335 | observe | 1 | 1.0 | 3966 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4831 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| Surfboard-tg-mixed | 0.308 | 4 | 9 | 13 |
| mheidari-all | 0.439 | 301 | 384 | 685 |
| DeltaKronecker-all | 0.601 | 95 | 63 | 158 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.958 | 500 | 22 | 522 |
| MatinGhanbari-all-sub | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19690 | yes | 3.55 | 0 |
| Epodonios-all | 6677 | yes | 0.39 | 0 |
| SoliSpirit-all | 6491 | yes | 1.19 | 0 |
| DeltaKronecker-all | 5643 | yes | 3.77 | 0 |
| Surfboard-tg-mixed | 5636 | yes | 2.39 | 0 |
| barry-far-vless | 5025 | yes | 0.56 | 0 |
| mahdibland-V2RayAggregator | 4997 | yes | 1.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 4831 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 4515 | yes | 2.22 | 0 |
| MatinGhanbari-all-sub | 3966 | yes | 0.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 237 |
| speed | 192 |
| cn-block | 32 |
| 204 | 25 |
