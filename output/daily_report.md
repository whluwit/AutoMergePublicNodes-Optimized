# AutoNodes 每日报告

生成时间：2026-09-06 19:59:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 94131 |
| 去重后节点数 | 24614 |
| TCP 可达数 | 3000 |
| 真测通过数 | 538 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24614 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 49.1 |
| geo | 1.4 |
| probe | 86.0 |
| real_test | 121.8 |
| tcp | 41.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 25 | 18 | 7 | 72.0% |
| hysteria2 | 26 | 25 | 1 | 96.2% |
| shadowsocks | 159 | 151 | 8 | 95.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 34 | 23 | 11 | 67.6% |
| vless | 442 | 315 | 127 | 71.3% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 48 |
| geo:ClientOSError | 34 |
| cn-block:TimeoutError | 21 |
| 204:TimeoutError | 17 |
| 204:ProxyConnectionError | 10 |
| speed:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| speed:TimeoutError | 5 |
| geo:ProxyError | 4 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5437 |
| ConnectionRefusedError | 1036 |
| gaierror | 451 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | prefer | 321 | 0.894 | 1861 |
| Surfboard-tg-mixed | 0.807 | prefer | 141 | 0.73 | 7357 |
| zhangkai | 0.766 | prefer | 23 | 0.783 | 144 |
| mheidari-all | 0.703 | prefer | 202 | 0.624 | 21188 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 5750 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 5856 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4791 |
| Epodonios-all | 0.255 | observe | 0 | None | 7817 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8260 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
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
| tg-oneclickvpnkeys | 0.25 | 1 | 3 | 4 |
| mheidari-all | 0.624 | 126 | 76 | 202 |
| Surfboard-tg-mixed | 0.73 | 103 | 38 | 141 |
| zhangkai | 0.783 | 18 | 5 | 23 |
| Au1rxx-base64 | 0.894 | 287 | 34 | 321 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21188 | yes | 5.37 | 0 |
| SoliSpirit-all | 8260 | yes | 1.67 | 0 |
| Epodonios-all | 7817 | yes | 3.04 | 0 |
| Surfboard-tg-mixed | 7357 | yes | 4.55 | 0 |
| barry-far-vless | 6306 | yes | 0.92 | 0 |
| Surfboard-tg-vless | 6090 | yes | 3.75 | 0 |
| DeltaKronecker-all | 5856 | yes | 4.29 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 1.34 | 0 |
| 10ium-ScrapeCategorize-Vless | 4791 | yes | 0.67 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 2.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 71 |
| geo | 43 |
| 204 | 33 |
| speed | 10 |
