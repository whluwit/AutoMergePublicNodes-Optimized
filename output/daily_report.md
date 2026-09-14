# AutoNodes 每日报告

生成时间：2026-09-14 03:13:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 89722 |
| 去重后节点数 | 25406 |
| TCP 可达数 | 3000 |
| 真测通过数 | 479 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25406 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 38.8 |
| geo | 1.4 |
| probe | 233.4 |
| real_test | 323.4 |
| tcp | 42.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 36 | 21 | 15 | 58.3% |
| hysteria2 | 31 | 21 | 10 | 67.7% |
| shadowsocks | 174 | 165 | 9 | 94.8% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 69 | 38 | 31 | 55.1% |
| vless | 400 | 230 | 170 | 57.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 66 |
| speed:TimeoutError | 35 |
| speed:ClientOSError | 33 |
| geo:ClientOSError | 33 |
| cn-block:ClientOSError | 19 |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 12 |
| 204:ProxyConnectionError | 11 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5485 |
| ConnectionRefusedError | 980 |
| gaierror | 552 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.901 | prefer | 346 | 0.838 | 1616 |
| Surfboard-tg-mixed | 0.853 | prefer | 95 | 0.779 | 7482 |
| mheidari-all | 0.653 | observe | 101 | 0.574 | 15963 |
| ermaozi | 0.583 | observe | 28 | 0.571 | 417 |
| ermaozi-get_subscribe | 0.427 | observe | 9 | 0.667 | 444 |
| DeltaKronecker-all | 0.391 | observe | 101 | 0.307 | 5892 |
| Epodonios-all | 0.255 | observe | 0 | None | 7945 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8882 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6107 |

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
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.236 | 30 | 0.133 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| xiaoji235-airport-v2ray-all | 0.133 | 4 | 26 | 30 |
| DeltaKronecker-all | 0.307 | 31 | 70 | 101 |
| ermaozi | 0.571 | 16 | 12 | 28 |
| mheidari-all | 0.574 | 58 | 43 | 101 |
| ermaozi-get_subscribe | 0.667 | 6 | 3 | 9 |
| Surfboard-tg-mixed | 0.779 | 74 | 21 | 95 |
| Au1rxx-base64 | 0.838 | 290 | 56 | 346 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15963 | yes | 4.8 | 0 |
| SoliSpirit-all | 8882 | yes | 4.78 | 0 |
| Epodonios-all | 7945 | yes | 0.95 | 0 |
| Surfboard-tg-mixed | 7482 | yes | 5.08 | 0 |
| barry-far-vless | 6350 | yes | 3.29 | 0 |
| Surfboard-tg-vless | 6107 | yes | 4.24 | 0 |
| DeltaKronecker-all | 5892 | yes | 5.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 3.1 | 0 |
| mahdibland-V2RayAggregator | 4222 | yes | 1.03 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.6 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 100 |
| speed | 68 |
| 204 | 36 |
| cn-block | 32 |
