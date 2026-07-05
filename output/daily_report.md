# AutoNodes 每日报告

生成时间：2026-07-05 13:25:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 80045 |
| 去重后节点数 | 23896 |
| TCP 可达数 | 3000 |
| 真测通过数 | 374 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23896 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 33.6 |
| geo | 1.4 |
| probe | 50.8 |
| real_test | 84.9 |
| tcp | 31.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 131 | 111 | 20 | 84.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 234 | 206 | 28 | 88.0% |
| vless | 44 | 12 | 32 | 27.3% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 20 |
| geo:TimeoutError | 16 |
| 204:ClientOSError | 12 |
| 204:TimeoutError | 9 |
| cn-block:TimeoutError | 6 |
| geo:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| speed:TimeoutError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4375 |
| ConnectionRefusedError | 785 |
| OSError | 155 |
| gaierror | 138 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.937 | prefer | 117 | 0.863 | 6156 |
| DeltaKronecker-all | 0.875 | prefer | 174 | 0.799 | 7739 |
| mheidari-all | 0.858 | prefer | 97 | 0.784 | 16415 |
| Au1rxx-base64 | 0.728 | prefer | 27 | 0.741 | 109 |
| nscl5-all | 0.364 | observe | 2 | 1.0 | 1323 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4662 |
| Epodonios-all | 0.255 | observe | 0 | None | 7257 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3977 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7136 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| roosterkid-openproxylist-v2ray | 0.133 | observe | 1 | 0.0 | 0 | 150 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Au1rxx-base64 | 0.741 | 20 | 7 | 27 |
| mheidari-all | 0.784 | 76 | 21 | 97 |
| DeltaKronecker-all | 0.799 | 139 | 35 | 174 |
| Surfboard-tg-mixed | 0.863 | 101 | 16 | 117 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16415 | yes | 3.83 | 0 |
| DeltaKronecker-all | 7739 | yes | 3.75 | 0 |
| Epodonios-all | 7257 | yes | 1.68 | 0 |
| SoliSpirit-all | 7136 | yes | 2.04 | 0 |
| Surfboard-tg-mixed | 6156 | yes | 2.34 | 0 |
| mahdibland-V2RayAggregator | 5372 | yes | 1.78 | 0 |
| barry-far-vless | 5319 | yes | 1.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 4662 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 4608 | yes | 2.08 | 0 |
| MatinGhanbari-all-sub | 3977 | yes | 1.6 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 24 |
| speed | 22 |
| geo | 22 |
| cn-block | 13 |
