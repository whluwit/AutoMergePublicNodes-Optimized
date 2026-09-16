# AutoNodes 每日报告

生成时间：2026-09-16 20:57:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 89382 |
| 去重后节点数 | 24518 |
| TCP 可达数 | 3000 |
| 真测通过数 | 411 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24518 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 77.0 |
| geo | 1.4 |
| probe | 282.3 |
| real_test | 211.0 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 18 | 12 | 6 | 66.7% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 155 | 144 | 11 | 92.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 35 | 26 | 9 | 74.3% |
| vless | 289 | 205 | 84 | 70.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 28 |
| cn-block:TimeoutError | 23 |
| speed:ClientOSError | 11 |
| 204:ProxyError | 10 |
| 204:TimeoutError | 10 |
| cn-block:ClientOSError | 8 |
| speed:TimeoutError | 8 |
| geo:TimeoutError | 7 |
| cn-block:ProxyError | 4 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6164 |
| ConnectionRefusedError | 907 |
| gaierror | 244 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.91 | prefer | 268 | 0.847 | 1651 |
| mheidari-all | 0.891 | prefer | 72 | 0.819 | 17985 |
| Surfboard-tg-mixed | 0.819 | prefer | 132 | 0.742 | 7470 |
| ermaozi | 0.558 | observe | 11 | 0.818 | 353 |
| DeltaKronecker-all | 0.547 | observe | 28 | 0.464 | 6081 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4234 |
| tg-oneclickvpnkeys | 0.274 | observe | 3 | 0.667 | 140 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7934 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| DeltaKronecker-all | 0.464 | 13 | 15 | 28 |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.742 | 98 | 34 | 132 |
| ermaozi | 0.818 | 9 | 2 | 11 |
| mheidari-all | 0.819 | 59 | 13 | 72 |
| Au1rxx-base64 | 0.847 | 227 | 41 | 268 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17985 | yes | 3.58 | 0 |
| SoliSpirit-all | 8999 | yes | 2.9 | 0 |
| Epodonios-all | 7934 | yes | 2.02 | 0 |
| Surfboard-tg-mixed | 7470 | yes | 3.81 | 0 |
| barry-far-vless | 6197 | yes | 1.48 | 0 |
| DeltaKronecker-all | 6081 | yes | 3.21 | 0 |
| Surfboard-tg-vless | 5979 | yes | 2.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 1.78 | 0 |
| mahdibland-V2RayAggregator | 4234 | yes | 0.49 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.91 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 35 |
| geo | 35 |
| 204 | 21 |
| speed | 20 |
