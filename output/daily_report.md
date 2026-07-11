# AutoNodes 每日报告

生成时间：2026-07-11 07:51:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 76014 |
| 去重后节点数 | 23866 |
| TCP 可达数 | 3000 |
| 真测通过数 | 355 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23866 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 29.4 |
| geo | 1.5 |
| probe | 51.9 |
| real_test | 89.8 |
| tcp | 31.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 121 | 104 | 17 | 86.0% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 247 | 185 | 62 | 74.9% |
| vless | 81 | 19 | 62 | 23.5% |
| vmess | 7 | 7 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 43 |
| speed:ClientOSError | 23 |
| 204:ProxyError | 20 |
| 204:TimeoutError | 11 |
| geo:ClientOSError | 9 |
| cn-block:ClientOSError | 9 |
| 204:ClientOSError | 9 |
| cn-block:ProxyError | 6 |
| cn-block:TimeoutError | 5 |
| geo:ProxyError | 5 |
| speed:ProxyError | 3 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4365 |
| ConnectionRefusedError | 662 |
| gaierror | 262 |
| OSError | 189 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.897 | prefer | 113 | 0.823 | 5476 |
| mheidari-all | 0.73 | prefer | 58 | 0.655 | 16299 |
| Au1rxx-base64 | 0.726 | prefer | 59 | 0.729 | 111 |
| DeltaKronecker-all | 0.703 | prefer | 229 | 0.624 | 7969 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3953 |
| Epodonios-all | 0.255 | observe | 0 | None | 6366 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6404 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.624 | 143 | 86 | 229 |
| mheidari-all | 0.655 | 38 | 20 | 58 |
| Au1rxx-base64 | 0.729 | 43 | 16 | 59 |
| Surfboard-tg-mixed | 0.823 | 93 | 20 | 113 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16299 | yes | 3.63 | 0 |
| DeltaKronecker-all | 7969 | yes | 3.76 | 0 |
| SoliSpirit-all | 6404 | yes | 2.18 | 0 |
| Epodonios-all | 6366 | yes | 1.66 | 0 |
| Surfboard-tg-mixed | 5476 | yes | 1.95 | 0 |
| mahdibland-V2RayAggregator | 5423 | yes | 1.76 | 0 |
| barry-far-vless | 4653 | yes | 1.63 | 0 |
| Surfboard-tg-vless | 4097 | yes | 2.3 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 3953 | yes | 1.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 57 |
| 204 | 40 |
| speed | 27 |
| cn-block | 20 |
