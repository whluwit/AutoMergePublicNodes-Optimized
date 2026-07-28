# AutoNodes 每日报告

生成时间：2026-07-28 13:58:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 86375 |
| 去重后节点数 | 23470 |
| TCP 可达数 | 3000 |
| 真测通过数 | 501 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23470 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 39.3 |
| geo | 1.4 |
| probe | 53.6 |
| real_test | 120.5 |
| tcp | 32.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 69 | 69 | 0 | 100.0% |
| hysteria2 | 11 | 9 | 2 | 81.8% |
| shadowsocks | 165 | 129 | 36 | 78.2% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 189 | 168 | 21 | 88.9% |
| vless | 227 | 123 | 104 | 54.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 38 |
| 204:ProxyError | 33 |
| geo:TimeoutError | 29 |
| geo:ClientOSError | 19 |
| speed:TimeoutError | 13 |
| speed:ClientOSError | 12 |
| cn-block:TimeoutError | 10 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4273 |
| ConnectionRefusedError | 764 |
| gaierror | 326 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 69 | 1.0 | 81 |
| DeltaKronecker-all | 0.953 | prefer | 124 | 0.879 | 5965 |
| Au1rxx-base64 | 0.877 | prefer | 211 | 0.825 | 1391 |
| Surfboard-tg-mixed | 0.694 | observe | 42 | 0.619 | 5771 |
| mheidari-all | 0.625 | observe | 209 | 0.545 | 18775 |
| tg-LonUp_M | 0.407 | observe | 4 | 1.0 | 179 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4972 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 3959 |
| tg-Farah_VPN | 0.263 | observe | 1 | 1.0 | 200 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.545 | 114 | 95 | 209 |
| Surfboard-tg-mixed | 0.619 | 26 | 16 | 42 |
| Au1rxx-base64 | 0.825 | 174 | 37 | 211 |
| DeltaKronecker-all | 0.879 | 109 | 15 | 124 |
| tg-Farah_VPN | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Pawdroid | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18775 | yes | 4.25 | 0 |
| Epodonios-all | 6785 | yes | 4.74 | 0 |
| SoliSpirit-all | 6699 | yes | 3.78 | 0 |
| DeltaKronecker-all | 5965 | yes | 5.01 | 0 |
| Surfboard-tg-mixed | 5771 | yes | 3.14 | 0 |
| barry-far-vless | 5088 | yes | 2.31 | 0 |
| mahdibland-V2RayAggregator | 4991 | yes | 1.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 4972 | yes | 2.58 | 0 |
| Surfboard-tg-vless | 4628 | yes | 2.96 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 2.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 75 |
| geo | 49 |
| speed | 26 |
| cn-block | 15 |
