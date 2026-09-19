# AutoNodes 每日报告

生成时间：2026-09-19 03:03:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 82231 |
| 去重后节点数 | 23232 |
| TCP 可达数 | 3000 |
| 真测通过数 | 611 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23232 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 73.7 |
| geo | 1.5 |
| probe | 273.2 |
| real_test | 362.4 |
| tcp | 39.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 60 | 41 | 19 | 68.3% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 196 | 185 | 11 | 94.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 46 | 32 | 14 | 69.6% |
| vless | 570 | 332 | 238 | 58.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 99 |
| speed:TimeoutError | 54 |
| geo:ClientOSError | 34 |
| 204:ProxyError | 24 |
| speed:ClientOSError | 24 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 13 |
| 204:TimeoutError | 10 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5682 |
| ConnectionRefusedError | 804 |
| gaierror | 224 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.943 | prefer | 326 | 0.874 | 1774 |
| Surfboard-tg-mixed | 0.769 | prefer | 262 | 0.691 | 7266 |
| ermaozi | 0.764 | prefer | 50 | 0.76 | 358 |
| mheidari-all | 0.514 | observe | 111 | 0.432 | 13937 |
| roosterkid-openproxylist-v2ray | 0.512 | observe | 10 | 0.8 | 150 |
| DeltaKronecker-all | 0.475 | observe | 112 | 0.393 | 6040 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| ermaozi-get_subscribe | 0.333 | observe | 12 | 0.417 | 387 |
| Epodonios-all | 0.255 | observe | 0 | None | 7793 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-ScrapeCategorize-Vless | 0.216 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| SoliSpirit-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.167 | 1 | 5 | 6 |
| DeltaKronecker-all | 0.393 | 44 | 68 | 112 |
| ermaozi-get_subscribe | 0.417 | 5 | 7 | 12 |
| mheidari-all | 0.432 | 48 | 63 | 111 |
| Surfboard-tg-mixed | 0.691 | 181 | 81 | 262 |
| ermaozi | 0.76 | 38 | 12 | 50 |
| roosterkid-openproxylist-v2ray | 0.8 | 8 | 2 | 10 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13937 | yes | 5.63 | 0 |
| SoliSpirit-all | 8922 | yes | 3.05 | 0 |
| Epodonios-all | 7793 | yes | 2.46 | 0 |
| Surfboard-tg-mixed | 7266 | yes | 4.34 | 0 |
| barry-far-vless | 6112 | yes | 2.33 | 0 |
| DeltaKronecker-all | 6040 | yes | 5.85 | 0 |
| Surfboard-tg-vless | 5822 | yes | 4.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 1.78 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 2.59 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 133 |
| speed | 79 |
| 204 | 39 |
| cn-block | 32 |
