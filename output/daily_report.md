# AutoNodes 每日报告

生成时间：2026-10-15 10:59:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99768 |
| 去重后节点数 | 27804 |
| TCP 可达数 | 3000 |
| 真测通过数 | 419 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27804 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 144.8 |
| geo | 1.5 |
| probe | 297.9 |
| real_test | 320.5 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 58 | 26 | 32 | 44.8% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 137 | 129 | 8 | 94.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 63 | 48 | 15 | 76.2% |
| vless | 322 | 200 | 122 | 62.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 40 |
| 204:ProxyError | 39 |
| cn-block:TimeoutError | 19 |
| geo:ClientOSError | 18 |
| speed:ClientOSError | 17 |
| speed:TimeoutError | 17 |
| geo:TimeoutError | 11 |
| cn-block:ClientOSError | 9 |
| 204:ProxyConnectionError | 4 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6564 |
| ConnectionRefusedError | 1082 |
| gaierror | 318 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | prefer | 447 | 0.796 | 1769 |
| ermaozi | 0.487 | observe | 59 | 0.458 | 703 |
| DeltaKronecker-all | 0.438 | observe | 79 | 0.354 | 5147 |
| mheidari-all | 0.421 | observe | 6 | 0.667 | 24005 |
| Surfboard-tg-mixed | 0.373 | observe | 5 | 0.6 | 7139 |
| ermaozi-get_subscribe | 0.279 | observe | 1 | 1.0 | 595 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Epodonios-all | 0.255 | observe | 0 | None | 7685 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10092 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.354 | 28 | 51 | 79 |
| ermaozi | 0.458 | 27 | 32 | 59 |
| Surfboard-tg-mixed | 0.6 | 3 | 2 | 5 |
| mheidari-all | 0.667 | 4 | 2 | 6 |
| Au1rxx-base64 | 0.796 | 356 | 91 | 447 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24005 | yes | 6.57 | 0 |
| SoliSpirit-all | 10092 | yes | 4.19 | 0 |
| Epodonios-all | 7685 | yes | 7.41 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 4.47 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.01 | 0 |
| barry-far-vless | 5924 | yes | 0.51 | 0 |
| Surfboard-tg-vless | 5693 | yes | 4.23 | 0 |
| DeltaKronecker-all | 5147 | yes | 6.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 1.24 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 3.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 85 |
| speed | 34 |
| cn-block | 30 |
| geo | 30 |
