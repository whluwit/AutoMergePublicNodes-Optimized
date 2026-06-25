# AutoNodes 每日报告

生成时间：2026-06-25 08:58:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 82391 |
| 去重后节点数 | 22466 |
| TCP 可达数 | 3000 |
| 真测通过数 | 388 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22466 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| generate | 42.6 |
| geo | 1.3 |
| probe | 56.0 |
| real_test | 111.3 |
| tcp | 29.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 124 | 102 | 22 | 82.3% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 143 | 104 | 39 | 72.7% |
| vless | 291 | 138 | 153 | 47.4% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 95 |
| geo:TimeoutError | 26 |
| 204:TimeoutError | 23 |
| cn-block:TimeoutError | 18 |
| 204:ProxyError | 12 |
| geo:ClientOSError | 10 |
| 204:ClientOSError | 10 |
| cn-block:ClientOSError | 9 |
| speed:TimeoutError | 6 |
| speed:ProxyError | 5 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4168 |
| ConnectionRefusedError | 612 |
| gaierror | 151 |
| OSError | 105 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | prefer | 36 | 1.0 | 82 |
| Surfboard-tg-mixed | 0.749 | prefer | 237 | 0.671 | 5184 |
| Au1rxx-base64 | 0.693 | observe | 59 | 0.695 | 111 |
| mheidari-all | 0.671 | observe | 157 | 0.592 | 15925 |
| DeltaKronecker-all | 0.594 | observe | 109 | 0.514 | 12590 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| nscl5-all | 0.3 | observe | 1 | 1.0 | 1136 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4787 |
| Epodonios-all | 0.255 | observe | 0 | None | 7823 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-ISVvpn | 0.175 | observe | 0 | None | 0 | 10 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.514 | 56 | 53 | 109 |
| mheidari-all | 0.592 | 93 | 64 | 157 |
| Surfboard-tg-mixed | 0.671 | 159 | 78 | 237 |
| Au1rxx-base64 | 0.695 | 41 | 18 | 59 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15925 | yes | 2.53 | 0 |
| DeltaKronecker-all | 12590 | yes | 2.98 | 0 |
| Epodonios-all | 7823 | yes | 1.42 | 0 |
| SoliSpirit-all | 7164 | yes | 1.67 | 0 |
| Surfboard-tg-mixed | 5184 | yes | 0.56 | 0 |
| mahdibland-V2RayAggregator | 5133 | yes | 1.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 4787 | yes | 1.36 | 0 |
| barry-far-vless | 4701 | yes | 1.47 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.73 | 0 |
| Surfboard-tg-vless | 3909 | yes | 1.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 106 |
| 204 | 45 |
| geo | 36 |
| cn-block | 27 |
