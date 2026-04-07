
每隔一段时间，VPS 圈子里就会炸出一款让人眼前一亮的套餐——不是因为配置多豪华，而是因为它用一个让人有点不敢相信的价格，把以前只有土豪才能玩的高端线路塞到了普通人面前。

DMIT 的 **LAX.Pro.MALIBU**，就是这样一款东西。

年付 $49.9，三网回程 CN2 GIA，洛杉矶机房，原生 IP。很多人看到这个价格的第一反应是：这靠谱吗？其实这不是什么新套餐了，从 2024 年首发到现在已经多次补货，每次上架都迅速售罄，这本身就说明了问题。

这篇文章就好好聊聊：DMIT Malibu 到底是什么、适合谁、和其他套餐比怎么样，以及如果你想买，现在能不能买到。

---

## Malibu 是个什么套餐？

DMIT（全称 DMIT.IO）是一家 2018 年就开始运营的 VPS 商家，纽约注册公司，主打洛杉矶、香港、东京三个数据中心，全系 KVM 虚拟化、AMD EPYC 处理器、企业级 SSD。它最让国内用户感兴趣的地方，是认真做了面向中国大陆的网络优化——CN2 GIA、CMIN2、AS9929 这些在其他商家嘴里都是卖点的词，DMIT 实打实地用在了线路上。

DMIT 的产品线分三档：

- **Premium（Pro 系列）**：三网回程 CN2 GIA，最顶级的中国优化线路
- **Eyeball（EB 系列）**：三网 CMIN2/AS9929 优化，性价比之选
- **Tier 1（T1 系列）**：国际通用路由，适合不需要国内优化的用户

**MALIBU** 就是 Premium 系列旗下的一款限量特供套餐，正式名称 `LAX.AN4.Pro.MALIBU`，属于洛杉矶 CN2 GIA 产品线，但价格比常规 Pro 套餐便宜得多。

配置很简单，也很"够用"：

| 配置项 | 参数 |
|--------|------|
| CPU | 1 vCPU（AMD EPYC） |
| 内存 | 1 GB RAM |
| 硬盘 | 20 GB SSD |
| 月流量 | 1000 GB |
| 带宽 | 1 Gbps |
| IP | 1 IPv4 + 1 IPv6 /64 |
| 线路 | 三网回程 CN2 GIA (AS4809)，电信/联通去程 CN2，移动去程 CMIN2 |
| 价格 | **$49.9/年** |
| 超量策略 | 超出后限速 2Mbps，不停机 |

👉 [点击查看 DMIT Malibu 特价套餐](https://www.dmit.io/aff.php?aff=13832&pid=186)

---

## 这个价格，划算在哪里？

说真的，CN2 GIA 线路一直是 VPS 里的"贵族产品"。搬瓦工的同类线路起步接近 $100/年，稳定归稳定，但价格门槛不低。DMIT Malibu 用差不多一半的钱，提供了同等线路质量，这是它每次补货都能迅速卖光的根本原因。

当然，$49.9 的代价是配置上做了妥协——1核1G，对跑个人博客、搭代理节点、做流媒体解锁完全够，但你要跑数据库密集型应用或者高并发服务，这个配置就有点捉襟见肘了。

DMIT 官方明确表示，Malibu 是**限量特供套餐**，不定期补货，没有就是没有，不是随时都能买到的。如果你看到有货，基本上就是"现在不买以后可能要等很久"的节奏。

另外值得一提的是：**不需要任何优惠码，直接购买就是这个价格**。

---

## 线路测试：用数据说话

选择 CN2 GIA 线路，本质上是在买"晚高峰的稳定性"。很多人用过普通国际线路，晚上 8-11 点打开网页像在走老式 56K 拨号；换了 CN2 GIA 之后，这个时段的体验明显不同。

DMIT LAX.Pro 系列路由（Malibu 同款线路）：

- 电信去程：直连 CN2（AS4809）
- 联通去程：直连 CN2（AS4809）
- 移动去程：CMIN2（AS58807）
- **三网回程：全部走 CN2 GIA（AS4809）**

测试 IP：`154.17.2.1`（可自行 ping 测延迟）

国内到洛杉矶的延迟通常在 150-180ms 区间，对于一个在美西的节点来说，这个数字相当稳定。更关键的是，这个数字在晚高峰时段不会变成 400+ms，这才是 CN2 GIA 的真正价值所在。

---

## DMIT 全系套餐完整对比表

DMIT 的产品线比较丰富，很多人第一次进官网会看得有点懵。以下是覆盖洛杉矶、香港、东京三个机房的完整套餐汇总（数据基于 2026 年 3 月官网更新）：

### 🇺🇸 洛杉矶 LAX — Premium 系列（CN2 GIA）

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|------|
| **MALIBU** ⭐ | 1核 | 1GB | 20GB | 1000GB | 1Gbps | **$49.9/年** |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=186) |
| TINY | 1核 | 2GB | 20GB | 1000GB | 1Gbps | $9.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=237) |
| Pocket | 2核 | 2GB | 40GB | 1500GB | 4Gbps | $14.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=238) |
| STARTER | 2核 | 2GB | 80GB | 3000GB | 10Gbps | $29.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=239) |
| MINI | 4核 | 4GB | 80GB | 5000GB | 10Gbps | $58.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=240) |
| MICRO | 4核 | 4GB | 160GB | 7000GB | 10Gbps | $74.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=241) |
| MEDIUM | 6核 | 8GB | 160GB | 15000GB | 10Gbps | $168.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=242) |
| LARGE | 8核 | 16GB | 320GB | 25000GB | 10Gbps | $338.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=243) |
| GIANT | 12核 | 24GB | 640GB | 50000GB | 10Gbps | $619.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=244) |

### 🇺🇸 洛杉矶 LAX — Eyeball 系列（AS9929/CMIN2）

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|------|
| TINY | 1核 | 2GB | 20GB | 1500GB | 2Gbps | $9.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=245) |
| Pocket | 2核 | 2GB | 40GB | 3000GB | 4Gbps | $14.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=246) |
| STARTER | 2核 | 2GB | 80GB | 5000GB | 10Gbps | $29.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=247) |
| MINI | 4核 | 4GB | 80GB | 10000GB | 10Gbps | $58.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=248) |
| MICRO | 4核 | 4GB | 160GB | 14000GB | 10Gbps | $74.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=249) |
| MEDIUM | 6核 | 8GB | 160GB | 30000GB | 10Gbps | $168.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=250) |
| LARGE | 8核 | 16GB | 320GB | 50000GB | 10Gbps | $338.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=251) |
| GIANT | 12核 | 24GB | 640GB | 100000GB | 10Gbps | $619.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=252) |

> 当前 LAX EB 系列可用优惠码：`LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF`（季付及以上周期享受 20% 永久折扣）

### 🇺🇸 洛杉矶 LAX — Tier 1 系列（国际线路）

**VOLUME 大流量版（AMD EPYC 9005 平台）：**

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|------|
| V2C2G | 2核 | 2GB | 40GB | 5000GB | 10Gbps | $14.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=169) |
| V2C4G | 2核 | 4GB | 80GB | 10000GB | 10Gbps | $23.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=170) |
| V4C4G | 4核 | 4GB | 120GB | 20000GB | 10Gbps | $36.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=171) |
| V4C8G | 4核 | 8GB | 160GB | 40000GB | 10Gbps | $52.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=180) |
| V8C16G | 8核 | 16GB | 240GB | 80000GB | 10Gbps | $119.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=172) |
| V12C24G | 12核 | 24GB | 320GB | 160000GB | 10Gbps | $199.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=173) |

**GENERAL 版（AMD EPYC 9004 平台）：**

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|------|
| WEE | 1核 | 1GB | 20GB | 1000GB | — | $36.90/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=71) |
| TINY | 1核 | 1GB | 20GB | 2000GB | — | $6.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=116) |
| STARTER | 2核 | 2GB | 40GB | 4000GB | 10Gbps | $12.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=117) |
| MINI | 2核 | 4GB | 80GB | 8000GB | 10Gbps | $21.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=118) |
| MICRO | 4核 | 4GB | 120GB | 16000GB | 10Gbps | $32.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=119) |

> LAX T1 系列优惠码：`2025-XMAS-LAX-T1-10-OFF-RECURRING`（10% 永久折扣）；年付 STARTER 及以上可用 `2025-XMAS-LAX-T1-ANNUALLY-EXCL-WEE-TINY-20OFF-RECURRING` 获 20% 永久折扣。

---

### 🇭🇰 香港 HKG — Premium 系列（CN2 GIA）

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|------|
| TINY | 1核 | 1GB | 20GB | 500GB | 1Gbps | $39.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=123) |
| STARTER | 1核 | 2GB | 40GB | 1000GB | 1Gbps | $79.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=124) |
| MINI | 2核 | 2GB | 60GB | 1500GB | 1Gbps | $119.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=125) |
| MICRO | 4核 | 4GB | 80GB | 2000GB | 1Gbps | $159.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=126) |
| MEDIUM | 4核 | 8GB | 160GB | 2500GB | 1Gbps | $179.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=127) |
| LARGE | 8核 | 16GB | 320GB | 3000GB | 1Gbps | $239.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=128) |
| GIANT | 8核 | 24GB | 640GB | 6000GB | 1Gbps | $499.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=129) |

### 🇭🇰 香港 HKG — Eyeball 系列（三网 CMI）

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|------|
| TINYv2 | 1核 | 1GB | 20GB | 1000GB | 1Gbps | $29.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=210) |
| STARTERv2 | 1核 | 2GB | 40GB | 2000GB | 2Gbps | $59.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=211) |
| MINIv2 | 2核 | 2GB | 60GB | 3000GB | 2Gbps | $89.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=212) |
| MICROv2 | 4核 | 4GB | 80GB | 4000GB | 4Gbps | $129.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=213) |
| MEDIUMv2 | 4核 | 8GB | 160GB | 6000GB | 4Gbps | $199.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=214) |
| LARGEv2 | 8核 | 16GB | 320GB | 12000GB | 4Gbps | $389.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=215) |
| GIANTv2 | 8核 | 24GB | 640GB | 24000GB | 4Gbps | $789.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=216) |

### 🇭🇰 香港 HKG — Tier 1 系列（国际线路）

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|
| WEE | 1核 | 1GB | 20GB | 1000GB | $36.90/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=197) |
| TINY | 1核 | 1GB | 20GB | 2000GB | $6.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=198) |
| STARTER | 1核 | 2GB | 40GB | 4000GB | $12.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=199) |
| MINI | 2核 | 2GB | 60GB | 8000GB | $21.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=200) |
| MICRO | 4核 | 4GB | 80GB | 16000GB | $32.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=201) |
| MEDIUM | 4核 | 8GB | 160GB | 32000GB | $49.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=202) |
| LARGE | 8核 | 16GB | 320GB | 64000GB | $99.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=203) |
| GIANT | 8核 | 24GB | 640GB | 128000GB | $199.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=204) |

> 香港 Tier 1 年付优惠码：`HKG-T1-ANNUALLY-45OFF-RECUR`（45% 永久折扣+配置升级）

---

### 🇯🇵 东京 TYO — Premium 系列（CN2 GIA）

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|------|
| TINY | 1核 | 1GB | 20GB | 500GB | 1Gbps | $21.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=138) |
| STARTER | 1核 | 2GB | 40GB | 1000GB | 1Gbps | $39.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=139) |
| MINI | 2核 | 2GB | 60GB | 2000GB | 1Gbps | $79.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=140) |
| MICRO | 4核 | 4GB | 80GB | 4000GB | 1Gbps | $159.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=141) |
| MEDIUM | 4核 | 8GB | 160GB | 5000GB | 1Gbps | $259.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=142) |
| LARGE | 8核 | 16GB | 320GB | 8000GB | 1Gbps | $429.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=143) |
| GIANT | 8核 | 24GB | 640GB | 15000GB | 1Gbps | $799.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=144) |

### 🇯🇵 东京 TYO — Eyeball 系列（三网 CMI）

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 带宽 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|------|
| TINY | 1核 | 1GB | 20GB | 1000GB | 1Gbps | $25.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=221) |
| STARTER | 1核 | 2GB | 40GB | 2000GB | 2Gbps | $55.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=222) |
| MINI | 2核 | 2GB | 60GB | 3000GB | 2Gbps | $85.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=223) |
| MICRO | 4核 | 4GB | 80GB | 4000GB | 4Gbps | $119.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=224) |
| MEDIUM | 4核 | 8GB | 160GB | 6000GB | 4Gbps | $179.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=225) |
| LARGE | 8核 | 16GB | 320GB | 12000GB | 4Gbps | $369.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=226) |
| GIANT | 8核 | 24GB | 640GB | 24000GB | 4Gbps | $749.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=227) |

### 🇯🇵 东京 TYO — Tier 1 系列（国际线路）

| 套餐 | CPU | 内存 | 硬盘 | 月流量 | 价格 | 购买 |
|------|-----|------|------|--------|------|------|
| WEE | 1核 | 1GB | 20GB | 1000GB | $36.90/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=228) |
| TINY | 1核 | 1GB | 20GB | 2000GB | $6.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=131) |
| STARTER | 1核 | 2GB | 40GB | 4000GB | $12.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=132) |
| MINI | 2核 | 2GB | 60GB | 8000GB | $21.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=133) |
| MICRO | 4核 | 4GB | 80GB | 16000GB | $32.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=134) |
| MEDIUM | 4核 | 8GB | 160GB | 32000GB | $49.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=135) |
| LARGE | 8核 | 16GB | 320GB | 64000GB | $99.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=136) |
| GIANT | 8核 | 24GB | 640GB | 128000GB | $199.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=229) |

> 东京 T1 优惠码：季付/年付可用 `2025-TYO-T1-HI-GSL-NON-MONTHLY-30OFF` 享受 30% 永久折扣

---

## 需要注意的几件事

买 DMIT Malibu 之前，有几点是新手容易忽略的：

**关于账号注册：** DMIT 对新注册账号有 7 天等待期才能下单，这不是针对所有人的，但如果你是刚注册的账号，记得提前几天搞定。

**关于 SSH 登录方式：** DMIT 默认使用 SSH 密钥登录，不是密码登录。在控制面板的 Access 页面可以下载密钥包，里面有 `.ppk` 文件供 PuTTY 使用。不习惯的话可以 DD 重装系统切换为密码登录，但步骤稍多。

**关于流量超限：** Malibu 套餐每月 1000GB 流量，超出后会限速到 2Mbps——注意不是停机，是降速。对于个人使用来说这个机制相对友好，至少不会突然断掉。

**关于 IP 被墙：** DMIT Premium 系列的 IP 被墙后可以免费换，每 15 天申请一次，其他情况收费 $5 一次。相比搬瓦工这已经是一个比较实惠的政策了。

**关于退款：** 购买后 3 天内、且流量消耗不超过 30GB 可以申请全额退款（扣支付手续费）；30 天内可以申请部分退款，按剩余时间比例计算。

---

## 谁适合 DMIT Malibu？

说简单点，这款套餐最适合这几类人：

**科学上网用户**：需要一个稳定好用的节点，CN2 GIA 线路晚高峰不卡，$49.9/年的成本也非常低，是很多人的主力机或备用机。

**个人建站或博客**：1核1G 对于静态博客、WordPress 小站完全够用，国内用户访问速度比普通美西 VPS 好很多。

**流媒体解锁**：DMIT 全系配原生 IP，实测可解锁 Netflix、TikTok 等主流流媒体（官方不作保证，以实测为准），这是很多"原生 IP"卖点 VPS 的核心使用场景。

**外贸或跨境业务轻量用户**：需要一个在美国的稳定节点，用于收发邮件、访问 Google Workspace 等，这个配置完全够。

如果你的需求超过上面这些，比如要跑 MySQL、需要 2GB+ 内存来跑某些程序、或者需要不限量流量——那就直接看 LAX.Pro 常规套餐，价格高一些但配置和弹性都更好。

👉 [查看 DMIT 全部洛杉矶套餐](https://www.dmit.io/aff.php?aff=13832)

---

## 最后说一句

DMIT Malibu 这款套餐存在的意义，就是让更多人能以一个合理的价格体验到 CN2 GIA 线路的质量。它不是完美的——1核1G 的配置注定了它的适用范围有限——但在这个价位上，你找不到比它网络质量更好的同类产品。

它是限量的，有货就是缘分，没货也不用着急，等下次补货就行——DMIT 补货的频率还算规律，大促节点（黑五、双十一、圣诞元旦）通常都会出现。

如果现在有货，不用想太多。

👉 [点击查看 DMIT Malibu 是否有货](https://www.dmit.io/aff.php?aff=13832&pid=186)

---

*价格与库存以 DMIT 官网实时显示为准，套餐信息可能随时调整。*
