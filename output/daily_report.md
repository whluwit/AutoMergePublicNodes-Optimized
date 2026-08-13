# AutoNodes 每日报告

生成时间：2026-08-13 13:03:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79755 |
| 去重后节点数 | 22396 |
| TCP 可达数 | 3000 |
| 真测通过数 | 763 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22396 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 37.1 |
| geo | 1.2 |
| probe | 56.1 |
| real_test | 162.0 |
| tcp | 33.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 165 | 152 | 13 | 92.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 323 | 313 | 10 | 96.9% |
| vless | 223 | 150 | 73 | 67.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 21 |
| 204:TimeoutError | 17 |
| geo:TimeoutError | 14 |
| geo:ClientOSError | 13 |
| 204:ProxyError | 9 |
| speed:TimeoutError | 8 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4106 |
| ConnectionRefusedError | 768 |
| gaierror | 350 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 520 | 0.94 | 1576 |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.838 | prefer | 118 | 0.763 | 5953 |
| mheidari-all | 0.688 | observe | 77 | 0.61 | 17032 |
| DeltaKronecker-all | 0.547 | observe | 18 | 0.5 | 4878 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5203 |
| Epodonios-all | 0.255 | observe | 0 | None | 6610 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7445 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4665 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 9 | 9 | 18 |
| mheidari-all | 0.61 | 47 | 30 | 77 |
| Surfboard-tg-mixed | 0.763 | 90 | 28 | 118 |
| Au1rxx-base64 | 0.94 | 489 | 31 | 520 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17032 | yes | 4.06 | 0 |
| SoliSpirit-all | 7445 | yes | 3.13 | 0 |
| Epodonios-all | 6610 | yes | 1.96 | 0 |
| Surfboard-tg-mixed | 5953 | yes | 2.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 5203 | yes | 1.49 | 0 |
| mahdibland-V2RayAggregator | 5197 | yes | 3.63 | 0 |
| barry-far-vless | 5031 | yes | 1.29 | 0 |
| DeltaKronecker-all | 4878 | yes | 3.92 | 0 |
| Surfboard-tg-vless | 4665 | yes | 2.91 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.93 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 31 |
| cn-block | 28 |
| geo | 27 |
| speed | 13 |
