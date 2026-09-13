# AutoNodes 每日报告

生成时间：2026-09-13 11:10:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 94216 |
| 去重后节点数 | 25182 |
| TCP 可达数 | 3000 |
| 真测通过数 | 422 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25182 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 30.5 |
| geo | 1.4 |
| probe | 307.1 |
| real_test | 246.5 |
| tcp | 41.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 56 | 33 | 23 | 58.9% |
| hysteria2 | 23 | 20 | 3 | 87.0% |
| shadowsocks | 141 | 130 | 11 | 92.2% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 22 | 17 | 5 | 77.3% |
| vless | 305 | 217 | 88 | 71.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 27 |
| speed:ClientOSError | 23 |
| 204:ProxyError | 18 |
| geo:ClientOSError | 17 |
| cn-block:TimeoutError | 15 |
| 204:ProxyConnectionError | 8 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4974 |
| ConnectionRefusedError | 986 |
| gaierror | 516 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.922 | prefer | 93 | 0.849 | 20485 |
| Au1rxx-base64 | 0.855 | prefer | 250 | 0.792 | 1633 |
| Surfboard-tg-mixed | 0.815 | prefer | 134 | 0.739 | 7439 |
| ermaozi | 0.677 | observe | 45 | 0.667 | 436 |
| DeltaKronecker-all | 0.65 | observe | 17 | 0.647 | 5892 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5301 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 102 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| Epodonios-all | 0.255 | observe | 0 | None | 7887 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.23 | 12 | 0.25 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 3 | 9 | 12 |
| DeltaKronecker-all | 0.647 | 11 | 6 | 17 |
| ermaozi | 0.667 | 30 | 15 | 45 |
| Surfboard-tg-mixed | 0.739 | 99 | 35 | 134 |
| Au1rxx-base64 | 0.792 | 198 | 52 | 250 |
| mheidari-all | 0.849 | 79 | 14 | 93 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20485 | yes | 5.82 | 0 |
| SoliSpirit-all | 8937 | yes | 5.51 | 0 |
| Epodonios-all | 7887 | yes | 3.57 | 0 |
| Surfboard-tg-mixed | 7439 | yes | 4.9 | 0 |
| barry-far-vless | 6291 | yes | 2.1 | 0 |
| Surfboard-tg-vless | 6075 | yes | 3.86 | 0 |
| DeltaKronecker-all | 5892 | yes | 6.32 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 1.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.01 | 0 |
| mahdibland-V2RayAggregator | 4221 | yes | 3.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 57 |
| speed | 30 |
| cn-block | 23 |
| geo | 22 |
