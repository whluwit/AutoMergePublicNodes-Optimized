# AutoNodes 每日报告

生成时间：2026-09-27 16:25:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96138 |
| 去重后节点数 | 26664 |
| TCP 可达数 | 3000 |
| 真测通过数 | 373 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26664 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 90.8 |
| geo | 1.6 |
| probe | 212.4 |
| real_test | 166.7 |
| tcp | 43.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 40 | 24 | 16 | 60.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 164 | 144 | 20 | 87.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 9 | 5 | 4 | 55.6% |
| vless | 233 | 179 | 54 | 76.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 20 |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 20 |
| speed:TimeoutError | 12 |
| geo:TimeoutError | 11 |
| speed:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5525 |
| ConnectionRefusedError | 986 |
| gaierror | 441 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.89 | prefer | 309 | 0.828 | 1601 |
| Surfboard-tg-mixed | 0.884 | prefer | 44 | 0.818 | 7109 |
| mheidari-all | 0.858 | prefer | 70 | 0.786 | 22413 |
| ermaozi | 0.66 | observe | 35 | 0.657 | 289 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 5466 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7600 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9194 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5703 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.158 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| ermaozi | 0.657 | 23 | 12 | 35 |
| mheidari-all | 0.786 | 55 | 15 | 70 |
| Surfboard-tg-mixed | 0.818 | 36 | 8 | 44 |
| Au1rxx-base64 | 0.828 | 256 | 53 | 309 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22413 | yes | 6.36 | 0 |
| SoliSpirit-all | 9194 | yes | 2.76 | 0 |
| Epodonios-all | 7600 | yes | 3.45 | 0 |
| Surfboard-tg-mixed | 7109 | yes | 4.11 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.36 | 0 |
| barry-far-vless | 5938 | yes | 1.64 | 0 |
| Surfboard-tg-vless | 5703 | yes | 3.86 | 0 |
| DeltaKronecker-all | 5466 | yes | 6.44 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.43 | 0 |
| mahdibland-V2RayAggregator | 4277 | yes | 3.04 | 0 |

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
| 204 | 41 |
| cn-block | 25 |
| speed | 17 |
| geo | 14 |
