# AutoNodes 每日报告

生成时间：2026-10-18 02:59:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99173 |
| 去重后节点数 | 27840 |
| TCP 可达数 | 3000 |
| 真测通过数 | 551 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27840 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 135.5 |
| geo | 1.4 |
| probe | 285.9 |
| real_test | 426.3 |
| tcp | 49.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 99 | 53 | 46 | 53.5% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 149 | 142 | 7 | 95.3% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 51 | 44 | 7 | 86.3% |
| vless | 501 | 293 | 208 | 58.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 103 |
| 204:ProxyError | 58 |
| geo:ClientOSError | 31 |
| speed:ClientOSError | 28 |
| cn-block:TimeoutError | 19 |
| speed:TimeoutError | 11 |
| 204:TimeoutError | 10 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7195 |
| ConnectionRefusedError | 1024 |
| OSError | 235 |
| gaierror | 138 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | prefer | 444 | 0.887 | 1798 |
| Surfboard-tg-mixed | 0.854 | prefer | 29 | 0.793 | 7181 |
| ermaozi | 0.577 | observe | 100 | 0.55 | 710 |
| DeltaKronecker-all | 0.45 | observe | 12 | 0.5 | 4999 |
| mheidari-all | 0.393 | observe | 231 | 0.312 | 23946 |
| ermaozi-get_subscribe | 0.279 | observe | 1 | 1.0 | 599 |
| Epodonios-all | 0.255 | observe | 0 | None | 7667 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9951 |
| barry-far-vless | 0.255 | observe | 0 | None | 5884 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.312 | 72 | 159 | 231 |
| DeltaKronecker-all | 0.5 | 6 | 6 | 12 |
| ermaozi | 0.55 | 55 | 45 | 100 |
| Surfboard-tg-mixed | 0.793 | 23 | 6 | 29 |
| Au1rxx-base64 | 0.887 | 394 | 50 | 444 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23946 | yes | 4.45 | 0 |
| SoliSpirit-all | 9951 | yes | 2.66 | 0 |
| Epodonios-all | 7667 | yes | 3.24 | 0 |
| Surfboard-tg-mixed | 7181 | yes | 2.61 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.09 | 0 |
| barry-far-vless | 5884 | yes | 1.33 | 0 |
| Surfboard-tg-vless | 5616 | yes | 3.34 | 0 |
| DeltaKronecker-all | 4999 | yes | 3.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 1.45 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 2.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 134 |
| 204 | 72 |
| speed | 39 |
| cn-block | 26 |
