# AutoNodes 每日报告

生成时间：2026-08-10 07:26:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 87538 |
| 去重后节点数 | 24644 |
| TCP 可达数 | 3000 |
| 真测通过数 | 465 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24644 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 32.4 |
| geo | 1.4 |
| probe | 56.8 |
| real_test | 108.6 |
| tcp | 36.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 153 | 135 | 18 | 88.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 153 | 130 | 23 | 85.0% |
| vless | 283 | 156 | 127 | 55.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 46 |
| geo:TimeoutError | 34 |
| 204:TimeoutError | 19 |
| speed:ClientOSError | 18 |
| 204:ProxyError | 14 |
| cn-block:TimeoutError | 14 |
| geo:ClientOSError | 13 |
| 204:ClientOSError | 9 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4929 |
| ConnectionRefusedError | 812 |
| gaierror | 287 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Au1rxx-base64 | 0.879 | prefer | 450 | 0.811 | 1742 |
| Surfboard-tg-mixed | 0.666 | observe | 85 | 0.588 | 6713 |
| DeltaKronecker-all | 0.448 | observe | 36 | 0.361 | 5881 |
| mheidari-all | 0.421 | observe | 39 | 0.333 | 20373 |
| Au1rxx-clash | 0.389 | observe | 4 | 0.75 | 1723 |
| nscl5-all | 0.313 | observe | 1 | 1.0 | 1442 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7338 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.333 | 13 | 26 | 39 |
| DeltaKronecker-all | 0.361 | 13 | 23 | 36 |
| Surfboard-tg-mixed | 0.588 | 50 | 35 | 85 |
| Au1rxx-clash | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.811 | 365 | 85 | 450 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20373 | yes | 5.12 | 0 |
| SoliSpirit-all | 7807 | yes | 3.76 | 0 |
| Epodonios-all | 7338 | yes | 3.93 | 0 |
| Surfboard-tg-mixed | 6713 | yes | 3.72 | 0 |
| DeltaKronecker-all | 5881 | yes | 4.73 | 0 |
| barry-far-vless | 5853 | yes | 2.12 | 0 |
| Surfboard-tg-vless | 5446 | yes | 4.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.91 | 0 |
| mahdibland-V2RayAggregator | 5191 | yes | 2.82 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 65 |
| geo | 48 |
| 204 | 42 |
| cn-block | 16 |
