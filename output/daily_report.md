# AutoNodes 每日报告

生成时间：2026-07-06 10:12:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 79123 |
| 去重后节点数 | 24389 |
| TCP 可达数 | 3000 |
| 真测通过数 | 368 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24389 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 28.3 |
| geo | 1.3 |
| probe | 45.8 |
| real_test | 84.6 |
| tcp | 30.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 129 | 110 | 19 | 85.3% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 234 | 200 | 34 | 85.5% |
| vless | 57 | 14 | 43 | 24.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 24 |
| speed:ClientOSError | 21 |
| 204:ProxyError | 11 |
| 204:ClientOSError | 9 |
| 204:TimeoutError | 9 |
| cn-block:TimeoutError | 8 |
| geo:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| cn-block:ClientOSError | 3 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4391 |
| ConnectionRefusedError | 768 |
| OSError | 158 |
| gaierror | 150 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.896 | prefer | 101 | 0.822 | 16255 |
| Au1rxx-base64 | 0.866 | prefer | 27 | 0.889 | 110 |
| DeltaKronecker-all | 0.848 | prefer | 188 | 0.771 | 8330 |
| Surfboard-tg-mixed | 0.783 | prefer | 109 | 0.706 | 5925 |
| nscl5-all | 0.377 | observe | 2 | 1.0 | 1651 |
| ermaozi | 0.256 | observe | 1 | 1.0 | 27 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4358 |
| Epodonios-all | 0.255 | observe | 0 | None | 6980 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.706 | 77 | 32 | 109 |
| DeltaKronecker-all | 0.771 | 145 | 43 | 188 |
| mheidari-all | 0.822 | 83 | 18 | 101 |
| Au1rxx-base64 | 0.889 | 24 | 3 | 27 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16255 | yes | 4.19 | 0 |
| DeltaKronecker-all | 8330 | yes | 3.49 | 0 |
| Epodonios-all | 6980 | yes | 1.65 | 0 |
| SoliSpirit-all | 6861 | yes | 2.43 | 0 |
| Surfboard-tg-mixed | 5925 | yes | 2.53 | 0 |
| mahdibland-V2RayAggregator | 5349 | yes | 1.01 | 0 |
| barry-far-vless | 5043 | yes | 2.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4358 | yes | 1.9 | 0 |
| Surfboard-tg-vless | 4334 | yes | 2.14 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.7 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 29 |
| geo | 29 |
| speed | 28 |
| cn-block | 12 |
