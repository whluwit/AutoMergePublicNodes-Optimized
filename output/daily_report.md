# AutoNodes 每日报告

生成时间：2026-09-24 11:09:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96221 |
| 去重后节点数 | 26192 |
| TCP 可达数 | 3000 |
| 真测通过数 | 372 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26192 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 87.1 |
| geo | 1.5 |
| probe | 268.5 |
| real_test | 168.4 |
| tcp | 42.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 68 | 42 | 26 | 61.8% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 157 | 143 | 14 | 91.1% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 29 | 10 | 19 | 34.5% |
| vless | 245 | 154 | 91 | 62.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 35 |
| cn-block:ClientOSError | 27 |
| 204:TimeoutError | 26 |
| geo:TimeoutError | 26 |
| speed:TimeoutError | 14 |
| cn-block:TimeoutError | 12 |
| geo:ClientOSError | 7 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:37015: bind: address already in use | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6063 |
| ConnectionRefusedError | 961 |
| gaierror | 341 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.963 | prefer | 215 | 0.902 | 1616 |
| Surfboard-tg-mixed | 0.747 | prefer | 103 | 0.67 | 7027 |
| ermaozi | 0.632 | observe | 53 | 0.623 | 339 |
| mheidari-all | 0.576 | observe | 127 | 0.496 | 22399 |
| ermaozi-get_subscribe | 0.537 | observe | 17 | 0.588 | 373 |
| DeltaKronecker-all | 0.314 | observe | 9 | 0.333 | 5845 |
| Epodonios-all | 0.255 | observe | 0 | None | 7495 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8854 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5676 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 3 | 6 | 9 |
| mheidari-all | 0.496 | 63 | 64 | 127 |
| ermaozi-get_subscribe | 0.588 | 10 | 7 | 17 |
| ermaozi | 0.623 | 33 | 20 | 53 |
| Surfboard-tg-mixed | 0.67 | 69 | 34 | 103 |
| Au1rxx-base64 | 0.902 | 194 | 21 | 215 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22399 | yes | 5.32 | 0 |
| SoliSpirit-all | 8854 | yes | 3.57 | 0 |
| Epodonios-all | 7495 | yes | 3.05 | 0 |
| Surfboard-tg-mixed | 7027 | yes | 3.63 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5899 | yes | 1.02 | 0 |
| DeltaKronecker-all | 5845 | yes | 6.15 | 0 |
| Surfboard-tg-vless | 5676 | yes | 5.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 2.81 | 0 |
| mahdibland-V2RayAggregator | 4305 | yes | 2.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 62 |
| cn-block | 41 |
| geo | 33 |
| speed | 18 |
| sing-box exited 1 | 1 |
