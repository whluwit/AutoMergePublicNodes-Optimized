# AutoNodes 每日报告

生成时间：2026-09-10 10:40:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 91075 |
| 去重后节点数 | 24106 |
| TCP 可达数 | 3000 |
| 真测通过数 | 467 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24106 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 84.2 |
| geo | 1.4 |
| probe | 327.2 |
| real_test | 303.2 |
| tcp | 40.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 52 | 38 | 14 | 73.1% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 153 | 142 | 11 | 92.8% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 36 | 27 | 9 | 75.0% |
| vless | 381 | 233 | 148 | 61.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 55 |
| cn-block:ClientOSError | 29 |
| 204:ProxyError | 21 |
| cn-block:TimeoutError | 21 |
| 204:TimeoutError | 19 |
| geo:TimeoutError | 13 |
| speed:ClientOSError | 11 |
| speed:TimeoutError | 9 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5688 |
| ConnectionRefusedError | 944 |
| gaierror | 420 |
| OSError | 244 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.935 | prefer | 274 | 0.872 | 1628 |
| Surfboard-tg-mixed | 0.852 | prefer | 134 | 0.776 | 7346 |
| ermaozi | 0.74 | prefer | 52 | 0.731 | 449 |
| mheidari-all | 0.557 | observe | 174 | 0.477 | 19290 |
| tg-oneclickvpnkeys | 0.264 | observe | 1 | 1.0 | 214 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7808 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8703 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.183 | 13 | 0.077 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.077 | 1 | 12 | 13 |
| mheidari-all | 0.477 | 83 | 91 | 174 |
| ermaozi | 0.731 | 38 | 14 | 52 |
| Surfboard-tg-mixed | 0.776 | 104 | 30 | 134 |
| Au1rxx-base64 | 0.872 | 239 | 35 | 274 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19290 | yes | 6.05 | 0 |
| SoliSpirit-all | 8703 | yes | 2.48 | 0 |
| Epodonios-all | 7808 | yes | 3.03 | 0 |
| Surfboard-tg-mixed | 7346 | yes | 4.69 | 0 |
| barry-far-vless | 6215 | yes | 1.64 | 0 |
| Surfboard-tg-vless | 5990 | yes | 4.24 | 0 |
| DeltaKronecker-all | 5853 | yes | 5.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 2.15 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 0.51 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.89 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 70 |
| cn-block | 52 |
| 204 | 43 |
| speed | 20 |
