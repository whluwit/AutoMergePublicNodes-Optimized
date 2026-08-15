# AutoNodes 每日报告

生成时间：2026-08-15 12:33:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 77476 |
| 去重后节点数 | 22389 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1032 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22389 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 12.7 |
| generate | 32.5 |
| geo | 1.0 |
| probe | 65.7 |
| real_test | 193.1 |
| tcp | 34.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 154 | 145 | 9 | 94.2% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 564 | 558 | 6 | 98.9% |
| vless | 240 | 179 | 61 | 74.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 18 |
| speed:TimeoutError | 13 |
| cn-block:TimeoutError | 12 |
| geo:ClientOSError | 11 |
| geo:TimeoutError | 9 |
| 204:ProxyError | 6 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4630 |
| ConnectionRefusedError | 801 |
| gaierror | 300 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 735 | 0.978 | 1659 |
| mheidari-all | 1.0 | prefer | 52 | 0.981 | 15977 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| DeltaKronecker-all | 0.783 | prefer | 72 | 0.708 | 5773 |
| Surfboard-tg-mixed | 0.741 | prefer | 119 | 0.664 | 5656 |
| nscl5-all | 0.438 | observe | 3 | 1.0 | 2081 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 160 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5113 |
| Epodonios-all | 0.255 | observe | 0 | None | 6303 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.664 | 79 | 40 | 119 |
| DeltaKronecker-all | 0.708 | 51 | 21 | 72 |
| Au1rxx-base64 | 0.978 | 719 | 16 | 735 |
| mheidari-all | 0.981 | 51 | 1 | 52 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15977 | yes | 5.61 | 0 |
| SoliSpirit-all | 7258 | yes | 2.05 | 0 |
| Epodonios-all | 6303 | yes | 3.61 | 0 |
| DeltaKronecker-all | 5773 | yes | 3.53 | 0 |
| Surfboard-tg-mixed | 5656 | yes | 2.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 5113 | yes | 1.08 | 0 |
| barry-far-vless | 4711 | yes | 0.81 | 0 |
| Surfboard-tg-vless | 4372 | yes | 2.97 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.89 | 0 |
| mahdibland-V2RayAggregator | 3935 | yes | 2.38 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 27 |
| geo | 20 |
| cn-block | 17 |
| speed | 15 |
