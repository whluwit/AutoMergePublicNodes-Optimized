# AutoNodes 每日报告

生成时间：2026-06-24 02:52:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 76548 |
| 去重后节点数 | 22515 |
| TCP 可达数 | 3000 |
| 真测通过数 | 568 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22515 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 22.0 |
| geo | 1.4 |
| probe | 53.9 |
| real_test | 129.8 |
| tcp | 29.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 50 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 137 | 127 | 10 | 92.7% |
| socks | 18 | 16 | 2 | 88.9% |
| trojan | 171 | 150 | 21 | 87.7% |
| vless | 426 | 219 | 207 | 51.4% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 95 |
| geo:TimeoutError | 61 |
| speed:TimeoutError | 26 |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 10 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 1 |
| geo:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4072 |
| ConnectionRefusedError | 618 |
| gaierror | 225 |
| OSError | 105 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | prefer | 50 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.906 | prefer | 325 | 0.828 | 5422 |
| Au1rxx-base64 | 0.695 | observe | 85 | 0.694 | 133 |
| mheidari-all | 0.636 | observe | 221 | 0.557 | 15461 |
| DeltaKronecker-all | 0.596 | observe | 124 | 0.516 | 6437 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| nscl5-all | 0.301 | observe | 1 | 1.0 | 1140 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4576 |
| Epodonios-all | 0.255 | observe | 0 | None | 8143 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3979 |

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
| tg-ISVvpn | 0.175 | observe | 0 | None | 0 | 9 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.516 | 64 | 60 | 124 |
| mheidari-all | 0.557 | 123 | 98 | 221 |
| Au1rxx-base64 | 0.694 | 59 | 26 | 85 |
| Surfboard-tg-mixed | 0.828 | 269 | 56 | 325 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 50 | 0 | 50 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15461 | yes | 3.41 | 0 |
| Epodonios-all | 8143 | yes | 2.94 | 0 |
| SoliSpirit-all | 7420 | yes | 2.63 | 0 |
| DeltaKronecker-all | 6437 | yes | 4.72 | 0 |
| Surfboard-tg-mixed | 5422 | yes | 2.57 | 0 |
| barry-far-vless | 4932 | yes | 1.14 | 0 |
| mahdibland-V2RayAggregator | 4664 | yes | 1.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4576 | yes | 0.96 | 0 |
| Surfboard-tg-vless | 4123 | yes | 2.38 | 0 |
| MatinGhanbari-all-sub | 3979 | yes | 1.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 121 |
| geo | 72 |
| 204 | 27 |
| cn-block | 20 |
