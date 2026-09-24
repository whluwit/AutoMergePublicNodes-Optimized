# AutoNodes 每日报告

生成时间：2026-09-24 16:31:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96369 |
| 去重后节点数 | 26302 |
| TCP 可达数 | 3000 |
| 真测通过数 | 369 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26302 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 76.3 |
| geo | 1.5 |
| probe | 234.1 |
| real_test | 163.0 |
| tcp | 43.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 35 | 21 | 14 | 60.0% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 157 | 137 | 20 | 87.3% |
| socks | 6 | 1 | 5 | 16.7% |
| trojan | 19 | 11 | 8 | 57.9% |
| vless | 237 | 179 | 58 | 75.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 28 |
| 204:ProxyError | 20 |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 18 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| geo:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5959 |
| ConnectionRefusedError | 974 |
| gaierror | 389 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.989 | prefer | 253 | 0.925 | 1697 |
| mheidari-all | 0.713 | prefer | 88 | 0.636 | 22258 |
| Surfboard-tg-mixed | 0.668 | observe | 95 | 0.589 | 7027 |
| ermaozi | 0.618 | observe | 31 | 0.613 | 298 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 5845 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 71 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5307 |
| Epodonios-all | 0.255 | observe | 0 | None | 7498 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.589 | 56 | 39 | 95 |
| ermaozi | 0.613 | 19 | 12 | 31 |
| mheidari-all | 0.636 | 56 | 32 | 88 |
| Au1rxx-base64 | 0.925 | 234 | 19 | 253 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22258 | yes | 6.26 | 0 |
| SoliSpirit-all | 9120 | yes | 3.15 | 0 |
| Epodonios-all | 7498 | yes | 3.5 | 0 |
| Surfboard-tg-mixed | 7027 | yes | 4.58 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.84 | 0 |
| barry-far-vless | 5901 | yes | 1.3 | 0 |
| DeltaKronecker-all | 5845 | yes | 6.48 | 0 |
| Surfboard-tg-vless | 5676 | yes | 4.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 1.59 | 0 |
| mahdibland-V2RayAggregator | 4305 | yes | 2.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 49 |
| 204 | 42 |
| speed | 10 |
| geo | 5 |
