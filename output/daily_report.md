# AutoNodes 每日报告

生成时间：2026-09-16 10:54:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 87860 |
| 去重后节点数 | 24299 |
| TCP 可达数 | 3000 |
| 真测通过数 | 471 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24299 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 71.9 |
| geo | 1.5 |
| probe | 233.7 |
| real_test | 256.2 |
| tcp | 41.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 73 | 49 | 24 | 67.1% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 152 | 136 | 16 | 89.5% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 38 | 31 | 7 | 81.6% |
| vless | 325 | 234 | 91 | 72.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 28 |
| 204:ProxyError | 26 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 17 |
| speed:ClientOSError | 14 |
| speed:TimeoutError | 11 |
| cn-block:ClientOSError | 10 |
| geo:TimeoutError | 8 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5636 |
| ConnectionRefusedError | 901 |
| gaierror | 436 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.914 | prefer | 303 | 0.848 | 1704 |
| DeltaKronecker-all | 0.818 | prefer | 40 | 0.75 | 6081 |
| ermaozi | 0.78 | prefer | 53 | 0.774 | 407 |
| mheidari-all | 0.776 | prefer | 67 | 0.701 | 16003 |
| Surfboard-tg-mixed | 0.76 | prefer | 126 | 0.683 | 7446 |
| ermaozi-get_subscribe | 0.432 | observe | 19 | 0.421 | 438 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5115 |
| Epodonios-all | 0.255 | observe | 0 | None | 8003 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.421 | 8 | 11 | 19 |
| Surfboard-tg-mixed | 0.683 | 86 | 40 | 126 |
| mheidari-all | 0.701 | 47 | 20 | 67 |
| DeltaKronecker-all | 0.75 | 30 | 10 | 40 |
| ermaozi | 0.774 | 41 | 12 | 53 |
| Au1rxx-base64 | 0.848 | 257 | 46 | 303 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16003 | yes | 3.21 | 0 |
| SoliSpirit-all | 9062 | yes | 3.93 | 0 |
| Epodonios-all | 8003 | yes | 4.04 | 0 |
| Surfboard-tg-mixed | 7446 | yes | 2.62 | 0 |
| barry-far-vless | 6340 | yes | 0.64 | 0 |
| DeltaKronecker-all | 6081 | yes | 3.49 | 0 |
| Surfboard-tg-vless | 6044 | yes | 2.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 4.1 | 0 |
| mahdibland-V2RayAggregator | 4206 | yes | 0.11 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.4 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 48 |
| geo | 37 |
| cn-block | 29 |
| speed | 27 |
