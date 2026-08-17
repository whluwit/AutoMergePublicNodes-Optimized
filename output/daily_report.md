# AutoNodes 每日报告

生成时间：2026-08-17 18:39:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 80682 |
| 去重后节点数 | 22980 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1377 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22980 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 13.8 |
| generate | 40.6 |
| geo | 1.4 |
| probe | 90.2 |
| real_test | 301.7 |
| tcp | 36.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 18 | 14 | 4 | 77.8% |
| shadowsocks | 126 | 109 | 17 | 86.5% |
| socks | 6 | 6 | 0 | 100.0% |
| trojan | 796 | 794 | 2 | 99.7% |
| tuic | 1 | 1 | 0 | 100.0% |
| vless | 438 | 324 | 114 | 74.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 41 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 16 |
| geo:TimeoutError | 13 |
| geo:ClientOSError | 12 |
| speed:ClientOSError | 11 |
| 204:ProxyError | 10 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4701 |
| ConnectionRefusedError | 817 |
| gaierror | 301 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 286 | 0.944 | 15619 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Au1rxx-base64 | 0.979 | prefer | 964 | 0.9 | 1983 |
| Surfboard-tg-mixed | 0.925 | prefer | 127 | 0.85 | 6186 |
| MatinGhanbari-all-sub | 0.335 | observe | 1 | 1.0 | 3987 |
| DeltaKronecker-all | 0.263 | observe | 8 | 0.25 | 6368 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 192 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5085 |
| Epodonios-all | 0.255 | observe | 0 | None | 6790 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6707 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.25 | 2 | 6 | 8 |
| Surfboard-tg-mixed | 0.85 | 108 | 19 | 127 |
| Au1rxx-base64 | 0.9 | 868 | 96 | 964 |
| mheidari-all | 0.944 | 270 | 16 | 286 |
| MatinGhanbari-all-sub | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15619 | yes | 5.24 | 0 |
| Epodonios-all | 6790 | yes | 4.12 | 0 |
| SoliSpirit-all | 6707 | yes | 3.08 | 0 |
| DeltaKronecker-all | 6368 | yes | 4.09 | 0 |
| Surfboard-tg-mixed | 6186 | yes | 3.92 | 0 |
| barry-far-vless | 5131 | yes | 1.81 | 0 |
| 10ium-ScrapeCategorize-Vless | 5085 | yes | 2.21 | 0 |
| Surfboard-tg-vless | 4808 | yes | 3.18 | 0 |
| mahdibland-V2RayAggregator | 4027 | yes | 1.3 | 0 |
| MatinGhanbari-all-sub | 3987 | yes | 2.02 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 52 |
| 204 | 32 |
| cn-block | 27 |
| geo | 26 |
