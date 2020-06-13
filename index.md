#最近发生的事情太多，以下已经 OUT OF DATE 了！


# 什么是Office365
参见[官方介绍](https://www.office.com/)

Office365使用订阅的机制，分为多个版本，如个人版、家庭版、教育订阅(A系列)、商业订阅(E系列)。
其中教育订阅包括A1、A1P、A3、A5等订阅，A1以及A1P目前比较容易获得，是微软给合规教育机构的优惠；E1、E3等是商业订阅，其中包括微软给NPO的优惠E1 NPO和给开发人员的福利E3 MSDN等等。

# 不同类型介绍
***
## 教育订阅
教育订阅以A1为例，其订阅处于始终免费的状态，微软并不向教育机构收取费用，但是微软提供如下服务:

```markdown
Office 365 A1 for students

 Whiteboard (Plan 1)
 Office Mobile Apps for Office 365
 To-Do (Plan 2)
 Azure Active Directory Basic for EDU
 School Data Sync (Plan 1)
 Microsoft Stream for O365 E3 SKU
 Microsoft Teams
 Microsoft StaffHub
 Flow for Office 365
 PowerApps for Office 365
 Azure Rights Management
 Microsoft Forms (Plan 2)
 Microsoft Planner
 Sway
 Yammer for Academic
 Office for the web (Education)
 Skype for Business Online (Plan 2)
 SharePoint Plan 1 for EDU
 Exchange Online (Plan 1)
```
Office 365 A1 for faculty和students区别在于多了Education Analytics和Microsoft Kaizala Pro的许可~~（并用不到）~~，A1P的主要区别是**增加**了**Office最新的桌面版本**，而A3、A5不常见，各版具体的区别可以在[官网](https://www.microsoft.com/en-us/microsoft-365/academic/compare-office-365-education-plans)查看。
### Onedrive
SharePoint 系列许可给予用户SharePoint、微软Onedrive网盘的使用权，其中OneDrive是SharePoint的子站点之一。A1、A1P、E1、E3、E5等订阅在默认的情况下最高有5T的容量（管理员设置，A1无管理默认1T），在使用到90%(4.5T)以上时，管理员可提交工单申请扩容至25T，SharePoint的使用请参考微软官方文档。
### Office365专业增强版订阅（PLUS）
**Office最新的桌面版本**给予用户激活office365桌面版的权限，一般最多可以在**5 台电脑或 Mac、5 个平板电脑以及智能手机**上安装并激活office桌面版全家桶，并持续享受更新，关于office365与office2019等有什么不同，可以在[官网](https://support.office.com/en-us/article/what-s-the-difference-between-office-365-and-office-2019-ed447ebf-6060-46f9-9e90-a239bd27eb96?ui=en-US&rs=en-US&ad=US)查看。
### Office套件在线及移动端
A1、A1P等订阅均可使用Office套件在线及移动端。
***
## 商业订阅
这里主要讲E3 MSDN，以其为例，该订阅为微软提供给开发这的福利，一个订阅许可证最多仅有25个，目前已经无法注册。其订阅为每年/每月**自动续订**，续订价格为**0**$。微软为该订阅用户提供以下服务:
```markdown
Office 365 E3 Developer

 Whiteboard (Plan 2)
 Information Protection for Office 365 - Standard
 To-Do (Plan 3)
 Microsoft Forms (Plan E5)
 Microsoft Stream for O365 E5 SKU
 Flow for Office 365
 PowerApps for Office 365
 Microsoft Teams
 Microsoft Planner
 Sway
 Office 最新的桌面版本
 Skype for Business Online (Plan 2)
 Exchange Online (Plan 2)
 Office for the web (Developer)
 SharePoint Online for Developer
```
可见相比教育订阅少了一些东西，但是实际用起来也没什么区别，毕竟大多数人都只用OneDrive/SharePoint、Exchange
、Forms和**Office 最新的桌面版本**，E3 MSDN订阅中包含**Office 最新的桌面版本**，即可在**5 台电脑或 Mac、5 个平板电脑以及智能手机**上安装并激活office桌面版全家桶，并持续享受更新。
**OneDrive、Office最新的桌面版本以及Office套件在线及移动端**功能同上教育订阅，并无两样。
***
# Q & A

**初次使用的账户，需要登陆[office官网](office.com)来启用OneDrive。**

## 1、这个东西可以于Microsoft个人账户绑定吗？
不可以，微软账户目前分为两种，一种是个人账户，另一种是工作与学校账户，二者相互独立，不可绑定，以上提到的office365均为工作与学校账户，如想使用个人账户享受office365服务，请在微软[官网](https://www.microsoft.com/en-/microsoft-365/compare-all-microsoft-365-products)查看、购买。

## 2、会翻车吗？
教育订阅目前拿出来卖的，大多数并不正规，而用户也无法得知其正规性，因此，除非是正规学校的订阅，否则都存在翻车的可能。
先说A1P，微软于2019年6月1日大规模禁用了一批不正规的A1P订阅，并且提示用户将在2019年10月1日(太平洋时间)禁用账户，用户在此之前可以进行数据的转移，由此可推测，微软清查不正规教育订阅的时候，可能会给用户提供**四个月**左右的时间来转移数据，但并不保证。但是佛心微软清查力度并不大，大规模的禁用订阅似乎仅此一次，并且似乎只针对全局管理员很早以前被微软禁止登陆的**A1P**订阅(教育订阅的异常可能触发微软风控，轻则影响订阅的购买，重则禁用全局管理员)。此外，玩弄订阅导致订阅被封禁的情况也时有发生。

再说A1订阅，关于A1订阅被禁用，目前了解到有玩弄订阅导致订阅被禁用的情况，并没有听说微软有过大规模封禁A1订阅。

玩订阅玩死的教育版订阅，亦有**四个月**时间来转移数据。

最后说E3 MSDN，同样，该订阅免费续订，目前也不存在过期，除了玩订阅玩死的，罕见订阅被莫名其妙禁用的的情况很少见，但有人声称自己的莫名其妙被禁用了，并称和OneDrive、SharePoint分享滥用有关，对此本人已对自己的订阅作出一定限制，将翻车风险降到最低。关于商业订阅，一旦被禁用，数据即不可取回，除非管理员提交工单要求取回数据或者恢复订阅才有可能可以取回数据，但本人未亲自尝试，因为本人手上的E3 MSDN订阅没翻过。

## 3、office最新的桌面版本包括什么，怎么激活？
包括Word、PowerPoint、Excel、OneNote、Access、Outlook、Skype for Business，激活方式有很多，可以自行百度，推荐在[office官网](office.com)登陆账户，并选择安装office来进行安装，安装完成自动激活。

## 4、可以绑定手机、邮箱找回密码吗？
订阅中的管理员开启后，即可绑定，并自助重置密码。

## 5、我改不了密码怎么办？
因为丢失找回密码方式或未绑定，可以联系管理员进行密码重置。

## 6、听说管理员能看用户的文件，是不是真的？
是的，是真的，订阅中拥有SharePoint管理员身份的用户，可以查看用户的OneDrive、SharePoint site中的文档。加之轻易能够购买到的均可能翻车，因此请勿存放重要文件。

## 7、怎么升级25T？
在OneDrive储存使用到4.5T(90%)以上时，联系管理员升级即可。

## 8、我想了解更多关于office365订阅的知识！
建议通读微软提供的[官方文档](https://docs.microsoft.com/en-us/office365/servicedescriptions)。

## 9、你给的链接全是英文，我看不懂！
之所以给英文链接，是因为微软部分页面并未翻译或翻译不完全，强行中文出来的页面均为微软机翻的，有很多理解不了、有缺陷甚至于原意相反的地方。如果想看中文，可以把链接中的en-us改成zh-cn/zh-tw/zh-hk，出现提示**“本主题的部分内容可能是由机器翻译。”**建议阅读英文原文。
例：https://docs.microsoft.com/**en-us**/office365/servicedescriptions
    https://docs.microsoft.com/**zh-cn**/office365/servicedescriptions
    
## 10、我想买一个账户，但是要提供些什么？
购买得到的账号为以下类型aaa@bbb.ccc，**aaa是需要用户提供的前缀**，重置密码所用到的邮箱、手机号，在管理员开启自主重置密前提下，登陆office.com的时候自助设置。

***
最后，这篇文章为本人从各方面了解到的内容，包括但不限于https://docs.microsoft.com ，来自https://docs.microsoft.com 之外的内容，不能代表微软官方的政策，由于本人水平十分有限，如内容有误，欢迎大佬指出！

