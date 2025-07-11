## 介绍
Loon、Surge自用分流去广告规则，规则、插件、模块收集于网络并进行适用性调整。本人不作维护。只进行了整合并整理适合个人使用的Loon、Surge规则


## 功能
- 自动分流、测速
- 负载均衡、广告过滤

## Surge 导入规则
- 复制 **[规则链接](https://raw.githubusercontent.com/dqzboy/Loon_Surge_Rule/refs/heads/main/conf/Surge/Surge.conf)** 导入Surge

### Surge IOS
<br/>
<table>
    <tr>
      <td width="50%" align="center"><b>下载规则</b></td>
      <td width="50%" align="center"><b>模块下载</b></td>
    </tr>
    <tr>
        <td width="50%" align="center"><img src="https://cdn.jsdelivr.net/gh/dqzboy/Images/dqzboy-proxy/surge-ios01.png?raw=true"></td>
        <td width="50%" align="center"><img src="https://cdn.jsdelivr.net/gh/dqzboy/Images/dqzboy-proxy/surge-ios02.png?raw=true"></td>
    </tr>
</table>

### Surge Mac
<details>
<summary>点击展开 ...</summary>
    
<br/>
<table>
    <tr>
      <td width="50%" align="center"><b>Surge Mac下载配置</b></td>
    </tr>
    <tr>
        <td width="50%" align="center"><img src="https://cdn.jsdelivr.net/gh/dqzboy/Images/dqzboy-proxy/surge-mac01.png?raw=true"></td>
    </tr>
</table>
</details>

## Loon 导入规则
- 复制 **[规则链接](https://raw.githubusercontent.com/dqzboy/Loon_Surge_Rule/refs/heads/main/conf/Loon/loon.conf)** 导入Loon

<details>
<summary>点击展开 ...</summary>
    
<br/>
<table>
    <tr>
      <td width="50%" align="center"><b>配置管理</b></td>
      <td width="50%" align="center"><b>下载规则</b></td>
    </tr>
    <tr>
        <td width="50%" align="center"><img src="https://cdn.jsdelivr.net/gh/dqzboy/Images/dqzboy-proxy/loon-ios01.png?raw=true"></td>
        <td width="50%" align="center"><img src="https://cdn.jsdelivr.net/gh/dqzboy/Images/dqzboy-proxy/loon-ios02.png?raw=true"></td>
    </tr>
</table>
</details>

## 重写、规则转换
<details>
<summary>点击展开 ...</summary>
    
**（1）** 首先在你的软件安装`Script-Hub`
- GitHub连接：[Script-Hub](https://github.com/Script-Hub-Org/Script-Hub)

**（2）** 通过浏览器打开 `Script-Hub` 
- https://script.hub

**（3）** 规则转换

<br/>
<table>
    <tr>
      <td width="50%" align="center"><b>规则转换</b></td>
      <td width="50%" align="center"><b>导入规则</b></td>
    </tr>
    <tr>
        <td width="50%" align="center"><img src="https://github.com/user-attachments/assets/d9b1317b-13eb-4c4c-a9ae-042bc3bde551?raw=true"></td>
        <td width="50%" align="center"><img src="https://github.com/user-attachments/assets/eb595b74-1cdb-46eb-91a7-d51df7d7c41c?raw=true"></td>
    </tr>
</table>
</details>

## 节点延迟测试地址汇总

> 各个代理工具都有一个测试节点延迟的功能，在 V2rayN 中又叫`真连接延迟`，目前各个工具都提供了修改测试链接地址的功能，以下为搜集的测速地址，可按自己测速情况来选择使用。

<details>
<summary>点击展开 ...</summary>
    
- 1、Apple：对中国大陆和境外都是最友好的
```
http://www.apple.com/library/test/success.html
```

- 2、高通：对中国大陆和境外都是最友好的
```
http://www.qualcomm.cn/generate_204
```

- 3、Cloudflare：境外代理节点好用，对中国大陆不友好（代理测试会使用CDN优选，不准确）
```
http://cp.cloudflare.com/generate_204
```

- 4、Google：各大代理工具都默认使用的地址，对中国大陆和境外都比较友好
```
http://www.gstatic.com/generate_204
```

- 5、Microsoft：入口一般
```
http://www.msftconnecttest.com/connecttest.txt
```

</details>

## DNS服务器

<details>
<summary>点击展开 ...</summary>
    
#### DNS over UDP：
```
# 阿里
223.5.5.5
223.6.6.6
2400:3200::1
2400:3200:baba::1

# 火山引擎(延迟高)
180.184.1.1
180.184.2.2
```

### DNV-over-HTTP/2
```
# 阿里
https://dns.alidns.com/dns-query, 
https://223.5.5.5/dns-query
https://223.6.6.6/dns-query

# 腾讯
https://1.12.12.12/dns-query
https://120.53.53.53/dns-query
https://doh.pub/dns-query

# 海外
https://9.9.9.9/dns-query
https://doh.apad.pro/dns-query
https://1.1.1.1/dns-query
```

### DNV-over-HTTP/3
```
# 阿里
h3://dns.alidns.com/dns-query
h3://223.5.5.5/dns-query
h3://223.6.6.6/dns-query
```

### DNV-over-QUIC
```
# 阿里
quic://dns.alidns.com:853
quic://223.5.5.5:853
quic://223.6.6.6:853
```
</details>

## 图标合集

<details>
<summary>点击展开 ...</summary>
    
[Weigeshen整合图标合集](https://raw.githubusercontent.com/weigeshen/-/main/TuBiao/TuBiaoDingYue.json)

[fmz200の图标合集](https://raw.githubusercontent.com/fmz200/wool_scripts/main/icons/icons-all.json)

[QureColor图标合集](https://raw.githubusercontent.com/Koolson/Qure/master/Other/QureColor.json)

[离歌图标集](https://raw.githubusercontent.com/lige47/QuanX-icon-rule/main/ligeicon-surge.json)
</details>

## 推广

<table style="width: 100%; table-layout: fixed;">
    <tr>
      <td width="50%" align="center"><b>海外服务器</b></td>
      <td width="50%" align="center"><b>海外服务器</b></td>
    </tr>
    <tr>
        <td width="50%" align="center">
            <a href="https://dqzboy.github.io/proxyui/racknerd" target="_blank">
                <img src="https://cdn.jsdelivr.net/gh/dqzboy/Images/dqzboy-proxy/1.png?raw=true" 
                     alt="RackNerd" 
                     style="width: 100%; height: auto; max-width: 400px; object-fit: contain;">
            </a>
        </td>
        <td width="50%" align="center">
            <a href="https://dqzboy.github.io/proxyui/CloudCone" target="_blank">
                <img src="https://cdn.jsdelivr.net/gh/dqzboy/Images/dqzboy-proxy/2.png?raw=true" 
                     alt="CloudCone" 
                     style="width: 100%; height: auto; max-width: 400px; object-fit: contain;">
            </a>
        </td>
    </tr>
</table>

## 感谢
规则来自：[blackmatrix7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon)

插件来自：[广告必须死](https://raw.githubusercontent.com/fmz200/wool_scripts/main/Loon/plugin/blockAds.plugin)，[可莉的Loon资源库](https://github.com/luestr/ProxyResource)
