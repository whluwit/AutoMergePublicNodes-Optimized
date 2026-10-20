# AutoNodes 每日报告

生成时间：2026-10-20 16:25:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94292 |
| 去重后节点数 | 26477 |
| TCP 可达数 | 3000 |
| 真测通过数 | 318 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26477 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 22.2 |
| generate | 83.5 |
| geo | 1.4 |
| probe | 221.1 |
| real_test | 237.6 |
| tcp | 45.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 37 | 18 | 19 | 48.6% |
| hysteria2 | 12 | 10 | 2 | 83.3% |
| shadowsocks | 138 | 119 | 19 | 86.2% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 28 | 20 | 8 | 71.4% |
| vless | 221 | 149 | 72 | 67.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 31 |
| 204:ProxyError | 22 |
| 204:TimeoutError | 20 |
| speed:TimeoutError | 18 |
| speed:ClientOSError | 11 |
| geo:ClientOSError | 6 |
| 204:ClientOSError | 4 |
| geo:TimeoutError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6691 |
| ConnectionRefusedError | 1044 |
| OSError | 237 |
| gaierror | 212 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.806 | prefer | 289 | 0.754 | 1348 |
| mheidari-all | 0.794 | prefer | 68 | 0.721 | 23236 |
| Surfboard-tg-mixed | 0.785 | prefer | 42 | 0.714 | 6911 |
| zhangkai | 0.484 | observe | 27 | 0.481 | 31 |
| Epodonios-all | 0.335 | observe | 1 | 1.0 | 7384 |
| ermaozi-get_subscribe | 0.309 | observe | 9 | 0.444 | 429 |
| chromego_merge | 0.264 | observe | 1 | 1.0 | 227 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 79 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |

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
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.444 | 4 | 5 | 9 |
| zhangkai | 0.481 | 13 | 14 | 27 |
| Surfboard-tg-mixed | 0.714 | 30 | 12 | 42 |
| mheidari-all | 0.721 | 49 | 19 | 68 |
| Au1rxx-base64 | 0.754 | 218 | 71 | 289 |
| Epodonios-all | 1.0 | 1 | 0 | 1 |
| chromego_merge | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23236 | yes | 3.47 | 0 |
| SoliSpirit-all | 10086 | yes | 2.3 | 0 |
| Epodonios-all | 7384 | yes | 3.69 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 1.88 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.9 | 0 |
| barry-far-vless | 5732 | yes | 1.28 | 0 |
| Surfboard-tg-vless | 5515 | yes | 2.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 1.39 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 1.65 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 46 |
| cn-block | 36 |
| speed | 30 |
| geo | 10 |
