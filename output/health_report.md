# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.2.0 |
| 更新时间 | 2026-06-11 23:58:32 |
| 运行耗时 | 209.3s |
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
| fetch | 3.0 |
| geo | 1.2 |
| tcp | 34.8 |
| real_test | 144.0 |
| generate | 26.3 |

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
| 57.66 | shadowsocks | 439.9 | 196.1 | Au1rxx-base64 | 149.22.87.240 |
| 57.57 | shadowsocks | 439.9 | 198.7 | Au1rxx-base64 | 149.22.87.204 |
| 57.51 | shadowsocks | 441.9 | 198.3 | Au1rxx-base64 | 149.22.87.241 |
| 57.19 | shadowsocks | 221.6 | 468.5 | Au1rxx-base64 | 108.181.0.177 |
| 56.71 | shadowsocks | 236.5 | 512.5 | Au1rxx-base64 | 108.181.118.10 |
| 56.57 | shadowsocks | 240.8 | 483.3 | Au1rxx-base64 | 173.244.56.9 |
| 54.91 | shadowsocks | 292.0 | 625.6 | Au1rxx-base64 | 173.244.56.6 |
| 54.62 | shadowsocks | 301.1 | 436.3 | Au1rxx-base64 | 149.22.95.183 |
| 53.52 | shadowsocks | 335.0 | 595.0 | Au1rxx-base64 | 156.146.38.170 |
| 53.48 | vmess | 251.7 | 567.8 | Barabama-yudou | 82.198.246.233 |
| 53.37 | shadowsocks | 339.6 | 607.0 | Au1rxx-base64 | 156.146.38.168 |
| 53.14 | shadowsocks | 346.6 | 620.5 | Au1rxx-base64 | 156.146.38.169 |
| 53.03 | shadowsocks | 350.2 | 620.6 | Au1rxx-base64 | 156.146.38.167 |
| 51.89 | vless | 572.4 | 207.2 | Au1rxx-base64 | 13.193.215.148 |
| 51.56 | vless | 606.0 | 187.4 | Au1rxx-base64 | 103.134.35.107 |
| 51.51 | shadowsocks | 229.7 | 499.1 | mheidari-all | 192.3.196.182 |
| 51.31 | vless | 370.9 | 803.0 | Au1rxx-base64 | 15.204.97.214 |
| 51.25 | vless | 373.1 | 639.9 | Au1rxx-base64 | 34.222.27.94 |
| 50.41 | shadowsocks | 213.0 | 446.2 | DeltaKronecker-all | 107.172.219.230 |
| 50.1 | shadowsocks | 440.5 | 900.2 | Au1rxx-base64 | 149.28.255.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | 0.977 | 43 | 52 | prefer |
| Au1rxx-base64 | 0.524 | 0.521 | 71 | 88 | observe |
| mheidari-all | 0.303 | 0.217 | 92 | 2000 | observe |
| roosterkid-openproxylist-v2ray | 0.296 | 0.276 | 29 | 150 | observe |
| Surfboard-tg-mixed | 0.28 | 0.199 | 752 | 4225 | observe |
| Epodonios-all | 0.255 | None | 0 | 3000 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3000 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3224 | observe |
| barry-far-vless | 0.255 | None | 0 | 2000 | observe |
| DeltaKronecker-all | 0.218 | 0.136 | 426 | 4660 | downweight |
| Barabama-yudou | 0.214 | 0.5 | 2 | 166 | observe |
| barry-far-Sub2 | 0.195 | None | 0 | 501 | observe |
| barry-far-Sub1 | 0.194 | None | 0 | 473 | observe |
| mfuu-v2ray | 0.19 | None | 0 | 387 | observe |
| MatinGhanbari-super-sub | 0.183 | None | 0 | 199 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ClientOSError | - | 492 |
| 204 | ProxyError | - | 378 |
| geo | status | 429 | 86 |
| 204 | TimeoutError | - | 85 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | - | 52 |
| geo | status | 403 | 37 |
| cn-block | ClientOSError | - | 10 |
| cn-block | TimeoutError | - | 9 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | - | 8 |
| speed | ClientOSError | - | 6 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | - | 3 |
| speed | TimeoutError | - | 3 |
| geo | TimeoutError | - | 3 |
| geo | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] decode config at /tmp/sb-devq_q95/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 280 | - |
| global | False | 300 | 284 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
