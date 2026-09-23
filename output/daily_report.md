# AutoNodes 每日报告

生成时间：2026-09-23 16:08:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96963 |
| 去重后节点数 | 26519 |
| TCP 可达数 | 3000 |
| 真测通过数 | 421 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26519 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 85.0 |
| geo | 1.4 |
| probe | 283.1 |
| real_test | 181.5 |
| tcp | 43.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 38 | 27 | 11 | 71.1% |
| hysteria2 | 19 | 16 | 3 | 84.2% |
| shadowsocks | 159 | 144 | 15 | 90.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 12 | 10 | 2 | 83.3% |
| vless | 338 | 221 | 117 | 65.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 40 |
| geo:ClientOSError | 32 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 17 |
| 204:ProxyError | 14 |
| speed:TimeoutError | 9 |
| 204:ClientOSError | 6 |
| speed:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6102 |
| ConnectionRefusedError | 970 |
| gaierror | 335 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 253 | 0.925 | 1629 |
| ermaozi | 0.812 | prefer | 28 | 0.821 | 291 |
| Surfboard-tg-mixed | 0.785 | prefer | 42 | 0.714 | 7138 |
| mheidari-all | 0.631 | observe | 234 | 0.551 | 22163 |
| tg-oneclickvpnkeys | 0.405 | observe | 4 | 1.0 | 117 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5131 |
| Epodonios-all | 0.255 | observe | 0 | None | 7512 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9221 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5827 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.141 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| mheidari-all | 0.551 | 129 | 105 | 234 |
| Surfboard-tg-mixed | 0.714 | 30 | 12 | 42 |
| ermaozi | 0.821 | 23 | 5 | 28 |
| Au1rxx-base64 | 0.925 | 234 | 19 | 253 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22163 | yes | 4.21 | 0 |
| SoliSpirit-all | 9221 | yes | 2.7 | 0 |
| Epodonios-all | 7512 | yes | 5.14 | 0 |
| Surfboard-tg-mixed | 7138 | yes | 3.39 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.99 | 0 |
| DeltaKronecker-all | 6471 | yes | 3.65 | 0 |
| barry-far-vless | 6042 | yes | 0.51 | 0 |
| Surfboard-tg-vless | 5827 | yes | 2.54 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 1.38 | 0 |
| mahdibland-V2RayAggregator | 4187 | yes | 2.25 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 61 |
| geo | 38 |
| 204 | 37 |
| speed | 13 |
