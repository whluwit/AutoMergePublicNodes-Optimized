# AutoNodes 每日报告

生成时间：2026-09-16 03:20:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 85245 |
| 去重后节点数 | 23243 |
| TCP 可达数 | 3000 |
| 真测通过数 | 651 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23243 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 135.0 |
| geo | 1.5 |
| probe | 365.1 |
| real_test | 588.5 |
| tcp | 38.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 59 | 46 | 13 | 78.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 169 | 156 | 13 | 92.3% |
| socks | 7 | 2 | 5 | 28.6% |
| trojan | 12 | 6 | 6 | 50.0% |
| vless | 859 | 423 | 436 | 49.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 201 |
| geo:ClientOSError | 82 |
| speed:TimeoutError | 59 |
| speed:ClientOSError | 48 |
| cn-block:TimeoutError | 27 |
| 204:ProxyError | 19 |
| 204:TimeoutError | 16 |
| cn-block:ClientOSError | 7 |
| 204:ProxyConnectionError | 6 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| 204:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5476 |
| ConnectionRefusedError | 833 |
| gaierror | 364 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | prefer | 278 | 0.881 | 1640 |
| ermaozi | 0.757 | prefer | 52 | 0.75 | 407 |
| Surfboard-tg-mixed | 0.685 | observe | 193 | 0.606 | 7549 |
| mheidari-all | 0.682 | observe | 106 | 0.604 | 16114 |
| ermaozi-get_subscribe | 0.467 | observe | 7 | 0.857 | 438 |
| DeltaKronecker-all | 0.447 | observe | 480 | 0.367 | 5932 |
| roosterkid-openproxylist-v2ray | 0.317 | observe | 2 | 1.0 | 150 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 148 |
| Epodonios-all | 0.255 | observe | 0 | None | 8042 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.367 | 176 | 304 | 480 |
| mheidari-all | 0.604 | 64 | 42 | 106 |
| Surfboard-tg-mixed | 0.606 | 117 | 76 | 193 |
| ermaozi | 0.75 | 39 | 13 | 52 |
| ermaozi-get_subscribe | 0.857 | 6 | 1 | 7 |
| Au1rxx-base64 | 0.881 | 245 | 33 | 278 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16114 | yes | 5.74 | 0 |
| SoliSpirit-all | 8952 | yes | 2.23 | 0 |
| Epodonios-all | 8042 | yes | 4.64 | 0 |
| Surfboard-tg-mixed | 7549 | yes | 3.63 | 0 |
| barry-far-vless | 6344 | yes | 1.55 | 0 |
| Surfboard-tg-vless | 6134 | yes | 4.1 | 0 |
| DeltaKronecker-all | 5932 | yes | 4.78 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.08 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 1.83 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 286 |
| speed | 107 |
| 204 | 44 |
| cn-block | 37 |
