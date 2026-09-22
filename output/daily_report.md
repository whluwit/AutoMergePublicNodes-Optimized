# AutoNodes 每日报告

生成时间：2026-09-22 03:11:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 1/104 |
| 原始节点数 | 91687 |
| 去重后节点数 | 25155 |
| TCP 可达数 | 3000 |
| 真测通过数 | 546 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25155 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 16.5 |
| generate | 76.2 |
| geo | 1.4 |
| probe | 235.9 |
| real_test | 278.2 |
| tcp | 43.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 50 | 32 | 18 | 64.0% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 170 | 162 | 8 | 95.3% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 39 | 31 | 8 | 79.5% |
| vless | 593 | 300 | 293 | 50.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 76 |
| geo:TimeoutError | 60 |
| speed:TimeoutError | 48 |
| cn-block:ClientOSError | 41 |
| speed:ClientOSError | 40 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 21 |
| 204:TimeoutError | 14 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6226 |
| ConnectionRefusedError | 911 |
| OSError | 229 |
| gaierror | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.913 | prefer | 312 | 0.849 | 1657 |
| Surfboard-tg-mixed | 0.666 | observe | 254 | 0.587 | 7121 |
| ermaozi | 0.642 | observe | 49 | 0.633 | 369 |
| mheidari-all | 0.524 | observe | 212 | 0.443 | 19852 |
| 10ium-ScrapeCategorize-Vless | 0.259 | observe | 3 | 0.333 | 5290 |
| Epodonios-all | 0.255 | observe | 0 | None | 7572 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8711 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5672 |
| barry-far-vless | 0.255 | observe | 0 | None | 5888 |

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
| downweight | DeltaKronecker-all | 0.188 | 35 | 0.086 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ermaozi-get_subscribe | 0.235 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.086 | 3 | 32 | 35 |
| 10ium-ScrapeCategorize-Vless | 0.333 | 1 | 2 | 3 |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| mheidari-all | 0.443 | 94 | 118 | 212 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.587 | 149 | 105 | 254 |
| ermaozi | 0.633 | 31 | 18 | 49 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19852 | yes | 4.47 | 0 |
| SoliSpirit-all | 8711 | yes | 2.54 | 0 |
| Epodonios-all | 7572 | yes | 4.06 | 0 |
| Surfboard-tg-mixed | 7121 | yes | 2.55 | 0 |
| DeltaKronecker-all | 6181 | yes | 5.36 | 0 |
| barry-far-vless | 5888 | yes | 1.6 | 0 |
| Surfboard-tg-vless | 5672 | yes | 2.71 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 0.7 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 2.3 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 1.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 137 |
| speed | 88 |
| cn-block | 65 |
| 204 | 40 |
