# AutoNodes 每日报告

生成时间：2026-06-29 03:04:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 75922 |
| 去重后节点数 | 22955 |
| TCP 可达数 | 3000 |
| 真测通过数 | 637 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22955 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 30.3 |
| geo | 1.4 |
| probe | 55.5 |
| real_test | 140.2 |
| tcp | 30.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 111 | 98 | 13 | 88.3% |
| trojan | 88 | 68 | 20 | 77.3% |
| vless | 825 | 430 | 395 | 52.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 179 |
| speed:ClientOSError | 130 |
| geo:ClientOSError | 59 |
| cn-block:TimeoutError | 19 |
| speed:TimeoutError | 18 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 7 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4193 |
| ConnectionRefusedError | 645 |
| gaierror | 259 |
| OSError | 131 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.904 | prefer | 368 | 0.826 | 16006 |
| Surfboard-tg-mixed | 0.799 | prefer | 268 | 0.72 | 5165 |
| Au1rxx-base64 | 0.617 | observe | 42 | 0.619 | 85 |
| nscl5-all | 0.358 | observe | 2 | 1.0 | 1166 |
| DeltaKronecker-all | 0.299 | observe | 349 | 0.218 | 6788 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7662 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6972 |

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
| tg-Parsashonam | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.218 | 76 | 273 | 349 |
| Au1rxx-base64 | 0.619 | 26 | 16 | 42 |
| Surfboard-tg-mixed | 0.72 | 193 | 75 | 268 |
| mheidari-all | 0.826 | 304 | 64 | 368 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16006 | yes | 3.21 | 0 |
| Epodonios-all | 7662 | yes | 1.91 | 0 |
| SoliSpirit-all | 6972 | yes | 1.91 | 0 |
| DeltaKronecker-all | 6788 | yes | 2.58 | 0 |
| mahdibland-V2RayAggregator | 5325 | yes | 1.53 | 0 |
| Surfboard-tg-mixed | 5165 | yes | 2.2 | 0 |
| barry-far-vless | 4390 | yes | 1.11 | 0 |
| 10ium-ScrapeCategorize-Vless | 4327 | yes | 1.34 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.18 | 0 |
| Surfboard-tg-vless | 3804 | yes | 2.02 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 238 |
| speed | 148 |
| cn-block | 30 |
| 204 | 12 |
