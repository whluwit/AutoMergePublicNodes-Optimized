# AutoNodes 每日报告

生成时间：2026-09-17 11:02:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84508 |
| 去重后节点数 | 22939 |
| TCP 可达数 | 3000 |
| 真测通过数 | 433 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22939 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 85.9 |
| geo | 1.4 |
| probe | 277.6 |
| real_test | 253.6 |
| tcp | 37.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 77 | 47 | 30 | 61.0% |
| hysteria2 | 19 | 16 | 3 | 84.2% |
| shadowsocks | 165 | 147 | 18 | 89.1% |
| socks | 8 | 5 | 3 | 62.5% |
| trojan | 16 | 5 | 11 | 31.2% |
| vless | 329 | 210 | 119 | 63.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 41 |
| 204:TimeoutError | 33 |
| geo:ClientOSError | 22 |
| geo:TimeoutError | 19 |
| speed:TimeoutError | 19 |
| cn-block:TimeoutError | 17 |
| speed:ClientOSError | 15 |
| cn-block:ClientOSError | 11 |
| cn-block:ProxyError | 4 |
| 204:ServerDisconnectedError | 1 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5308 |
| ConnectionRefusedError | 828 |
| gaierror | 340 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.881 | prefer | 289 | 0.817 | 1671 |
| mheidari-all | 0.838 | prefer | 64 | 0.766 | 16008 |
| ermaozi | 0.735 | prefer | 55 | 0.727 | 396 |
| DeltaKronecker-all | 0.667 | observe | 44 | 0.591 | 5931 |
| Surfboard-tg-mixed | 0.616 | observe | 138 | 0.536 | 7408 |
| ermaozi-get_subscribe | 0.325 | observe | 24 | 0.292 | 431 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 189 |
| Epodonios-all | 0.255 | observe | 0 | None | 7867 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8876 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.292 | 7 | 17 | 24 |
| Surfboard-tg-mixed | 0.536 | 74 | 64 | 138 |
| DeltaKronecker-all | 0.591 | 26 | 18 | 44 |
| ermaozi | 0.727 | 40 | 15 | 55 |
| mheidari-all | 0.766 | 49 | 15 | 64 |
| Au1rxx-base64 | 0.817 | 236 | 53 | 289 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16008 | yes | 4.4 | 0 |
| SoliSpirit-all | 8876 | yes | 3.61 | 0 |
| Epodonios-all | 7867 | yes | 4.6 | 0 |
| Surfboard-tg-mixed | 7408 | yes | 3.31 | 0 |
| barry-far-vless | 6149 | yes | 4.31 | 0 |
| DeltaKronecker-all | 5931 | yes | 3.69 | 0 |
| Surfboard-tg-vless | 5925 | yes | 3.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 4.66 | 0 |
| mahdibland-V2RayAggregator | 4179 | yes | 0.15 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.61 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 76 |
| geo | 42 |
| speed | 34 |
| cn-block | 32 |
