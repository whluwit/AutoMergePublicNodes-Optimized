# AutoNodes 每日报告

生成时间：2026-09-08 20:48:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 85321 |
| 去重后节点数 | 22703 |
| TCP 可达数 | 3000 |
| 真测通过数 | 514 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22703 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 77.2 |
| geo | 1.4 |
| probe | 289.7 |
| real_test | 256.2 |
| tcp | 38.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 34 | 24 | 10 | 70.6% |
| hysteria2 | 20 | 17 | 3 | 85.0% |
| shadowsocks | 158 | 144 | 14 | 91.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 20 | 17 | 3 | 85.0% |
| vless | 378 | 308 | 70 | 81.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 18 |
| geo:ClientOSError | 17 |
| 204:ProxyError | 13 |
| cn-block:ClientOSError | 9 |
| speed:ClientOSError | 7 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| geo:TimeoutError | 3 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4961 |
| ConnectionRefusedError | 872 |
| gaierror | 454 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 1.0 | prefer | 28 | 0.964 | 6097 |
| Au1rxx-base64 | 0.979 | prefer | 290 | 0.914 | 1700 |
| mheidari-all | 0.855 | prefer | 100 | 0.78 | 16416 |
| Surfboard-tg-mixed | 0.818 | prefer | 158 | 0.741 | 7545 |
| ermaozi | 0.719 | prefer | 35 | 0.714 | 409 |
| ermaozi-get_subscribe | 0.272 | observe | 1 | 1.0 | 420 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| Epodonios-all | 0.255 | observe | 0 | None | 7999 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8578 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.714 | 25 | 10 | 35 |
| Surfboard-tg-mixed | 0.741 | 117 | 41 | 158 |
| mheidari-all | 0.78 | 78 | 22 | 100 |
| Au1rxx-base64 | 0.914 | 265 | 25 | 290 |
| DeltaKronecker-all | 0.964 | 27 | 1 | 28 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16416 | yes | 4.65 | 0 |
| SoliSpirit-all | 8578 | yes | 3.0 | 0 |
| Epodonios-all | 7999 | yes | 3.11 | 0 |
| Surfboard-tg-mixed | 7545 | yes | 3.7 | 0 |
| barry-far-vless | 6497 | yes | 1.62 | 0 |
| Surfboard-tg-vless | 6277 | yes | 4.18 | 0 |
| DeltaKronecker-all | 6097 | yes | 4.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 1.17 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 2.33 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.7 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 40 |
| cn-block | 28 |
| geo | 20 |
| speed | 13 |
