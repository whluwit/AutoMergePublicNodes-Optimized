# AutoNodes 每日报告

生成时间：2026-08-24 18:39:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84182 |
| 去重后节点数 | 23793 |
| TCP 可达数 | 3000 |
| 真测通过数 | 569 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23793 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 70.8 |
| generate | 42.1 |
| geo | 1.4 |
| probe | 58.6 |
| real_test | 129.7 |
| tcp | 36.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 25 | 25 | 0 | 100.0% |
| shadowsocks | 201 | 181 | 20 | 90.0% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 45 | 38 | 7 | 84.4% |
| vless | 405 | 300 | 105 | 74.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 36 |
| cn-block:TimeoutError | 35 |
| 204:TimeoutError | 26 |
| 204:ProxyError | 10 |
| speed:TimeoutError | 9 |
| geo:ClientOSError | 8 |
| speed:ClientOSError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4664 |
| ConnectionRefusedError | 931 |
| gaierror | 511 |
| OSError | 243 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.939 | prefer | 362 | 0.87 | 1779 |
| Surfboard-tg-mixed | 0.929 | prefer | 117 | 0.855 | 6472 |
| mheidari-all | 0.895 | prefer | 79 | 0.823 | 19577 |
| DeltaKronecker-all | 0.625 | observe | 121 | 0.545 | 5914 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4899 |
| Epodonios-all | 0.255 | observe | 0 | None | 6977 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3989 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7298 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5396 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.545 | 66 | 55 | 121 |
| mheidari-all | 0.823 | 65 | 14 | 79 |
| Surfboard-tg-mixed | 0.855 | 100 | 17 | 117 |
| Au1rxx-base64 | 0.87 | 315 | 47 | 362 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19577 | yes | 4.67 | 0 |
| SoliSpirit-all | 7298 | yes | 4.75 | 0 |
| Epodonios-all | 6977 | yes | 4.96 | 0 |
| Surfboard-tg-mixed | 6472 | yes | 5.49 | 0 |
| DeltaKronecker-all | 5914 | yes | 5.33 | 0 |
| barry-far-vless | 5685 | yes | 2.69 | 0 |
| Surfboard-tg-vless | 5396 | yes | 3.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 4899 | yes | 3.39 | 0 |
| mahdibland-V2RayAggregator | 4132 | yes | 3.04 | 0 |
| MatinGhanbari-all-sub | 3989 | yes | 3.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 45 |
| 204 | 40 |
| cn-block | 37 |
| speed | 13 |
