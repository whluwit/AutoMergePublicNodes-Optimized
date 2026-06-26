# AutoNodes 每日报告

生成时间：2026-06-26 02:58:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82426 |
| 去重后节点数 | 22884 |
| TCP 可达数 | 3000 |
| 真测通过数 | 556 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22884 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 34.5 |
| geo | 1.3 |
| probe | 61.1 |
| real_test | 137.1 |
| tcp | 30.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 140 | 128 | 12 | 91.4% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 134 | 118 | 16 | 88.1% |
| vless | 571 | 265 | 306 | 46.4% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 155 |
| geo:TimeoutError | 114 |
| speed:TimeoutError | 25 |
| cn-block:TimeoutError | 12 |
| geo:ClientOSError | 7 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 4 |
| 204:TimeoutError | 4 |
| geo:status | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4162 |
| ConnectionRefusedError | 640 |
| gaierror | 233 |
| OSError | 118 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | prefer | 36 | 1.0 | 82 |
| Surfboard-tg-mixed | 0.896 | prefer | 281 | 0.819 | 5129 |
| Au1rxx-base64 | 0.758 | prefer | 59 | 0.763 | 109 |
| mheidari-all | 0.716 | prefer | 289 | 0.637 | 16097 |
| nscl5-all | 0.358 | observe | 2 | 1.0 | 1175 |
| DeltaKronecker-all | 0.34 | observe | 221 | 0.258 | 12590 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4787 |
| Epodonios-all | 0.255 | observe | 0 | None | 7810 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3982 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.258 | 57 | 164 | 221 |
| mheidari-all | 0.637 | 184 | 105 | 289 |
| Au1rxx-base64 | 0.763 | 45 | 14 | 59 |
| Surfboard-tg-mixed | 0.819 | 230 | 51 | 281 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16097 | yes | 3.13 | 0 |
| DeltaKronecker-all | 12590 | yes | 4.81 | 0 |
| Epodonios-all | 7810 | yes | 2.31 | 0 |
| SoliSpirit-all | 7206 | yes | 2.82 | 0 |
| Surfboard-tg-mixed | 5129 | yes | 2.5 | 0 |
| mahdibland-V2RayAggregator | 5117 | yes | 1.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 4787 | yes | 1.81 | 0 |
| barry-far-vless | 4580 | yes | 2.22 | 0 |
| MatinGhanbari-all-sub | 3982 | yes | 2.31 | 0 |
| Surfboard-tg-vless | 3784 | yes | 1.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 180 |
| geo | 122 |
| cn-block | 18 |
| 204 | 14 |
