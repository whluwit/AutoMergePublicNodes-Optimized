# AutoNodes 每日报告

生成时间：2026-09-09 03:00:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85506 |
| 去重后节点数 | 22889 |
| TCP 可达数 | 3000 |
| 真测通过数 | 531 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22889 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 80.2 |
| geo | 1.4 |
| probe | 328.6 |
| real_test | 453.5 |
| tcp | 38.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 51 | 26 | 25 | 51.0% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 176 | 159 | 17 | 90.3% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 59 | 47 | 12 | 79.7% |
| vless | 503 | 284 | 219 | 56.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 114 |
| geo:ClientOSError | 34 |
| speed:TimeoutError | 29 |
| 204:ProxyError | 27 |
| speed:ClientOSError | 24 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 11 |
| 204:ProxyConnectionError | 8 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5054 |
| ConnectionRefusedError | 891 |
| gaierror | 507 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.97 | prefer | 264 | 0.905 | 1690 |
| Surfboard-tg-mixed | 0.838 | prefer | 122 | 0.762 | 7518 |
| mheidari-all | 0.774 | prefer | 119 | 0.697 | 16648 |
| ermaozi-get_subscribe | 0.618 | observe | 19 | 0.632 | 473 |
| ermaozi | 0.49 | observe | 34 | 0.471 | 442 |
| DeltaKronecker-all | 0.431 | observe | 243 | 0.35 | 6097 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 176 |
| Epodonios-all | 0.255 | observe | 0 | None | 7969 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.35 | 85 | 158 | 243 |
| ermaozi | 0.471 | 16 | 18 | 34 |
| ermaozi-get_subscribe | 0.632 | 12 | 7 | 19 |
| mheidari-all | 0.697 | 83 | 36 | 119 |
| Surfboard-tg-mixed | 0.762 | 93 | 29 | 122 |
| Au1rxx-base64 | 0.905 | 239 | 25 | 264 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16648 | yes | 5.58 | 0 |
| SoliSpirit-all | 8719 | yes | 3.75 | 0 |
| Epodonios-all | 7969 | yes | 4.79 | 0 |
| Surfboard-tg-mixed | 7518 | yes | 4.49 | 0 |
| barry-far-vless | 6393 | yes | 2.86 | 0 |
| Surfboard-tg-vless | 6168 | yes | 3.7 | 0 |
| DeltaKronecker-all | 6097 | yes | 5.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 2.54 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 2.81 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 149 |
| speed | 55 |
| 204 | 50 |
| cn-block | 22 |
