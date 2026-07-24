# AutoNodes 每日报告

生成时间：2026-07-24 13:32:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82965 |
| 去重后节点数 | 22672 |
| TCP 可达数 | 3000 |
| 真测通过数 | 638 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22672 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 39.2 |
| geo | 1.3 |
| probe | 64.7 |
| real_test | 146.5 |
| tcp | 32.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 18 | 11 | 7 | 61.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 514 | 450 | 64 | 87.5% |
| vless | 294 | 135 | 159 | 45.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 68 |
| speed:ClientOSError | 42 |
| 204:ProxyError | 29 |
| cn-block:TimeoutError | 25 |
| geo:ClientOSError | 20 |
| 204:TimeoutError | 12 |
| cn-block:ProxyError | 11 |
| speed:TimeoutError | 9 |
| geo:ProxyError | 6 |
| speed:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4061 |
| ConnectionRefusedError | 703 |
| gaierror | 448 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.818 | prefer | 665 | 0.738 | 19570 |
| Surfboard-tg-mixed | 0.729 | prefer | 35 | 0.657 | 5218 |
| DeltaKronecker-all | 0.711 | prefer | 120 | 0.633 | 5559 |
| Au1rxx-base64 | 0.601 | observe | 9 | 1.0 | 432 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 3847 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4588 |
| Epodonios-all | 0.255 | observe | 0 | None | 6521 |
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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.633 | 76 | 44 | 120 |
| Surfboard-tg-mixed | 0.657 | 23 | 12 | 35 |
| mheidari-all | 0.738 | 491 | 174 | 665 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| Au1rxx-base64 | 1.0 | 9 | 0 | 9 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19570 | yes | 4.29 | 0 |
| SoliSpirit-all | 6965 | yes | 2.5 | 0 |
| Epodonios-all | 6521 | yes | 1.26 | 0 |
| DeltaKronecker-all | 5559 | yes | 3.54 | 0 |
| Surfboard-tg-mixed | 5218 | yes | 2.36 | 0 |
| mahdibland-V2RayAggregator | 5027 | yes | 2.01 | 0 |
| barry-far-vless | 4809 | yes | 0.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4588 | yes | 1.99 | 0 |
| Surfboard-tg-vless | 4143 | yes | 3.24 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 1.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 94 |
| speed | 55 |
| 204 | 43 |
| cn-block | 39 |
