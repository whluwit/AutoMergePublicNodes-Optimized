# AutoNodes 每日报告

生成时间：2026-09-09 10:50:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85031 |
| 去重后节点数 | 22037 |
| TCP 可达数 | 3000 |
| 真测通过数 | 489 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22037 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 80.3 |
| geo | 1.4 |
| probe | 227.9 |
| real_test | 270.2 |
| tcp | 36.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 52 | 32 | 20 | 61.5% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 174 | 166 | 8 | 95.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 22 | 14 | 8 | 63.6% |
| vless | 328 | 256 | 72 | 78.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 29 |
| geo:ClientOSError | 24 |
| 204:TimeoutError | 23 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 4 |
| speed:ProxyError | 4 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| speed:ClientOSError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:39336: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4759 |
| ConnectionRefusedError | 874 |
| gaierror | 400 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | prefer | 248 | 0.911 | 1749 |
| mheidari-all | 0.856 | prefer | 114 | 0.781 | 16452 |
| Surfboard-tg-mixed | 0.852 | prefer | 165 | 0.776 | 7479 |
| DeltaKronecker-all | 0.66 | observe | 16 | 0.688 | 5187 |
| ermaozi-get_subscribe | 0.644 | observe | 22 | 0.636 | 473 |
| ermaozi | 0.635 | observe | 32 | 0.625 | 442 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 180 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4795 |
| Epodonios-all | 0.255 | observe | 0 | None | 7964 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.625 | 20 | 12 | 32 |
| ermaozi-get_subscribe | 0.636 | 14 | 8 | 22 |
| DeltaKronecker-all | 0.688 | 11 | 5 | 16 |
| Surfboard-tg-mixed | 0.776 | 128 | 37 | 165 |
| mheidari-all | 0.781 | 89 | 25 | 114 |
| Au1rxx-base64 | 0.911 | 226 | 22 | 248 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16452 | yes | 4.86 | 0 |
| SoliSpirit-all | 9095 | yes | 1.41 | 0 |
| Epodonios-all | 7964 | yes | 5.3 | 0 |
| Surfboard-tg-mixed | 7479 | yes | 5.52 | 0 |
| barry-far-vless | 6404 | yes | 0.85 | 0 |
| Surfboard-tg-vless | 6181 | yes | 3.47 | 0 |
| DeltaKronecker-all | 5187 | yes | 3.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 0.58 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 0.46 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 55 |
| geo | 27 |
| cn-block | 16 |
| speed | 11 |
| sing-box exited 1 | 1 |
