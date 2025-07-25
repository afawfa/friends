# 友链交换

> 因为目前友链已经很多了，暂时不接受陌生博主的友链申请。想要互换友链的朋友可以先在评论一下自己喜欢的文章，混个脸熟啥的。

**非常欢迎前来申请友链的小伙伴，在交换友链之前请仔细阅读以下内容。**

## 交换方式

### Pull Request

1. Fork 本仓库。
2. 按照格式添加你的站点信息到 `links.yml`。
3. 创建一个 Pull Request 请求合并到本仓库。
4. 等待回复。

### 电子邮件

通过 Github 的用户信息界面找到我的电子邮箱，然后通过邮箱发送申请信息。

如果您使用邮箱发送申请信息并且您的申请信息中包含了联系邮箱，申请通过后我会将您的联系邮箱**加密**后上传到本仓库。

## 原则

原则即申请友链时必须满足的条件，但并不是全部满足就一定会申请成功。

*目前友链较多，所以审核时会带有**个人喜好**的影响，如果您的友链申请没有通过，可能仅仅是因为不对口味而已，并不是您的站点不优秀。*

* 请按照指定格式申请友链。
* 您的网站上必须能容易地看到友链展示（汇总）页面。
* 您可以使用不传递搜索引擎权重的方式添加本站友链（如链接中使用 nofollow 属性或者使用 JS 跳转）。如果您使用了这类方式，那么本人保留对相应友链使用同样方式的权力。
* 必须有非免费的独立域名，`*.github.io` 或 `*.gitee.io` 可以酌情考虑。
* 站点正常运行至少一年。
* 必须是使用 HTTPS 协议的站点。
* 观感良好。比如不能有大量的广告去影响阅读。
* 至少要有十篇原创文章。
* 目前不接受资源分享网站和文章采集网站。
* 站点中若包含转载的文章，则这类三类文章数量之和不能超过站点文章总数的 25%。
* 站点不能存在下列内容：
    * 政治敏感的内容。
    * 钓鱼链接等恶意链接。
    * 病毒木马、挖矿脚本等恶意程序。
    * 暴力、恐怖，反动、迷信、恶意攻击他人等内容。
    * 在博客分享虐待他人、包养情人、遗弃家庭成员等严重违背社会道德的内容。

申请后可以先不添加本站友链，但必须在申请通过后 15 日内添加本站的友链，否则将取消本次申请，如有特殊情况可以适当延长期限。

**极少数情况下我会主动移除一个友链但不公开相关材料，只会将加密后的材料在此处归档。原因通常是材料不便公开，如涉及个人隐私、涉及重要信息、涉及恶劣行为或涉及其它不便公开的因素。如有必要可能将材料解密，甚至公开相关的加密材料。如果您被无故移除友链可以联系我，如错误地删除了友链我将恢复友链并道歉。**

## 格式

```
blog: 寂静花园
name: ADD-SP
url: https://www.addesp.com
avatar: https://www.addesp.com/avatar
email: xxx@yyyy.zz
color: "#007bbb"
desc: "寂静中交织着热情"
```

* `blog`：博客名称（可选，但是`blog`和`name`至少选一个）
* `name`：怎么称呼（可选，但是`blog`和`name`至少选一个）
* `url`：博客链接
* `avatar`：头像图片链接，最好使用 HTTPS（须为正方形或圆形），在保证清晰度的前提下，越小越利于迅速加载展示哦～
* `color`：喜欢的颜色，将用作友链文字，友链边框以及头像边框的颜色（可选）
* `email`：联系邮箱，提供您的邮箱便于联系（可选）
* `desc`：简短描述你的站点，太长会被截断（可选）

## 关于邮箱

建议您在申请友链时留下您的邮箱，这样后面联系起来也方便。

如果您担心留下邮箱会将您的邮箱暴露在网络上，您可以在我的 Github 个人主页上找到我的邮箱，通过邮箱发送申请信息。
申请通过后您的邮箱地址将会被加密，然后更新到本仓库中。

## 注意事项

* 本站会不定期检查友链指向的网站，若发现不符合要求则会视情况做出下列三种处理中的一种：
  * 删除友链、不通知站长。
  * 暂时删除友链，如果有站长的联系方式则通知站长，之后是否恢复视情况而定。典型情况是友链指向的网站被挂马。
  * 在本站友链界面进行特殊标记，如果有站长的联系方式则通知站长，之后是否移除标记视情况而定。

## 友链处理日志

见 [CHANGES](CHANGES.md)。

## Commit 格式

本格式在您创建 Pull Request 时无需遵守，只是如果您想阅读本仓库的 Commit 记录，了解一下格式可以帮助理解。

如果友链对增加，修改，标记，暂时移除，彻底移除这几个操作，Commit 的格式见下面。

Commit 格式为：emoji 博客名

> 博客名有时会经过 base64 编码。

* emoji：emoji 表情，可以是下列取值。
  * :white_check_mark:：表示新增了一个友链。
  * :arrow_up:：表示更新了一个友链的信息。
  * :triangular_flag_on_post:：表示标记或暂时移除了一个友链。
  * :heavy_minus_sign:：表示彻底移除了一个友链。
  * :art:：杂项

如因站点大事（更换域名和改名等）更新则 commit 记录中带有 :sparkles: 。


## 其它信息

这部分信息作为友链的申请者无需了解。

### 加密相关

友链中的敏感信息如邮箱可能会被加密存储，加解密脚本在 `tools` 目录下。

* 密钥导出函数：PBKDF2
* 迭代次数：2,000,000

问：主密钥不保存在这里，为什么迭代次数这么多？

答：我也不知道，随便写了一个数，反正也不会花费多久去迭代。

```shell
# 加密明文，输出 Base64 编码的密文。
./tools/encrypt plainText

# 解密经过 Base64 编码的密文，输出明文。
./tools/decrypt cipherText
```
