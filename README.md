# 2022便宜好用的VPS推荐，美国香港VPS避坑攻略

在论坛、QQ群或网站留言里，经常会有人问有哪些便宜的VPS。因为不少人买国外VPS都是用来搭梯子<a rel="noopener nofollow" href="https://github.com/search?q=VPN+%E7%BF%BB%E5%A2%99+%E6%8E%A8%E8%8D%90" target="_blank">科学上网</a>翻墙、跑跑任务、建个人网站，一般对于VPS的性能要求不算太高，能满足基本需求即可。但需要注意的是，买美国和香港VPS的时候有一些坑需要避开，不然即浪费金钱、精力，又费时间，得不偿失。

## 不推荐的VPS

```markdown
购买的VPS如果在国内不能用，再便宜也不要买！
```

目前有几家国人用户较多的VPS商家IP被封比较严重，比如BandWagon搬瓦工、Vultr、DO等，由于前几年国人购买这几款VPS搭梯子翻墙的人太多，IP大面积被封（国内网络无法访问），商家的IP资源再多也扛不住墙的打击，我今年在Vultr开了几次都没有一个可用的IP，大家就别浪费时间了。BandWagon搬瓦工目前已经不便宜了，最低年付49.9刀，而且要看运气，运气好还能搞到能用的IP，但如果购买的VPS的IP是被封的，换一次IP要8.79刀，而且不能确保是可用IP，感觉很鸡肋。

## 香港VPS特点

香港vps也比较热门，由于香港寸土寸金和港商的鸡贼，香港vps相对于美国VPS、新加坡、日本等热门地区的vps主机的价格高居不下。我讲下香港机房的主要特点：

1. **价格相对较贵**，香港vps相对于其他热门地区相同配置的VPS价格贵了不少，大多数都是$10/月起步。一方面是竞争大、地盘小；另一方面是奸商垄断，vps主机行业在香港水很深，如果新商家价格过低，会遭到其他商家的打压，比如疯狂DDos和CC攻击。前几年SL机房在香港刚刚开卖就被持续D了半年之久，最后终于撑不住了，取消大陆直连后才慢慢恢复。
2. **带宽较小**，大部分是1-5Mbps的水龙头带宽，但并不绝对，有钱就能任性。带宽小，只能适合对速度要求不高的用户，4k视频是不用想了，建站使用如果并发数过大也很难撑得住。

所以，**如果是搭梯子，香港vps我并不大推荐，并不一定地理位置离得近速度就快**。我建议科学上网的同学，要么使用<a rel="noopener" href="https://github.com/vpncn/vpncn.github.io" target="_blank">稳定的翻墙梯子</a>，要么使用美国VPS的CN2线路，价格便宜、带宽大、速度快。不推荐搬瓦工除香港之外的机房和Vultr的机房，IP目前基本不能用了；

如果是建站，网站访客不多的话可以考虑，网站流量很大的话美国vps（CN2 Gia线路）不香吗？在国内打开站点慢是慢点，但不会和香港vps差距很大，国外访问就更快了。简单来说，香港VPS适合要求在大陆访问速度快、不用备案、网站访客量不大的用户。

当然，有钱就能任性，钱管够香港vps还是很香的，钱不够的同学请参考上面我的建议。<a rel="noopener" href="https://linkv.org/bwhk/" target="_blank">搬瓦工的香港VPS</a>，除了价格贵没什么大的缺点，预算充足可以考虑，但是搬瓦工除香港之外的机房不再推荐购买，因为服务器IP大面积被封，有些新开的服务器IP就不能用，付费换IP也不能保证可用。

## 便宜的高性能VPS推荐 - <a rel="nofollow noopener" href="https://linkv.org/hostwinds/" target="_blank">HostWinds</a>

[![HostWinds](https://www.safewebcn.com/img/hostwinds-logo-min.png)](#便宜的高性能vps推荐---hostwinds)

Hostwinds算是主机界的后起之秀，成立于2010年。目前提供了虚拟主机，云主机，VPS, 独立服务器等，它的服务器数据中心也只有两个，达拉斯和西雅图，国内用户推荐选择美国西海岸的西雅图机房，速度快，延迟较低。Hostwinds的口碑一直不错，所有的主机都会采取自动的全球CND加速，服务器采用的是SSD硬盘（相对于传统的机械硬盘传送速度会快很多），免费SSL证书，免费域名，免费独立ip等等，重点是价格还比较便宜！

Hostwinds在国内名气不算大，还没有像搬瓦工、Vultr那样国人扎堆，我自己建站实测速度比搬瓦工和VULTR都好不少。月付$4.99，支持支付宝，1Gb内存，1Tb流量，自带 SNAPSHOT 快照备份，可以免费更换IP。

HostWinds的VPS包含Linux和Windows系统，分为Managed托管型和Unmanaged非托管型。VPS产品包含托管型Linux VPS和非托管型的Linux VPS，托管Windows VPS 和非托管Windows VPS。如果已经会Linux或是想更加熟悉Linux系统和掌握一些Linux的基础操作，一般我是建议选择Unmanaged Linux VPS，建网站或是干其他别的都够用了，Linux的稳定性也足够好；Windows选择的人相对少一些，而且价格偏高，如果不是对Windows有特殊需求一般不会选择。

- Managed托管型的Hostwinds官方技术人员为服务器提供全套运维服务，省事省力，但是价格稍贵一些，有点不划算。
- Unmanaged非托管型就是买个裸机VPS，随意DIY，包括系统在内的所有程序自己搭建（按流程很简单），在学会一些Linux的知识的同时还能省点钱，性价比较高。

目前Hostwinds托管型Linux的价格最低是8.24美元/月， 非托管型的Linux价格最低是4.99美元/月，两者都是1CPU,1Gb内存，30GB的SSD硬盘空间，每月1TB的数据流量。

托管型Windows的价格最低是12.79美元/月，非托管型的Windows价格最低是9.89美元/月，两者都是1CPU, 1GB RAM， 30GB的SSD硬盘空间，每月1TB的数据流量。

可以看到非托管型的Linux性价比最高了，每月费用甚至比Vultr还低，更不用说搬瓦工了，但是系统配置却比Vultr更高。机房选择有达拉斯，西雅图和阿姆斯特丹。我建议选择西雅图机房，国内访问速度还不错。目前官网正做活动，新用户优惠10%！

#### <a rel="nofollow noopener" href="https://linkv.org/hostwinds/" target="_blank">获取HostWinds优惠链接>></a>

### 如何购买Hostwinds-VPS

下面我以Unmanaged非托管型VPS为例进行说明，首先<a rel="nofollow noopener" href="https://linkv.org/hostwinds/" target="_blank">打开Hostwinds官网</a>，选择Unmanaged， 1GB – $4.99这款VPS。

[![如何购买HostWinds](https://www.safewebcn.com/img/Hostwinds-Unmanaged-vps.png)](#如何购买hostwinds-vps)

点击“Order”注册账户。如果是用PayPal付款，邮箱地址最好和PayPal账户邮箱保持一致，使用支付宝和银行卡付款使用自己的常用邮箱就行：

[![如何购买HostWinds](https://www.safewebcn.com/img/Hostwinds-email-register.png)](#如何购买hostwinds-vps)

接下来需要填写一些必要的注册信息。请尽量填写真实信息，特别是IP地址要和本机所在地相同，这是网站防止信用卡盗刷风险。比如你在广州，IP显示地址也是广州，就不能填地址在上海。Hostwinds官网在中国是可以正常访问的，所以，为避免不必要的麻烦，如果你在使用梯子或者代理服务器，在购买前请确保关闭梯子，尽量使用本地网络访问，否则订单的审核可能会出现问题：

[![购买HostWinds](https://www.safewebcn.com/img/Hostwinds-infomation.png)](#如何购买hostwinds-vps)

然后，选择并确认信息。确认是Unmanaged非托管型，付款周期（年付/季付/月付），机房（西雅图/SEATTLE），系统为Debian 9（占用内存小，适合建站，也可选CentOS或Ubuntu），确认主机为CPU:1 Core，内存1GB，存储30GB。其他信息默认不需改动：

[![购买HostWinds](https://www.safewebcn.com/img/Hostwinds-unmanaged-vps-order.png)](#如何购买hostwinds-vps)

这里有可选功能：云备份和VPS监测提醒，可以根据自己的需求选择：

[![HostWinds云备份](https://www.safewebcn.com/img/Hostwinds-cloud-backup.png)](#如何购买hostwinds-vps)

支付方式有信用卡（Visa、Master Card）、Paypal和支付宝，支付方式建议优先选择Paypal，如果没有Paypal可以选择信用卡或支付宝：

[![HostWinds支付方式](https://www.safewebcn.com/img/Hostwinds-payment-method.png)](#如何购买hostwinds-vps)

最后，勾选同意服务条款、隐私政策，并确认订单支付：

[![HostWinds隐私政策](https://www.safewebcn.com/img/Hostwinds-tos.png)](#如何购买hostwinds-vps)

完成订单付款后，等待几分钟，邮箱会收到VPS成功开通的邮件，邮件有VPS相关信息，比如VPS服务器的IP地址、root密码和SSH端口等。建议复制保存下来备用，免得以后要登录VPS时找得麻烦。

### IP更换的方法

进入VPS管理后台，点击Manage IP’s ，然后点击Fix ISP Block按钮，在弹出的窗口点击确认Confirm。

[![HostWinds换IP](https://www.safewebcn.com/img/Hostwinds-Fix-ISP-Block.png)](#ip更换的方法)

下一次，我们说说如何正确设置和优化VPS，以及WordPress建站。

本文页面：

<a rel="noopener" href="https://vpsda.github.io/" target="_blank">好用便宜的VPS推荐</a>
