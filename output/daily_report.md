# AutoNodes 每日报告

生成时间：2026-06-24 19:45:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 76859 |
| 去重后节点数 | 22597 |
| TCP 可达数 | 3000 |
| 真测通过数 | 401 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22597 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 46.5 |
| geo | 1.4 |
| probe | 58.5 |
| real_test | 126.3 |
| tcp | 29.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 2 | 1 | 66.7% |
| shadowsocks | 124 | 101 | 23 | 81.5% |
| trojan | 124 | 75 | 49 | 60.5% |
| vless | 287 | 183 | 104 | 63.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 72 |
| 204:TimeoutError | 28 |
| cn-block:TimeoutError | 24 |
| 204:ProxyError | 15 |
| cn-block:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| geo:ClientOSError | 4 |
| speed:ProxyError | 4 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4157 |
| ConnectionRefusedError | 627 |
| gaierror | 204 |
| OSError | 105 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | prefer | 36 | 1.0 | 82 |
| Surfboard-tg-mixed | 0.804 | prefer | 226 | 0.726 | 5375 |
| Au1rxx-base64 | 0.746 | prefer | 60 | 0.75 | 114 |
| mheidari-all | 0.71 | prefer | 190 | 0.632 | 15681 |
| DeltaKronecker-all | 0.61 | observe | 64 | 0.531 | 6644 |
| nscl5-all | 0.301 | observe | 1 | 1.0 | 1140 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4745 |
| Epodonios-all | 0.255 | observe | 0 | None | 8092 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3980 |

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
| DeltaKronecker-all | 0.531 | 34 | 30 | 64 |
| mheidari-all | 0.632 | 120 | 70 | 190 |
| Surfboard-tg-mixed | 0.726 | 164 | 62 | 226 |
| Au1rxx-base64 | 0.75 | 45 | 15 | 60 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15681 | yes | 3.8 | 0 |
| Epodonios-all | 8092 | yes | 2.05 | 0 |
| SoliSpirit-all | 7510 | yes | 2.7 | 0 |
| DeltaKronecker-all | 6644 | yes | 3.97 | 0 |
| Surfboard-tg-mixed | 5375 | yes | 2.78 | 0 |
| barry-far-vless | 4852 | yes | 1.54 | 0 |
| 10ium-ScrapeCategorize-Vless | 4745 | yes | 1.88 | 0 |
| mahdibland-V2RayAggregator | 4710 | yes | 1.5 | 0 |
| Surfboard-tg-vless | 4084 | yes | 2.28 | 0 |
| MatinGhanbari-all-sub | 3980 | yes | 1.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 83 |
| 204 | 48 |
| cn-block | 36 |
| geo | 10 |
