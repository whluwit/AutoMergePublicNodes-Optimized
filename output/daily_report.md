# AutoNodes 每日报告

生成时间：2026-09-19 10:21:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87126 |
| 去重后节点数 | 25045 |
| TCP 可达数 | 3000 |
| 真测通过数 | 494 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25045 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 81.6 |
| geo | 1.4 |
| probe | 229.8 |
| real_test | 218.8 |
| tcp | 41.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 50 | 35 | 15 | 70.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 181 | 163 | 18 | 90.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 44 | 33 | 11 | 75.0% |
| vless | 342 | 246 | 96 | 71.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 20 |
| geo:TimeoutError | 20 |
| speed:ClientOSError | 19 |
| 204:ProxyError | 17 |
| geo:ClientOSError | 16 |
| speed:TimeoutError | 13 |
| cn-block:ClientOSError | 11 |
| 204:ProxyConnectionError | 5 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5853 |
| ConnectionRefusedError | 889 |
| gaierror | 360 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.914 | prefer | 308 | 0.854 | 1569 |
| mheidari-all | 0.851 | prefer | 46 | 0.783 | 19088 |
| Surfboard-tg-mixed | 0.79 | prefer | 167 | 0.713 | 7238 |
| DeltaKronecker-all | 0.695 | observe | 63 | 0.619 | 6421 |
| ermaozi | 0.687 | observe | 50 | 0.68 | 358 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| ermaozi-get_subscribe | 0.27 | observe | 1 | 1.0 | 387 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5174 |
| Epodonios-all | 0.255 | observe | 0 | None | 7699 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.619 | 39 | 24 | 63 |
| ermaozi | 0.68 | 34 | 16 | 50 |
| Surfboard-tg-mixed | 0.713 | 119 | 48 | 167 |
| mheidari-all | 0.783 | 36 | 10 | 46 |
| Au1rxx-base64 | 0.854 | 263 | 45 | 308 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19088 | yes | 5.72 | 0 |
| SoliSpirit-all | 8837 | yes | 2.82 | 0 |
| Epodonios-all | 7699 | yes | 3.37 | 0 |
| Surfboard-tg-mixed | 7238 | yes | 4.94 | 0 |
| DeltaKronecker-all | 6421 | yes | 4.63 | 0 |
| barry-far-vless | 5996 | yes | 1.07 | 0 |
| Surfboard-tg-vless | 5783 | yes | 4.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 0.72 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 3.09 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.82 | 0 |

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
| 204 | 42 |
| geo | 36 |
| cn-block | 34 |
| speed | 32 |
