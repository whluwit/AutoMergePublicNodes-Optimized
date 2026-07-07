# AutoNodes 每日报告

生成时间：2026-07-07 02:44:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82307 |
| 去重后节点数 | 24669 |
| TCP 可达数 | 3000 |
| 真测通过数 | 578 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24669 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 41.7 |
| geo | 1.3 |
| probe | 57.0 |
| real_test | 140.7 |
| tcp | 32.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 5 | 4 | 1 | 80.0% |
| shadowsocks | 142 | 134 | 8 | 94.4% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 138 | 131 | 7 | 94.9% |
| vless | 589 | 264 | 325 | 44.8% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 162 |
| geo:TimeoutError | 90 |
| speed:TimeoutError | 32 |
| geo:ClientOSError | 24 |
| 204:ClientOSError | 9 |
| 204:TimeoutError | 9 |
| cn-block:TimeoutError | 6 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4622 |
| ConnectionRefusedError | 812 |
| OSError | 165 |
| gaierror | 120 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.84 | prefer | 59 | 0.847 | 110 |
| Surfboard-tg-mixed | 0.723 | prefer | 399 | 0.644 | 6047 |
| DeltaKronecker-all | 0.646 | observe | 127 | 0.567 | 8330 |
| mheidari-all | 0.631 | observe | 290 | 0.552 | 16411 |
| xiaoji235-airport-v2ray-all | 0.352 | observe | 6 | 0.5 | 3626 |
| Epodonios-all | 0.255 | observe | 0 | None | 7041 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7175 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4526 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 3 | 3 | 6 |
| mheidari-all | 0.552 | 160 | 130 | 290 |
| DeltaKronecker-all | 0.567 | 72 | 55 | 127 |
| Surfboard-tg-mixed | 0.644 | 257 | 142 | 399 |
| Au1rxx-base64 | 0.847 | 50 | 9 | 59 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16411 | yes | 3.57 | 0 |
| DeltaKronecker-all | 8330 | yes | 3.76 | 0 |
| SoliSpirit-all | 7175 | yes | 2.35 | 0 |
| Epodonios-all | 7041 | yes | 1.8 | 0 |
| Surfboard-tg-mixed | 6047 | yes | 2.43 | 0 |
| mahdibland-V2RayAggregator | 5338 | yes | 0.16 | 0 |
| barry-far-vless | 5184 | yes | 1.12 | 0 |
| Surfboard-tg-vless | 4526 | yes | 2.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4358 | yes | 1.32 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 1.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 195 |
| geo | 114 |
| 204 | 22 |
| cn-block | 12 |
