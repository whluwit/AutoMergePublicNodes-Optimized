# AutoNodes 每日报告

生成时间：2026-07-04 19:07:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 79057 |
| 去重后节点数 | 23716 |
| TCP 可达数 | 3000 |
| 真测通过数 | 165 |
| verified 输出数 | 165 |
| global 输出数 | 175 |
| all 输出数 | 23716 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 43.1 |
| geo | 1.3 |
| probe | 43.4 |
| real_test | 64.3 |
| tcp | 30.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 82 | 63 | 19 | 76.8% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 71 | 33 | 38 | 46.5% |
| vless | 100 | 21 | 79 | 21.0% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 41 |
| 204:TimeoutError | 24 |
| speed:ClientOSError | 20 |
| 204:ProxyError | 16 |
| cn-block:TimeoutError | 13 |
| 204:ClientOSError | 11 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4408 |
| ConnectionRefusedError | 697 |
| OSError | 152 |
| gaierror | 142 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.715 | prefer | 36 | 0.722 | 100 |
| Surfboard-tg-mixed | 0.691 | observe | 70 | 0.614 | 6107 |
| DeltaKronecker-all | 0.452 | observe | 143 | 0.371 | 7309 |
| mheidari-all | 0.337 | observe | 13 | 0.308 | 16429 |
| tg-ConfigV2rayNG | 0.319 | observe | 2 | 1.0 | 200 |
| nscl5-all | 0.303 | observe | 1 | 1.0 | 1189 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4579 |
| Epodonios-all | 0.255 | observe | 0 | None | 6997 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3978 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.308 | 4 | 9 | 13 |
| DeltaKronecker-all | 0.371 | 53 | 90 | 143 |
| Surfboard-tg-mixed | 0.614 | 43 | 27 | 70 |
| Au1rxx-base64 | 0.722 | 26 | 10 | 36 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-ConfigV2rayNG | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16429 | yes | 3.72 | 0 |
| DeltaKronecker-all | 7309 | yes | 3.41 | 0 |
| SoliSpirit-all | 7306 | yes | 2.62 | 0 |
| Epodonios-all | 6997 | yes | 1.73 | 0 |
| Surfboard-tg-mixed | 6107 | yes | 1.55 | 0 |
| mahdibland-V2RayAggregator | 5366 | yes | 0.17 | 0 |
| barry-far-vless | 5100 | yes | 1.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 4579 | yes | 1.28 | 0 |
| Surfboard-tg-vless | 4528 | yes | 2.32 | 0 |
| MatinGhanbari-all-sub | 3978 | yes | 1.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 51 |
| geo | 43 |
| speed | 25 |
| cn-block | 19 |
