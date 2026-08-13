# AutoNodes 每日报告

生成时间：2026-08-13 01:32:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 79693 |
| 去重后节点数 | 22323 |
| TCP 可达数 | 3000 |
| 真测通过数 | 671 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22323 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 32.0 |
| geo | 1.3 |
| probe | 56.3 |
| real_test | 162.5 |
| tcp | 32.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 127 | 1 | 99.2% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 170 | 161 | 9 | 94.7% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 141 | 122 | 19 | 86.5% |
| vless | 517 | 239 | 278 | 46.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 123 |
| speed:TimeoutError | 65 |
| cn-block:TimeoutError | 35 |
| geo:ClientOSError | 34 |
| speed:ClientOSError | 26 |
| 204:TimeoutError | 10 |
| 204:ProxyError | 9 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4533 |
| ConnectionRefusedError | 770 |
| gaierror | 311 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 128 | 0.992 | 159 |
| Au1rxx-base64 | 0.954 | prefer | 404 | 0.896 | 1489 |
| Surfboard-tg-mixed | 0.686 | observe | 158 | 0.608 | 5952 |
| mheidari-all | 0.465 | observe | 177 | 0.384 | 16809 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5328 |
| Epodonios-all | 0.255 | observe | 0 | None | 6571 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7449 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4781 |
| barry-far-vless | 0.255 | observe | 0 | None | 5114 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.167 | 18 | 90 | 108 |
| mheidari-all | 0.384 | 68 | 109 | 177 |
| Surfboard-tg-mixed | 0.608 | 96 | 62 | 158 |
| Au1rxx-base64 | 0.896 | 362 | 42 | 404 |
| zhangkai | 0.992 | 127 | 1 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16809 | yes | 3.83 | 0 |
| SoliSpirit-all | 7449 | yes | 2.79 | 0 |
| Epodonios-all | 6571 | yes | 1.94 | 0 |
| Surfboard-tg-mixed | 5952 | yes | 2.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 5328 | yes | 2.4 | 0 |
| mahdibland-V2RayAggregator | 5209 | yes | 2.05 | 0 |
| barry-far-vless | 5114 | yes | 0.81 | 0 |
| DeltaKronecker-all | 4975 | yes | 3.12 | 0 |
| Surfboard-tg-vless | 4781 | yes | 2.18 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.52 | 0 |

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
| geo | 158 |
| speed | 91 |
| cn-block | 37 |
| 204 | 22 |
