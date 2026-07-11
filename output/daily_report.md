# AutoNodes 每日报告

生成时间：2026-07-11 02:14:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 75573 |
| 去重后节点数 | 23961 |
| TCP 可达数 | 3000 |
| 真测通过数 | 495 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23961 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 32.4 |
| geo | 1.4 |
| probe | 47.1 |
| real_test | 108.0 |
| tcp | 32.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 137 | 123 | 14 | 89.8% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 134 | 132 | 2 | 98.5% |
| vless | 492 | 193 | 299 | 39.2% |
| vmess | 7 | 7 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 160 |
| geo:TimeoutError | 79 |
| speed:TimeoutError | 38 |
| geo:ClientOSError | 17 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| 204:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4297 |
| ConnectionRefusedError | 674 |
| gaierror | 308 |
| OSError | 190 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.836 | prefer | 98 | 0.837 | 149 |
| Surfboard-tg-mixed | 0.707 | prefer | 312 | 0.628 | 5480 |
| DeltaKronecker-all | 0.605 | observe | 116 | 0.526 | 7600 |
| mheidari-all | 0.56 | observe | 244 | 0.48 | 16179 |
| nscl5-all | 0.36 | observe | 2 | 1.0 | 1207 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4165 |
| Epodonios-all | 0.255 | observe | 0 | None | 6288 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6366 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| xiaoji235-airport-v2ray-all | 0.157 | observe | 2 | 0.0 | 0 | 1340 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.48 | 117 | 127 | 244 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.526 | 61 | 55 | 116 |
| Surfboard-tg-mixed | 0.628 | 196 | 116 | 312 |
| Au1rxx-base64 | 0.837 | 82 | 16 | 98 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16179 | yes | 3.43 | 0 |
| DeltaKronecker-all | 7600 | yes | 3.58 | 0 |
| SoliSpirit-all | 6366 | yes | 1.67 | 0 |
| Epodonios-all | 6288 | yes | 1.75 | 0 |
| Surfboard-tg-mixed | 5480 | yes | 2.04 | 0 |
| mahdibland-V2RayAggregator | 5415 | yes | 0.34 | 0 |
| barry-far-vless | 4570 | yes | 1.13 | 0 |
| 10ium-ScrapeCategorize-Vless | 4165 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 4087 | yes | 3.57 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 1.42 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 198 |
| geo | 97 |
| cn-block | 19 |
| 204 | 4 |
