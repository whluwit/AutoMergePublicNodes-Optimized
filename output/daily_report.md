# AutoNodes 每日报告

生成时间：2026-10-20 03:19:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94696 |
| 去重后节点数 | 26184 |
| TCP 可达数 | 3000 |
| 真测通过数 | 467 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26184 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 79.1 |
| geo | 1.5 |
| probe | 243.9 |
| real_test | 318.9 |
| tcp | 44.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 34 | 16 | 68.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 156 | 146 | 10 | 93.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 66 | 59 | 7 | 89.4% |
| vless | 380 | 208 | 172 | 54.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 87 |
| geo:ClientOSError | 30 |
| 204:ProxyError | 22 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 19 |
| speed:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| 204:TimeoutError | 6 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6485 |
| ConnectionRefusedError | 1021 |
| gaierror | 274 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.964 | prefer | 84 | 0.893 | 6911 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 27 |
| Au1rxx-base64 | 0.902 | prefer | 289 | 0.848 | 1420 |
| mheidari-all | 0.533 | observe | 241 | 0.452 | 23317 |
| ermaozi-get_subscribe | 0.489 | observe | 30 | 0.467 | 510 |
| DeltaKronecker-all | 0.361 | observe | 10 | 0.4 | 3294 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| Epodonios-all | 0.255 | observe | 0 | None | 7516 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10158 |

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
| DeltaKronecker-all | 0.4 | 4 | 6 | 10 |
| mheidari-all | 0.452 | 109 | 132 | 241 |
| ermaozi-get_subscribe | 0.467 | 14 | 16 | 30 |
| Au1rxx-base64 | 0.848 | 245 | 44 | 289 |
| Surfboard-tg-mixed | 0.893 | 75 | 9 | 84 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23317 | yes | 4.45 | 0 |
| SoliSpirit-all | 10158 | yes | 3.14 | 0 |
| Epodonios-all | 7516 | yes | 4.65 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 2.98 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.41 | 0 |
| barry-far-vless | 5797 | yes | 1.77 | 0 |
| Surfboard-tg-vless | 5515 | yes | 3.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 1.92 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 0.08 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.61 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 117 |
| speed | 32 |
| 204 | 29 |
| cn-block | 29 |
