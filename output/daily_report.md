# AutoNodes 每日报告

生成时间：2026-08-04 14:03:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 86791 |
| 去重后节点数 | 24317 |
| TCP 可达数 | 3000 |
| 真测通过数 | 464 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24317 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 28.1 |
| geo | 1.6 |
| probe | 51.1 |
| real_test | 100.7 |
| tcp | 36.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 51 | 51 | 0 | 100.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 125 | 102 | 23 | 81.6% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 136 | 125 | 11 | 91.9% |
| vless | 260 | 167 | 93 | 64.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 25 |
| 204:TimeoutError | 21 |
| speed:TimeoutError | 20 |
| geo:ClientOSError | 17 |
| cn-block:TimeoutError | 13 |
| speed:ClientOSError | 11 |
| 204:ClientOSError | 10 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 5 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4922 |
| ConnectionRefusedError | 823 |
| gaierror | 284 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.984 | prefer | 52 | 1.0 | 72 |
| Au1rxx-base64 | 0.902 | prefer | 444 | 0.836 | 1686 |
| Surfboard-tg-mixed | 0.72 | prefer | 15 | 0.8 | 5397 |
| DeltaKronecker-all | 0.45 | observe | 12 | 0.5 | 5788 |
| mheidari-all | 0.39 | observe | 69 | 0.304 | 20302 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 58 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5251 |
| Epodonios-all | 0.255 | observe | 0 | None | 5995 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.304 | 21 | 48 | 69 |
| DeltaKronecker-all | 0.5 | 6 | 6 | 12 |
| Surfboard-tg-mixed | 0.8 | 12 | 3 | 15 |
| Au1rxx-base64 | 0.836 | 371 | 73 | 444 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 52 | 0 | 52 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20302 | yes | 4.71 | 0 |
| SoliSpirit-all | 7362 | yes | 2.55 | 0 |
| Epodonios-all | 5995 | yes | 2.88 | 0 |
| DeltaKronecker-all | 5788 | yes | 4.86 | 0 |
| Surfboard-tg-mixed | 5397 | yes | 4.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 5251 | yes | 0.85 | 0 |
| xiaoji235-airport-v2ray-all | 5127 | yes | 1.59 | 0 |
| mahdibland-V2RayAggregator | 5110 | yes | 2.54 | 0 |
| barry-far-vless | 4658 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 4315 | yes | 3.04 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 42 |
| 204 | 39 |
| speed | 32 |
| cn-block | 19 |
