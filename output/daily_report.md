# AutoNodes 每日报告

生成时间：2026-07-20 08:56:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 85554 |
| 去重后节点数 | 23995 |
| TCP 可达数 | 3000 |
| 真测通过数 | 534 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23995 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.5 |
| generate | 43.0 |
| geo | 0.5 |
| probe | 65.6 |
| real_test | 223.4 |
| tcp | 32.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 128 | 113 | 15 | 88.3% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 352 | 307 | 45 | 87.2% |
| vless | 897 | 72 | 825 | 8.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 424 |
| speed:ClientOSError | 364 |
| cn-block:TimeoutError | 32 |
| speed:TimeoutError | 23 |
| geo:ClientOSError | 18 |
| cn-block:ClientOSError | 9 |
| 204:TimeoutError | 6 |
| 204:ProxyError | 6 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4421 |
| ConnectionRefusedError | 680 |
| gaierror | 540 |
| OSError | 215 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.949 | prefer | 235 | 0.911 | 1057 |
| Surfboard-tg-mixed | 0.683 | observe | 56 | 0.607 | 5183 |
| mheidari-all | 0.657 | observe | 109 | 0.578 | 20095 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5035 |
| DeltaKronecker-all | 0.27 | observe | 979 | 0.189 | 5962 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4714 |
| Epodonios-all | 0.255 | observe | 0 | None | 6441 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6852 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.189 | 185 | 794 | 979 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.578 | 63 | 46 | 109 |
| Surfboard-tg-mixed | 0.607 | 34 | 22 | 56 |
| Au1rxx-base64 | 0.911 | 214 | 21 | 235 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20095 | yes | 4.0 | 0 |
| SoliSpirit-all | 6852 | yes | 2.63 | 0 |
| Epodonios-all | 6441 | yes | 4.21 | 0 |
| DeltaKronecker-all | 5962 | yes | 3.98 | 0 |
| mahdibland-V2RayAggregator | 5193 | yes | 2.06 | 0 |
| Surfboard-tg-mixed | 5183 | yes | 2.54 | 0 |
| xiaoji235-airport-v2ray-all | 5035 | yes | 1.44 | 0 |
| barry-far-vless | 4852 | yes | 1.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 4714 | yes | 1.34 | 0 |
| Surfboard-tg-vless | 4032 | yes | 2.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.08 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 444 |
| speed | 388 |
| cn-block | 43 |
| 204 | 12 |
