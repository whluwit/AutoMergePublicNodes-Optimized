# AutoNodes 每日报告

生成时间：2026-10-14 16:34:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 98095 |
| 去重后节点数 | 27247 |
| TCP 可达数 | 3000 |
| 真测通过数 | 337 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27247 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.7 |
| generate | 80.0 |
| geo | 1.4 |
| probe | 283.7 |
| real_test | 239.9 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 31 | 23 | 8 | 74.2% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 130 | 110 | 20 | 84.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 35 | 32 | 3 | 91.4% |
| vless | 231 | 161 | 70 | 69.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 29 |
| cn-block:TimeoutError | 26 |
| 204:ProxyError | 15 |
| speed:ClientOSError | 10 |
| geo:TimeoutError | 8 |
| speed:TimeoutError | 5 |
| geo:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6732 |
| ConnectionRefusedError | 1055 |
| gaierror | 366 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.862 | prefer | 294 | 0.793 | 1780 |
| mheidari-all | 0.799 | prefer | 87 | 0.724 | 23968 |
| Surfboard-tg-mixed | 0.747 | prefer | 22 | 0.682 | 7056 |
| DeltaKronecker-all | 0.373 | observe | 5 | 0.6 | 4803 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7543 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9997 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5579 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.079 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 9 | 9 |
| DeltaKronecker-all | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.682 | 15 | 7 | 22 |
| mheidari-all | 0.724 | 63 | 24 | 87 |
| Au1rxx-base64 | 0.793 | 233 | 61 | 294 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23968 | yes | 3.81 | 0 |
| SoliSpirit-all | 9997 | yes | 3.22 | 0 |
| Epodonios-all | 7543 | yes | 4.18 | 0 |
| Surfboard-tg-mixed | 7056 | yes | 2.57 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.95 | 0 |
| barry-far-vless | 5831 | yes | 1.77 | 0 |
| Surfboard-tg-vless | 5579 | yes | 2.76 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 2.15 | 0 |
| DeltaKronecker-all | 4803 | yes | 4.31 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 0.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 47 |
| cn-block | 29 |
| speed | 15 |
| geo | 13 |
