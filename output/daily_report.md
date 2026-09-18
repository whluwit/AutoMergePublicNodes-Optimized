# AutoNodes 每日报告

生成时间：2026-09-18 10:38:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83517 |
| 去重后节点数 | 22969 |
| TCP 可达数 | 3000 |
| 真测通过数 | 398 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22969 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 79.2 |
| geo | 1.6 |
| probe | 277.7 |
| real_test | 260.8 |
| tcp | 37.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 45 | 35 | 10 | 77.8% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 178 | 158 | 20 | 88.8% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 39 | 6 | 33 | 15.4% |
| vless | 290 | 179 | 111 | 61.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 40 |
| geo:TimeoutError | 27 |
| 204:ProxyError | 25 |
| geo:ClientOSError | 25 |
| cn-block:TimeoutError | 19 |
| speed:TimeoutError | 18 |
| speed:ClientOSError | 10 |
| cn-block:ClientOSError | 8 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5173 |
| ConnectionRefusedError | 827 |
| gaierror | 432 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | prefer | 260 | 0.823 | 1622 |
| ermaozi | 0.729 | prefer | 47 | 0.723 | 378 |
| mheidari-all | 0.716 | prefer | 64 | 0.641 | 15778 |
| Surfboard-tg-mixed | 0.658 | observe | 152 | 0.579 | 7294 |
| DeltaKronecker-all | 0.44 | observe | 48 | 0.354 | 6040 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| ermaozi-get_subscribe | 0.327 | observe | 2 | 1.0 | 402 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7751 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.354 | 17 | 31 | 48 |
| Surfboard-tg-mixed | 0.579 | 88 | 64 | 152 |
| mheidari-all | 0.641 | 41 | 23 | 64 |
| ermaozi | 0.723 | 34 | 13 | 47 |
| Au1rxx-base64 | 0.823 | 214 | 46 | 260 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15778 | yes | 4.67 | 0 |
| SoliSpirit-all | 8957 | yes | 4.13 | 0 |
| Epodonios-all | 7751 | yes | 4.97 | 0 |
| Surfboard-tg-mixed | 7294 | yes | 3.5 | 0 |
| DeltaKronecker-all | 6040 | yes | 5.19 | 0 |
| barry-far-vless | 5979 | yes | 2.76 | 0 |
| Surfboard-tg-vless | 5763 | yes | 4.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 2.56 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 3.12 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.9 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 67 |
| geo | 53 |
| cn-block | 30 |
| speed | 28 |
