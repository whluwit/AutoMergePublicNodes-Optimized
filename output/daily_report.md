# AutoNodes 每日报告

生成时间：2026-08-30 20:31:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79396 |
| 去重后节点数 | 21771 |
| TCP 可达数 | 3000 |
| 真测通过数 | 579 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21771 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 42.3 |
| geo | 1.5 |
| probe | 59.9 |
| real_test | 131.2 |
| tcp | 34.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 141 | 130 | 11 | 92.2% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 27 | 19 | 8 | 70.4% |
| vless | 478 | 385 | 93 | 80.5% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 28 |
| 204:TimeoutError | 26 |
| 204:ProxyError | 15 |
| geo:ClientOSError | 12 |
| speed:ClientOSError | 9 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 5 |
| speed:TimeoutError | 5 |
| geo:TimeoutError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4739 |
| ConnectionRefusedError | 887 |
| gaierror | 399 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | prefer | 337 | 0.92 | 1804 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| Surfboard-tg-mixed | 0.862 | prefer | 154 | 0.786 | 7004 |
| DeltaKronecker-all | 0.764 | prefer | 169 | 0.686 | 5576 |
| mheidari-all | 0.664 | observe | 9 | 1.0 | 14482 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4762 |
| Epodonios-all | 0.255 | observe | 0 | None | 7411 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7545 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5872 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.686 | 116 | 53 | 169 |
| Surfboard-tg-mixed | 0.786 | 121 | 33 | 154 |
| Au1rxx-base64 | 0.92 | 310 | 27 | 337 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| mheidari-all | 1.0 | 9 | 0 | 9 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14482 | yes | 5.03 | 0 |
| SoliSpirit-all | 7545 | yes | 4.0 | 0 |
| Epodonios-all | 7411 | yes | 4.11 | 0 |
| Surfboard-tg-mixed | 7004 | yes | 5.26 | 0 |
| barry-far-vless | 6057 | yes | 2.6 | 0 |
| Surfboard-tg-vless | 5872 | yes | 3.72 | 0 |
| DeltaKronecker-all | 5576 | yes | 4.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 4762 | yes | 5.09 | 0 |
| mahdibland-V2RayAggregator | 4041 | yes | 0.47 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.92 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 46 |
| cn-block | 38 |
| geo | 17 |
| speed | 15 |
