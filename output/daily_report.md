# AutoNodes 每日报告

生成时间：2026-06-28 03:02:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 76048 |
| 去重后节点数 | 23107 |
| TCP 可达数 | 3000 |
| 真测通过数 | 555 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23107 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 34.0 |
| geo | 1.4 |
| probe | 52.0 |
| real_test | 112.6 |
| tcp | 31.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 134 | 114 | 20 | 85.1% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 201 | 165 | 36 | 82.1% |
| vless | 403 | 230 | 173 | 57.1% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 95 |
| geo:TimeoutError | 67 |
| geo:ClientOSError | 18 |
| cn-block:TimeoutError | 12 |
| 204:ClientOSError | 11 |
| speed:TimeoutError | 6 |
| cn-block:ClientOSError | 6 |
| 204:TimeoutError | 6 |
| 204:ProxyError | 5 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4386 |
| ConnectionRefusedError | 653 |
| gaierror | 171 |
| OSError | 127 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.882 | prefer | 291 | 0.804 | 5007 |
| mheidari-all | 0.734 | prefer | 235 | 0.655 | 16017 |
| Au1rxx-base64 | 0.711 | prefer | 66 | 0.712 | 122 |
| DeltaKronecker-all | 0.612 | observe | 154 | 0.532 | 6822 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4579 |
| Epodonios-all | 0.255 | observe | 0 | None | 7553 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3982 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7010 |

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
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.532 | 82 | 72 | 154 |
| mheidari-all | 0.655 | 154 | 81 | 235 |
| Au1rxx-base64 | 0.712 | 47 | 19 | 66 |
| Surfboard-tg-mixed | 0.804 | 234 | 57 | 291 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16017 | yes | 3.68 | 0 |
| Epodonios-all | 7553 | yes | 2.55 | 0 |
| SoliSpirit-all | 7010 | yes | 2.86 | 0 |
| DeltaKronecker-all | 6822 | yes | 3.8 | 0 |
| mahdibland-V2RayAggregator | 5287 | yes | 1.79 | 0 |
| Surfboard-tg-mixed | 5007 | yes | 2.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4579 | yes | 1.81 | 0 |
| barry-far-vless | 4479 | yes | 2.14 | 0 |
| MatinGhanbari-all-sub | 3982 | yes | 2.42 | 0 |
| Surfboard-tg-vless | 3707 | yes | 1.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 101 |
| geo | 87 |
| 204 | 22 |
| cn-block | 19 |
