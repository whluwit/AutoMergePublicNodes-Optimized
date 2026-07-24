# AutoNodes 每日报告

生成时间：2026-07-24 19:23:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83200 |
| 去重后节点数 | 22824 |
| TCP 可达数 | 3000 |
| 真测通过数 | 589 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22824 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 42.4 |
| geo | 1.0 |
| probe | 65.9 |
| real_test | 143.8 |
| tcp | 32.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 35 | 1 | 97.2% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 12 | 9 | 3 | 75.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 451 | 425 | 26 | 94.2% |
| vless | 294 | 113 | 181 | 38.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 85 |
| speed:ClientOSError | 59 |
| cn-block:TimeoutError | 30 |
| 204:TimeoutError | 13 |
| geo:ClientOSError | 10 |
| 204:ProxyError | 6 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4148 |
| ConnectionRefusedError | 706 |
| gaierror | 443 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.95 | prefer | 36 | 0.972 | 61 |
| Surfboard-tg-mixed | 0.928 | prefer | 90 | 0.856 | 5475 |
| mheidari-all | 0.788 | prefer | 583 | 0.708 | 19355 |
| DeltaKronecker-all | 0.73 | prefer | 78 | 0.654 | 5559 |
| Au1rxx-base64 | 0.636 | observe | 10 | 1.0 | 432 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 3847 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4588 |
| Epodonios-all | 0.255 | observe | 0 | None | 6668 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.654 | 51 | 27 | 78 |
| mheidari-all | 0.708 | 413 | 170 | 583 |
| Surfboard-tg-mixed | 0.856 | 77 | 13 | 90 |
| zhangkai | 0.972 | 35 | 1 | 36 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| Au1rxx-base64 | 1.0 | 10 | 0 | 10 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19355 | yes | 3.07 | 0 |
| SoliSpirit-all | 6766 | yes | 2.61 | 0 |
| Epodonios-all | 6668 | yes | 3.92 | 0 |
| DeltaKronecker-all | 5559 | yes | 2.88 | 0 |
| Surfboard-tg-mixed | 5475 | yes | 2.09 | 0 |
| mahdibland-V2RayAggregator | 5027 | yes | 1.51 | 0 |
| barry-far-vless | 4905 | yes | 1.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4588 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 4271 | yes | 2.25 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 1.35 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 96 |
| speed | 60 |
| cn-block | 35 |
| 204 | 21 |
