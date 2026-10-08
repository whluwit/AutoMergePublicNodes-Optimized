# AutoNodes 每日报告

生成时间：2026-10-08 12:51:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 98612 |
| 去重后节点数 | 27531 |
| TCP 可达数 | 3000 |
| 真测通过数 | 464 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27531 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 88.0 |
| geo | 1.4 |
| probe | 235.4 |
| real_test | 216.5 |
| tcp | 46.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 1 | 5 | 16.7% |
| http | 37 | 24 | 13 | 64.9% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 162 | 142 | 20 | 87.7% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 115 | 94 | 21 | 81.7% |
| vless | 247 | 181 | 66 | 73.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 28 |
| 204:ProxyError | 22 |
| 204:TimeoutError | 19 |
| geo:TimeoutError | 15 |
| speed:ClientOSError | 14 |
| geo:ClientOSError | 8 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 6 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6416 |
| ConnectionRefusedError | 1020 |
| gaierror | 356 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| mheidari-all | 0.947 | prefer | 43 | 0.884 | 23417 |
| Au1rxx-base64 | 0.929 | prefer | 345 | 0.858 | 1824 |
| Surfboard-tg-mixed | 0.752 | prefer | 126 | 0.675 | 7320 |
| DeltaKronecker-all | 0.625 | observe | 31 | 0.548 | 5197 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| ermaozi | 0.258 | observe | 1 | 1.0 | 66 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5081 |
| Epodonios-all | 0.255 | observe | 0 | None | 7669 |

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
| downweight | ermaozi-get_subscribe | 0.158 | 20 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.1 | 2 | 18 | 20 |
| DeltaKronecker-all | 0.548 | 17 | 14 | 31 |
| Surfboard-tg-mixed | 0.675 | 85 | 41 | 126 |
| Au1rxx-base64 | 0.858 | 296 | 49 | 345 |
| mheidari-all | 0.884 | 38 | 5 | 43 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23417 | yes | 5.16 | 0 |
| SoliSpirit-all | 9654 | yes | 3.09 | 0 |
| Epodonios-all | 7669 | yes | 2.48 | 0 |
| Surfboard-tg-mixed | 7320 | yes | 4.44 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.8 | 0 |
| barry-far-vless | 5968 | yes | 2.09 | 0 |
| Surfboard-tg-vless | 5776 | yes | 3.05 | 0 |
| DeltaKronecker-all | 5197 | yes | 4.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 5081 | yes | 2.26 | 0 |
| mahdibland-V2RayAggregator | 4431 | yes | 2.85 | 0 |

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
| 204 | 47 |
| cn-block | 39 |
| geo | 24 |
| speed | 18 |
