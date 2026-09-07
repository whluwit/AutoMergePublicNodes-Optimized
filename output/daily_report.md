# AutoNodes 每日报告

生成时间：2026-09-07 11:29:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 94672 |
| 去重后节点数 | 24923 |
| TCP 可达数 | 3000 |
| 真测通过数 | 475 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24923 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 42.6 |
| geo | 1.4 |
| probe | 95.5 |
| real_test | 106.6 |
| tcp | 41.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 23 | 15 | 8 | 65.2% |
| hysteria2 | 24 | 24 | 0 | 100.0% |
| shadowsocks | 158 | 141 | 17 | 89.2% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 31 | 16 | 15 | 51.6% |
| vless | 360 | 274 | 86 | 76.1% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 33 |
| 204:TimeoutError | 30 |
| 204:ProxyConnectionError | 14 |
| cn-block:TimeoutError | 12 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 7 |
| geo:TimeoutError | 7 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5129 |
| ConnectionRefusedError | 1033 |
| gaierror | 382 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | prefer | 311 | 0.926 | 1781 |
| Surfboard-tg-mixed | 0.766 | prefer | 151 | 0.689 | 7247 |
| mheidari-all | 0.646 | observe | 111 | 0.568 | 21631 |
| zhangkai | 0.646 | observe | 23 | 0.652 | 144 |
| DeltaKronecker-all | 0.4 | observe | 4 | 0.75 | 6417 |
| tg-oneclickvpnkeys | 0.275 | observe | 3 | 0.667 | 151 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4650 |
| Epodonios-all | 0.255 | observe | 0 | None | 7707 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8442 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.568 | 63 | 48 | 111 |
| zhangkai | 0.652 | 15 | 8 | 23 |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.689 | 104 | 47 | 151 |
| DeltaKronecker-all | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.926 | 288 | 23 | 311 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21631 | yes | 6.05 | 0 |
| SoliSpirit-all | 8442 | yes | 6.14 | 0 |
| Epodonios-all | 7707 | yes | 1.92 | 0 |
| Surfboard-tg-mixed | 7247 | yes | 4.44 | 0 |
| DeltaKronecker-all | 6417 | yes | 4.96 | 0 |
| barry-far-vless | 6245 | yes | 2.42 | 0 |
| Surfboard-tg-vless | 6030 | yes | 4.66 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 2.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 3.33 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 0.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 53 |
| geo | 40 |
| cn-block | 21 |
| speed | 16 |
