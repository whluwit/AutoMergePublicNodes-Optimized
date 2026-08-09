# AutoNodes 每日报告

生成时间：2026-08-09 18:36:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 86004 |
| 去重后节点数 | 23964 |
| TCP 可达数 | 3000 |
| 真测通过数 | 456 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23964 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 30.3 |
| geo | 1.4 |
| probe | 48.4 |
| real_test | 99.8 |
| tcp | 35.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 145 | 135 | 10 | 93.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 126 | 121 | 5 | 96.0% |
| vless | 244 | 155 | 89 | 63.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 31 |
| 204:TimeoutError | 25 |
| speed:TimeoutError | 13 |
| speed:ClientOSError | 9 |
| geo:TimeoutError | 7 |
| cn-block:TimeoutError | 5 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5010 |
| ConnectionRefusedError | 813 |
| gaierror | 232 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.992 | prefer | 382 | 0.927 | 1688 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.753 | prefer | 99 | 0.677 | 6583 |
| mheidari-all | 0.334 | observe | 57 | 0.246 | 20206 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 107 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5505 |
| Epodonios-all | 0.255 | observe | 0 | None | 7179 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7585 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5399 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| DeltaKronecker-all | 0.17 | observe | 3 | 0.0 | 0 | 4998 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.246 | 14 | 43 | 57 |
| Surfboard-tg-mixed | 0.677 | 67 | 32 | 99 |
| Au1rxx-base64 | 0.927 | 354 | 28 | 382 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20206 | yes | 4.88 | 0 |
| SoliSpirit-all | 7585 | yes | 1.36 | 0 |
| Epodonios-all | 7179 | yes | 3.76 | 0 |
| Surfboard-tg-mixed | 6583 | yes | 2.75 | 0 |
| barry-far-vless | 5713 | yes | 0.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 5505 | yes | 1.07 | 0 |
| Surfboard-tg-vless | 5399 | yes | 3.92 | 0 |
| mahdibland-V2RayAggregator | 5189 | yes | 2.5 | 0 |
| DeltaKronecker-all | 4998 | yes | 3.98 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 38 |
| 204 | 34 |
| speed | 24 |
| cn-block | 10 |
