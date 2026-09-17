# AutoNodes 每日报告

生成时间：2026-09-17 21:03:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84628 |
| 去重后节点数 | 23061 |
| TCP 可达数 | 3000 |
| 真测通过数 | 447 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23061 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 86.8 |
| geo | 1.5 |
| probe | 214.8 |
| real_test | 217.7 |
| tcp | 37.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 19 | 9 | 10 | 47.4% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 161 | 149 | 12 | 92.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 11 | 8 | 3 | 72.7% |
| vless | 345 | 262 | 83 | 75.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 20 |
| 204:ProxyError | 17 |
| geo:TimeoutError | 13 |
| cn-block:TimeoutError | 13 |
| geo:ClientOSError | 12 |
| speed:ClientOSError | 11 |
| speed:TimeoutError | 9 |
| cn-block:ProxyError | 5 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4963 |
| ConnectionRefusedError | 839 |
| gaierror | 438 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.994 | prefer | 33 | 0.939 | 16164 |
| Au1rxx-base64 | 0.93 | prefer | 265 | 0.868 | 1619 |
| DeltaKronecker-all | 0.847 | prefer | 118 | 0.771 | 5931 |
| Surfboard-tg-mixed | 0.78 | prefer | 118 | 0.703 | 7499 |
| ermaozi | 0.449 | observe | 16 | 0.5 | 357 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4261 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5093 |
| Epodonios-all | 0.255 | observe | 0 | None | 7954 |
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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.5 | 2 | 2 | 4 |
| ermaozi | 0.5 | 8 | 8 | 16 |
| Surfboard-tg-mixed | 0.703 | 83 | 35 | 118 |
| DeltaKronecker-all | 0.771 | 91 | 27 | 118 |
| Au1rxx-base64 | 0.868 | 230 | 35 | 265 |
| mheidari-all | 0.939 | 31 | 2 | 33 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16164 | yes | 5.32 | 0 |
| SoliSpirit-all | 8875 | yes | 3.89 | 0 |
| Epodonios-all | 7954 | yes | 3.43 | 0 |
| Surfboard-tg-mixed | 7499 | yes | 5.92 | 0 |
| barry-far-vless | 6157 | yes | 0.96 | 0 |
| Surfboard-tg-vless | 5936 | yes | 4.29 | 0 |
| DeltaKronecker-all | 5931 | yes | 4.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 2.97 | 0 |
| mahdibland-V2RayAggregator | 4261 | yes | 3.04 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.34 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| geo | 25 |
| cn-block | 23 |
| speed | 21 |
