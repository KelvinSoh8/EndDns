### 一点说明
此仓库为EndDNS发布所用。EndDNS是用于查找最快IP，快速解析，防DNS污染用途，不是用于科学上网的，请大家不要讨论不相关的话题。[项目主页](https://www.enddns.com/)。

### 关于本软件的申明
此软件为免费软件，且当前仍处于开发阶段，不能确保稳定性。愿意使用此软件的用户都被视为测试用户，此软件开发者不对用户使用此软件造成的直接或间接损失承担任何责任，如果不同意此申明，请不要使用此软件。

### 下载链接
- [Windows版本](https://www.enddns.com/download/windows/latest)
- [Mac版本](https://www.enddns.com/download/darwin/latest)

### BUG相关
请通过[Issues](https://gitee.com/gazeboxu/enddns-pub/issues)进行Bug反馈及交流，请严格按照[问题模板填写](bug_template.txt)

### 配置分享
3rdrefconf可用于有愿意分享配置文件的同学使用，请严格按时以下格式来使用

虽然EndDNS有对使用的DNS IP限制，但静态域名解析也可能导致恶意行为，使用三方分享的配置文件时尽量只是参考，不要全部拷贝使用!!!

#### 目录结构：
- refconf（目录），官方配置文件
- 3rdrefconf（目录），三方配置文件
    + 你的gitee用户名（目录）
        - 配置包名（目录）
            + README.md，配置介绍
            + dnswhitelist.toml，这个可以不要
            + config.toml，配置文件
