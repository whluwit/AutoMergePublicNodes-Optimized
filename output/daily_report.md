# AutoNodes 每日报告

生成时间：2026-10-07 22:43:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98251 |
| 去重后节点数 | 27407 |
| TCP 可达数 | 3000 |
| 真测通过数 | 430 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27407 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 74.5 |
| geo | 1.5 |
| probe | 189.0 |
| real_test | 189.6 |
| tcp | 46.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 39 | 24 | 15 | 61.5% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 135 | 110 | 25 | 81.5% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 90 | 89 | 1 | 98.9% |
| vless | 226 | 179 | 47 | 79.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 30 |
| 204:ProxyError | 14 |
| speed:TimeoutError | 12 |
| 204:TimeoutError | 10 |
| speed:ClientOSError | 7 |
| geo:TimeoutError | 6 |
| geo:ClientOSError | 3 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6683 |
| ConnectionRefusedError | 1021 |
| gaierror | 388 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.932 | prefer | 52 | 0.865 | 7069 |
| mheidari-all | 0.929 | prefer | 84 | 0.857 | 23169 |
| Au1rxx-base64 | 0.912 | prefer | 339 | 0.841 | 1824 |
| ermaozi | 0.636 | observe | 39 | 0.615 | 664 |
| ermaozi-get_subscribe | 0.278 | observe | 1 | 1.0 | 565 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 5344 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7553 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| ermaozi | 0.615 | 24 | 15 | 39 |
| Au1rxx-base64 | 0.841 | 285 | 54 | 339 |
| mheidari-all | 0.857 | 72 | 12 | 84 |
| Surfboard-tg-mixed | 0.865 | 45 | 7 | 52 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23169 | yes | 6.15 | 0 |
| SoliSpirit-all | 9262 | yes | 6.2 | 0 |
| Epodonios-all | 7553 | yes | 3.9 | 0 |
| Surfboard-tg-mixed | 7069 | yes | 7.14 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.24 | 0 |
| barry-far-vless | 5859 | yes | 4.92 | 0 |
| Surfboard-tg-vless | 5616 | yes | 4.55 | 0 |
| DeltaKronecker-all | 5344 | yes | 5.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 5138 | yes | 2.27 | 0 |
| mahdibland-V2RayAggregator | 4431 | yes | 2.07 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 34 |
| 204 | 28 |
| speed | 19 |
| geo | 10 |
