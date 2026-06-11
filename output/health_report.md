# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.2.0 |
| 更新时间 | 2026-06-11 23:38:12 |
| 运行耗时 | 202.4s |
| 订阅源总数 | 44 |
| 健康订阅源 | 44 |
| 原始节点 | 39955 |
| 去重后节点 | 15027 |
| TCP 可达 | 1500 |
| 真实可用 | 316 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 15027 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.2 |
| geo | 1.2 |
| tcp | 36.8 |
| real_test | 136.4 |
| generate | 24.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 20391 |
| shadowsocks | 7985 |
| trojan | 6037 |
| vmess | 5130 |
| hysteria2 | 184 |
| shadowsocksr | 90 |
| http | 86 |
| socks | 41 |
| hysteria | 6 |
| anytls | 4 |
| tuic | 1 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- |
| 57.41 | shadowsocks | 209.4 | 438.4 | Au1rxx-base64 | 108.181.0.177 |
| 57.26 | shadowsocks | 445.6 | 196.8 | Au1rxx-base64 | 149.22.87.240 |
| 57.07 | shadowsocks | 446.2 | 201.7 | Au1rxx-base64 | 149.22.87.204 |
| 56.77 | shadowsocks | 229.2 | 497.2 | Au1rxx-base64 | 108.181.118.10 |
| 56.57 | shadowsocks | 446.1 | 215.3 | Au1rxx-base64 | 149.22.87.241 |
| 56.41 | shadowsocks | 240.2 | 476.0 | Au1rxx-base64 | 173.244.56.9 |
| 56.27 | shadowsocks | 244.8 | 563.6 | Au1rxx-base64 | 216.105.168.18 |
| 55.03 | shadowsocks | 282.9 | 603.0 | Au1rxx-base64 | 173.244.56.6 |
| 54.44 | shadowsocks | 301.1 | 529.9 | Au1rxx-base64 | 149.22.95.183 |
| 54.15 | shadowsocks | 482.4 | 248.4 | Au1rxx-base64 | 103.106.228.175 |
| 53.38 | vmess | 209.8 | 448.7 | Barabama-yudou | 82.198.246.233 |
| 53.19 | shadowsocks | 339.6 | 597.0 | Au1rxx-base64 | 156.146.38.167 |
| 53.19 | shadowsocks | 339.6 | 592.7 | Au1rxx-base64 | 156.146.38.169 |
| 53.17 | shadowsocks | 340.3 | 608.3 | Au1rxx-base64 | 156.146.38.168 |
| 53.12 | shadowsocks | 341.8 | 612.9 | Au1rxx-base64 | 156.146.38.170 |
| 51.96 | shadowsocks | 377.6 | 685.3 | Au1rxx-base64 | 149.28.255.6 |
| 51.69 | vless | 562.5 | 204.6 | Au1rxx-base64 | 103.134.35.107 |
| 51.55 | shadowsocks | 226.1 | 497.3 | mheidari-all | 192.3.196.182 |
| 51.04 | vless | 359.9 | 748.5 | Au1rxx-base64 | 15.204.97.214 |
| 50.99 | vless | 576.1 | 211.2 | Au1rxx-base64 | 13.193.215.148 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | 0.977 | 43 | 52 | prefer |
| Au1rxx-base64 | 0.551 | 0.549 | 71 | 88 | observe |
| roosterkid-openproxylist-v2ray | 0.329 | 0.31 | 29 | 150 | observe |
| Surfboard-tg-mixed | 0.286 | 0.205 | 737 | 4225 | observe |
| mheidari-all | 0.259 | 0.172 | 93 | 2000 | observe |
| Epodonios-all | 0.255 | None | 0 | 3000 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3000 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3224 | observe |
| barry-far-vless | 0.255 | None | 0 | 2000 | observe |
| DeltaKronecker-all | 0.213 | 0.132 | 441 | 4660 | downweight |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |
| barry-far-Sub2 | 0.195 | None | 0 | 501 | observe |
| barry-far-Sub1 | 0.194 | None | 0 | 473 | observe |
| mfuu-v2ray | 0.19 | None | 0 | 387 | observe |
| Barabama-yudou | 0.186 | 0.333 | 3 | 166 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ClientOSError | - | 557 |
| 204 | ProxyError | - | 317 |
| geo | status | 429 | 114 |
| 204 | TimeoutError | - | 62 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | - | 52 |
| geo | status | 403 | 25 |
| cn-block | ClientOSError | - | 12 |
| cn-block | TimeoutError | - | 11 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | - | 8 |
| speed | ClientOSError | - | 6 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | - | 3 |
| speed | TimeoutError | - | 3 |
| geo | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] decode config at /tmp/sb-ersjev1s/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] decode config at /tmp/sb-xju01anp/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 288 | 300 | - |
| global | False | 298 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
