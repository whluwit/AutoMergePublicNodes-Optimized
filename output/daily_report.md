# AutoNodes 每日报告

生成时间：2026-09-09 20:29:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83566 |
| 去重后节点数 | 22095 |
| TCP 可达数 | 3000 |
| 真测通过数 | 440 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22095 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 86.6 |
| geo | 1.4 |
| probe | 275.0 |
| real_test | 220.6 |
| tcp | 36.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 23 | 4 | 85.2% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 168 | 151 | 17 | 89.9% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 28 | 15 | 13 | 53.6% |
| vless | 281 | 228 | 53 | 81.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 16 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 10 |
| speed:ClientOSError | 7 |
| geo:ClientOSError | 6 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| speed:TimeoutError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4534 |
| ConnectionRefusedError | 882 |
| gaierror | 389 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | prefer | 305 | 0.918 | 1527 |
| mheidari-all | 0.92 | prefer | 23 | 0.87 | 16196 |
| ermaozi | 0.844 | prefer | 27 | 0.852 | 410 |
| Surfboard-tg-mixed | 0.782 | prefer | 139 | 0.705 | 7393 |
| DeltaKronecker-all | 0.642 | observe | 30 | 0.567 | 5187 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 147 |
| Epodonios-all | 0.255 | observe | 0 | None | 7839 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8955 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6033 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.567 | 17 | 13 | 30 |
| Surfboard-tg-mixed | 0.705 | 98 | 41 | 139 |
| ermaozi | 0.852 | 23 | 4 | 27 |
| mheidari-all | 0.87 | 20 | 3 | 23 |
| Au1rxx-base64 | 0.918 | 280 | 25 | 305 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16196 | yes | 4.58 | 0 |
| SoliSpirit-all | 8955 | yes | 1.31 | 0 |
| Epodonios-all | 7839 | yes | 4.92 | 0 |
| Surfboard-tg-mixed | 7393 | yes | 3.81 | 0 |
| barry-far-vless | 6253 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 6033 | yes | 5.11 | 0 |
| DeltaKronecker-all | 5187 | yes | 5.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 0.45 | 0 |
| mahdibland-V2RayAggregator | 4247 | yes | 2.86 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 36 |
| cn-block | 29 |
| geo | 12 |
| speed | 10 |
