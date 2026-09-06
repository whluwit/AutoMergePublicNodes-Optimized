# AutoNodes 每日报告

生成时间：2026-09-06 14:54:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 93779 |
| 去重后节点数 | 24474 |
| TCP 可达数 | 3000 |
| 真测通过数 | 589 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24474 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 29.2 |
| geo | 1.4 |
| probe | 80.7 |
| real_test | 147.8 |
| tcp | 41.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 26 | 26 | 0 | 100.0% |
| hysteria2 | 25 | 24 | 1 | 96.0% |
| shadowsocks | 165 | 157 | 8 | 95.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 45 | 39 | 6 | 86.7% |
| vless | 471 | 337 | 134 | 71.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 37 |
| geo:ClientOSError | 35 |
| cn-block:TimeoutError | 27 |
| 204:TimeoutError | 25 |
| 204:ProxyError | 8 |
| speed:TimeoutError | 7 |
| speed:ClientOSError | 5 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5804 |
| ConnectionRefusedError | 1017 |
| gaierror | 371 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | prefer | 354 | 0.91 | 1876 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.848 | prefer | 162 | 0.772 | 7318 |
| mheidari-all | 0.662 | observe | 192 | 0.583 | 21148 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 5750 |
| tg-oneclickvpnkeys | 0.363 | observe | 3 | 1.0 | 133 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 5856 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4791 |
| Epodonios-all | 0.255 | observe | 0 | None | 7776 |

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
| mheidari-all | 0.583 | 112 | 80 | 192 |
| Surfboard-tg-mixed | 0.772 | 125 | 37 | 162 |
| Au1rxx-base64 | 0.91 | 322 | 32 | 354 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21148 | yes | 3.69 | 0 |
| SoliSpirit-all | 8207 | yes | 2.08 | 0 |
| Epodonios-all | 7776 | yes | 4.28 | 0 |
| Surfboard-tg-mixed | 7318 | yes | 3.87 | 0 |
| barry-far-vless | 6226 | yes | 0.83 | 0 |
| Surfboard-tg-vless | 6005 | yes | 2.65 | 0 |
| DeltaKronecker-all | 5856 | yes | 5.62 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 1.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4791 | yes | 0.53 | 0 |
| mahdibland-V2RayAggregator | 4111 | yes | 2.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 65 |
| geo | 38 |
| 204 | 34 |
| speed | 13 |
