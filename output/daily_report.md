# AutoNodes 每日报告

生成时间：2026-08-25 12:42:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78304 |
| 去重后节点数 | 22373 |
| TCP 可达数 | 3000 |
| 真测通过数 | 568 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22373 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 42.8 |
| geo | 1.4 |
| probe | 56.3 |
| real_test | 118.6 |
| tcp | 36.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 28 | 28 | 0 | 100.0% |
| shadowsocks | 202 | 191 | 11 | 94.6% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 63 | 57 | 6 | 90.5% |
| vless | 361 | 267 | 94 | 74.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 36 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 14 |
| speed:TimeoutError | 13 |
| speed:ClientOSError | 10 |
| geo:ClientOSError | 9 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4778 |
| ConnectionRefusedError | 847 |
| gaierror | 365 |
| OSError | 24 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 25 | 0.96 | 14402 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.905 | prefer | 397 | 0.844 | 1581 |
| Surfboard-tg-mixed | 0.894 | prefer | 159 | 0.818 | 6506 |
| DeltaKronecker-all | 0.804 | prefer | 74 | 0.73 | 6340 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 167 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 7010 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.73 | 54 | 20 | 74 |
| Surfboard-tg-mixed | 0.818 | 130 | 29 | 159 |
| Au1rxx-base64 | 0.844 | 335 | 62 | 397 |
| mheidari-all | 0.96 | 24 | 1 | 25 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14402 | yes | 4.08 | 0 |
| SoliSpirit-all | 7084 | yes | 3.56 | 0 |
| Epodonios-all | 7010 | yes | 3.24 | 0 |
| Surfboard-tg-mixed | 6506 | yes | 3.44 | 0 |
| DeltaKronecker-all | 6340 | yes | 4.87 | 0 |
| barry-far-vless | 5577 | yes | 2.27 | 0 |
| Surfboard-tg-vless | 5298 | yes | 3.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 3.87 | 0 |
| mahdibland-V2RayAggregator | 4119 | yes | 1.23 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.76 | 0 |

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
| geo | 45 |
| 204 | 23 |
| cn-block | 23 |
| speed | 23 |
