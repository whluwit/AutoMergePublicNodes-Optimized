# AutoNodes 每日报告

生成时间：2026-09-23 10:49:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96830 |
| 去重后节点数 | 26481 |
| TCP 可达数 | 3000 |
| 真测通过数 | 427 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26481 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 71.0 |
| geo | 1.3 |
| probe | 278.1 |
| real_test | 187.9 |
| tcp | 43.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 66 | 47 | 19 | 71.2% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 171 | 156 | 15 | 91.2% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 15 | 8 | 7 | 53.3% |
| vless | 329 | 193 | 136 | 58.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 52 |
| 204:ProxyError | 29 |
| geo:ClientOSError | 27 |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 15 |
| geo:TimeoutError | 13 |
| speed:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5871 |
| ConnectionRefusedError | 957 |
| gaierror | 320 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.899 | prefer | 246 | 0.837 | 1602 |
| mheidari-all | 0.811 | prefer | 91 | 0.736 | 22242 |
| ermaozi | 0.76 | prefer | 57 | 0.754 | 346 |
| Surfboard-tg-mixed | 0.625 | observe | 185 | 0.546 | 7036 |
| DeltaKronecker-all | 0.425 | observe | 15 | 0.4 | 6471 |
| ermaozi-get_subscribe | 0.307 | observe | 9 | 0.444 | 372 |
| Epodonios-all | 0.255 | observe | 0 | None | 7633 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9065 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5755 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.4 | 6 | 9 | 15 |
| ermaozi-get_subscribe | 0.444 | 4 | 5 | 9 |
| Surfboard-tg-mixed | 0.546 | 101 | 84 | 185 |
| mheidari-all | 0.736 | 67 | 24 | 91 |
| ermaozi | 0.754 | 43 | 14 | 57 |
| Au1rxx-base64 | 0.837 | 206 | 40 | 246 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22242 | yes | 3.11 | 0 |
| SoliSpirit-all | 9065 | yes | 1.92 | 0 |
| Epodonios-all | 7633 | yes | 1.56 | 0 |
| Surfboard-tg-mixed | 7036 | yes | 2.57 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.58 | 0 |
| DeltaKronecker-all | 6471 | yes | 3.09 | 0 |
| barry-far-vless | 5975 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 5755 | yes | 2.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 1.15 | 0 |
| mahdibland-V2RayAggregator | 4187 | yes | 0.87 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 64 |
| 204 | 51 |
| geo | 41 |
| cn-block | 24 |
