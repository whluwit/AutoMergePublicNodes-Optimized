# AutoNodes 每日报告

生成时间：2026-10-09 22:21:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 97852 |
| 去重后节点数 | 27615 |
| TCP 可达数 | 3000 |
| 真测通过数 | 435 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27615 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 82.0 |
| geo | 1.5 |
| probe | 266.5 |
| real_test | 301.3 |
| tcp | 47.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 3 | 4 | 42.9% |
| http | 26 | 20 | 6 | 76.9% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 121 | 113 | 8 | 93.4% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 87 | 86 | 1 | 98.9% |
| vless | 244 | 198 | 46 | 81.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 22 |
| speed:ClientOSError | 10 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 8 |
| geo:ClientOSError | 4 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 3 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| geo:TimeoutError | 2 |
| 204:TimeoutError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6407 |
| ConnectionRefusedError | 1018 |
| gaierror | 435 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | prefer | 353 | 0.909 | 1805 |
| Surfboard-tg-mixed | 0.942 | prefer | 27 | 0.889 | 7025 |
| zhangkai | 0.927 | prefer | 19 | 1.0 | 144 |
| mheidari-all | 0.844 | prefer | 87 | 0.77 | 23076 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4984 |
| Epodonios-all | 0.255 | observe | 0 | None | 7582 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9986 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5553 |

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
| downweight | ermaozi-get_subscribe | 0.225 | 14 | 0.214 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.214 | 3 | 11 | 14 |
| mheidari-all | 0.77 | 67 | 20 | 87 |
| Surfboard-tg-mixed | 0.889 | 24 | 3 | 27 |
| Au1rxx-base64 | 0.909 | 321 | 32 | 353 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23076 | yes | 6.94 | 0 |
| SoliSpirit-all | 9986 | yes | 4.04 | 0 |
| Epodonios-all | 7582 | yes | 4.1 | 0 |
| Surfboard-tg-mixed | 7025 | yes | 4.86 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.33 | 0 |
| barry-far-vless | 5812 | yes | 3.62 | 0 |
| Surfboard-tg-vless | 5553 | yes | 4.62 | 0 |
| DeltaKronecker-all | 5154 | yes | 6.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 4984 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 4346 | yes | 2.3 | 0 |

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
| cn-block | 32 |
| 204 | 17 |
| speed | 14 |
| geo | 6 |
