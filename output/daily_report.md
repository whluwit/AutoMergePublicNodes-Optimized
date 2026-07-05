# AutoNodes 每日报告

生成时间：2026-07-05 02:43:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78851 |
| 去重后节点数 | 23827 |
| TCP 可达数 | 3000 |
| 真测通过数 | 508 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23827 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 46.3 |
| geo | 1.3 |
| probe | 46.4 |
| real_test | 102.4 |
| tcp | 31.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 141 | 129 | 12 | 91.5% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 204 | 188 | 16 | 92.2% |
| vless | 321 | 141 | 180 | 43.9% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 106 |
| geo:TimeoutError | 41 |
| speed:TimeoutError | 16 |
| geo:ClientOSError | 15 |
| 204:ClientOSError | 9 |
| cn-block:TimeoutError | 8 |
| 204:ProxyError | 6 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| speed:ClientPayloadError | 2 |
| 204:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4448 |
| ConnectionRefusedError | 798 |
| OSError | 155 |
| gaierror | 97 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| DeltaKronecker-all | 0.856 | prefer | 208 | 0.779 | 7309 |
| Au1rxx-base64 | 0.802 | prefer | 57 | 0.807 | 127 |
| mheidari-all | 0.761 | prefer | 45 | 0.689 | 16452 |
| Surfboard-tg-mixed | 0.71 | prefer | 363 | 0.631 | 6073 |
| tg-ConfigV2rayNG | 0.319 | observe | 2 | 1.0 | 200 |
| nscl5-all | 0.308 | observe | 1 | 1.0 | 1323 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6981 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.631 | 229 | 134 | 363 |
| mheidari-all | 0.689 | 31 | 14 | 45 |
| DeltaKronecker-all | 0.779 | 162 | 46 | 208 |
| Au1rxx-base64 | 0.807 | 46 | 11 | 57 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-ConfigV2rayNG | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16452 | yes | 3.75 | 0 |
| DeltaKronecker-all | 7309 | yes | 3.87 | 0 |
| SoliSpirit-all | 6984 | yes | 1.89 | 0 |
| Epodonios-all | 6981 | yes | 1.76 | 0 |
| Surfboard-tg-mixed | 6073 | yes | 2.49 | 0 |
| mahdibland-V2RayAggregator | 5366 | yes | 1.56 | 0 |
| barry-far-vless | 5089 | yes | 1.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4579 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 4518 | yes | 2.11 | 0 |
| MatinGhanbari-all-sub | 3976 | yes | 1.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 124 |
| geo | 56 |
| 204 | 17 |
| cn-block | 12 |
