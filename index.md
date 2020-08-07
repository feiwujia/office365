# 2020.8.8 更新了大部分内容。


# 什么是Microsoft 365
请参见[官方介绍](https://www.microsoft.com/zh-cn/microsoft-365)。

Microsoft 365使用订阅的机制，分为多个版本，如个人版、家庭版、教育订阅(A系列)、商业/企业订阅(E系列)；其中订阅分为Microsoft 365(M365)订阅以及Office 365(O365)订阅，前者追加了更多的服务与功能(例如可能包含**Window 10 Enterprise**、**Microsoft Intune**等等)。

O365教育订阅包括A1、A1P、A3、A5等，最常见的为A1、A1P；
M365教育订阅包括A1、A3、A5等，目前常见的、能够不给微软交钱就取得的仅有A3，于2020年5月初出现；
教育订阅均为微软向合规教育机构的捐赠(O365A1等免费订阅)或正规教育机构以优惠价格取得的(A1P、A3)；
就在2020年8月6日，微软搞了一波Microsoft 365 零元购，大量Prepaid订阅以零元的价格被放在了[管理中心](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/catalog)后台，并且可直接购买，出现了一堆奇怪的教育订阅，例如O365 E3/E4/A3 for students/faculty、Microsoft 365 Apps for students/faculty等等，这些铁灵车，下文不做介绍。
商业订阅包括企业版和商业版，订阅大部分都是E开头，有的叫Office 365，有的叫Microsoft 365；具体有E1、E3、E4、E5、Microsoft 365 Business XXX，其中Office 365 E3 for Symphony 和Microsoft 365 E5 Developer (without Windows and Audio Conferencing)最常见，亦有微软向Non-Profit Organization的捐赠及优惠(E1、Microsoft 365 Business Premium)和面向开发人员的E3MSDN、E5MSDN等等。
一样的，2020年8月6日，Microsoft 365 零元购，一堆的商业版/企业版订阅也是以Prepaid订阅的形式、零元的价格被放在了[管理中心](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/catalog)后台，并且可直接购买，这些铁灵车，下文亦不做介绍。
最后，还有什么Teams 800年试用订阅，和一堆没什么用的/不常见的订阅，不做介绍。

# 不同订阅介绍
***
##一、教育订阅
### 1、Office 365 订阅
A1许可可达Unlimited，A1P大部分为5000+5000或单5000许可，其订阅/许可证处于始终免费的状态，微软并不向教育机构收取费用，但微软提供如下服务:
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

```markdown
Office 365 A1 Plus for students

Whiteboard (Plan 1)
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
Office for the web (Education)
SharePoint Plan 1 for EDU
Exchange Online (Plan 1)
The latest desktop version of Office 
Skype for Business Online (Plan 2)
```

Office 365 A1 for faculty和students区别在于多了Education Analytics和Microsoft Kaizala Pro的许可~~（并用不到）~~，Office 365 A1 Plus for faculty、Office 365 A1 Plus for students与A1(无Plus)的主要区别是**增加**了**Office最新的桌面版本**，而O365A3、O355A5不常见，各版具体的区别可以在[官网](https://www.microsoft.com/en-us/microsoft-365/academic/compare-office-365-education-plans)查看。
### 2、Microsoft 365 订阅
以Microsoft 365 A3 - Unattended License for students use benefit为例，其订阅最高可达Unlimited，其许可证如下：
```markdown
Microsoft 365 A3 - Unattended License for students use benefit

Yammer for Academic
Windows 10 Enterprise
Whiteboard (Plan 2)
To-Do (Plan 2)
Sway
Skype for Business Online (Plan 2)
SharePoint Plan 2 for EDU
School Data Sync (Plan 2)
PowerApps for Office 365
Office for the web (Education)
The latest desktop version of Office
Office 365 Cloud App Security
Minecraft Education Edition
Microsoft Teams
Microsoft Stream for O365 E3 SKU
Microsoft StaffHub
Microsoft Planner
Microsoft Kaizala Pro
Microsoft Intune
Microsoft Forms (Plan 2)
Microsoft Azure Multi-Factor Authentication
Intune for Education
Information Protection for Office 365 - Standard
Flow for Office 365
Exchange Online (Plan 2)
Education Analytics
Cloud App Security Discovery
Azure Information Protection Premium P1
Azure Active Directory Premium P1
Azure Active Directory Basic for EDU
```

相比Office 365 A1 Plus多了Windows 10 Enterprise、Microsoft Intune、Minecraft Education Edition、Azure Active Directory Premium P1以及一堆杂毛许可，是一个功能比较完整的订阅，但Microsoft 365 A5的许可比A3还要多、部分许可还要高级。对于这个订阅，价值最大的不过也是SharePoint、Exchange、Office365桌面版和Minecraft Education Edition；关于Window 10 Enterprise许可证，需要组织的全局管理员开启相关设置，才可以激活Window 10 Enterprise，并不能激活LTSB、LTSC等其他版本，并且只要将Window连接到组织的Azure Active Directory，组织即可控制相应的设备，而激活Window 10 Enterprise，必须将Window连接到组织的Azure Active Directory，因此非常不建议使用此类账户激活Window 10 Enterprise，除非自己为全局管理员。
最后关于Microsoft 365 A3 - Unattended License for students use benefit这一订阅，在2020年5月初被微软~~临时工~~错误的配置到了[管理中心](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/catalog)中，并称是给bot使用的，要求拥有Microsoft 365 A3的组织管理员**在6月30日前取消面向学生的许可证分配**，但是已经添加该订阅的，6月30日之后该订阅仍处于活动状态，并未被微软大规模禁用。

## 二、商业订阅
###1、灵车
最著名的灵车无非就是 Office 365 E3 for Symphony(E3 SY)了，据大佬说，该订阅为微软提供给其合作伙伴Symphony公司的测试订阅，单订阅许可证可达350W，其许可证如下：
```markdown
Office 365 E3

Common Data Service
Microsoft Bookings
Microsoft Kaizala Pro
Whiteboard (Plan 2)
Information Protection for Office 365 - Standard
Insights by MyAnalytics
To-Do (Plan 2)
Microsoft Forms (Plan E3)
Microsoft Stream for O365 E3 SKU
Microsoft StaffHub
Flow for Office 365
PowerApps for Office 365
Microsoft Teams
Microsoft Planner
Sway
Yammer Enterprise
Azure Rights Management
The latest desktop version of Office
Skype for Business Online (Plan 2)
Office for the web
SharePoint (Plan 2)
Exchange Online (Plan 2)
```
###2、其他
E3 MSDN，订阅名为Office 365 E3 Developer，和2019年以前申请的开发者试用E3一模一样，许可证最高为25个，其许可证如下：
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
Microsoft 365 E5 Developer (without Windows and Audio Conferencing)，许可证最高为25个，分为两种，一种是在[Microsoft 365 开发人员中心](https://developer.microsoft.com/)注册的试用订阅，微软会考核使用此订阅的开发活跃程度，来决定是否该订阅是否获得免费续订~~(玄学续订)~~，90天为一个考核周期，在[Microsoft 365 开发人员中心](https://developer.microsoft.com/)可以查看剩余日期等信息；另一种是由Visual Studio Enterprise或者类似的Visual Studio订阅中激活，在[Microsoft 365 开发人员中心](https://developer.microsoft.com/)显示剩余日期的地方无日期，提示“活动”，Office 365 [管理中心](https://admin.microsoft.com/)订阅虽显示试用，提示90天内将过期，但无需担心微软考核，在Visual Studio订阅的有效期内，该订阅会自动续订。以下为该订阅的许可证：
```
Microsoft 365 E5 Developer (without Windows and Audio Conferencing)

Microsoft Excel Advanced Analytics
Microsoft Threat Protection
Common Data Service
Microsoft Bookings
Microsoft Records Management
Microsoft ML-based classification
RETIRED - Microsoft Insider Risk Management
Microsoft Information Governance
Microsoft Data Investigations
Microsoft Customer Key
Microsoft Communications DLP
Microsoft Communications Compliance
Office 365 SafeDocs
Microsoft 365 Advanced Auditing
Yammer Enterprise
Whiteboard (Plan 3)
To-Do (Plan 3)
Sway
Skype for Business Online (Plan 2)
SharePoint (Plan 2)
PowerApps for Office 365
Power BI Pro
Microsoft 365 Phone System
Office for the web
The latest desktop version of Office
Office 365 Privileged Access Management
Office 365 Advanced Threat Protection (Plan 2)
Office 365 Cloud App Security
Office 365 Advanced eDiscovery
Microsoft Teams
Microsoft Stream for O365 E5 SKU
Microsoft StaffHub
Microsoft Planner
Microsoft MyAnalytics (Full)
Microsoft Intune
Microsoft Forms (Plan E5)
Microsoft Cloud App Security
Microsoft Azure Multi-Factor Authentication
Azure Rights Management
Information Protection for Office 365 - Standard
Information Protection for Office 365 - Premium
Flow for Office 365
Exchange Online (Plan 2)
Customer Lockbox
Azure Information Protection Premium P2
Azure Information Protection Premium P1
Azure Advanced Threat Protection
Azure Active Directory Premium P2
Azure Active Directory Premium P1
```
首先可见，E3 SY、E3 MSDN相比教育订阅少了一些东西，E5、E5 MSDN相比教育订阅多了一堆东西，但是实际用起来也没什么区别，毕竟大多数人都只用OneDrive/SharePoint、Exchange
、Forms和**Office 最新的桌面版本**，上述全部商业订阅均包含**Office 最新的桌面版本**，即可在**5 台电脑或 Mac、5 个平板电脑以及智能手机**上安装并激活office桌面版全家桶，并持续享受更新。
**OneDrive、Office最新的桌面版本以及Office套件在线及移动端**功能同上教育订阅，并无两样。
但是如果有**Power BI Pro的使用需求**、有使用**Microsoft 365 开发的需求**，相对好取得的**E5**会是一个不错的选择。
其次，灵车E3 SY，功能虽有，但是亦有各个时间产出的，**稳定性不一，翻车方式多样**，**仅建议拿来激活桌面版或者拿来乐呵乐呵**，往里面存数据就要时刻做好**数据全丢**的准备。
最后，还有一堆商业版订阅，例如E1和Business Basic系列，大部分长得和A1差不多，Business Premium，长得和M365 A3差不多，在此不做详细介绍。

# 不同订阅介绍
###一、真理
所有非正规的、非正规渠道取得(总之就是**有违微软相关规定**)的订阅，均有翻车的可能性，微软才是永远的爸爸。
###二、关于翻车
翻车形式多种多样，不排除微软还有新花样。
####常规操作
1、封订阅，即订阅被禁用。——添加奇怪的订阅常见翻车形式。
2、掉许可，未分配的即非订阅许可证掉光。——教育无订阅仅许可证全局常见。
3、禁止具有管理中心访问权限的用户登陆，之前有那么一段时间有只禁全局的情况下，现在是全禁。——老E3 SY常见翻车形式，大部分添加过Microsoft 365 A3 - Unattended License for students use benefit的翻车方式。
4、提示“用户将在2019年10月1日(太平洋时间)禁用账户“，用户在此之前可以进行数据的转移，这是2019年部分教育全局出现的状况，以后估摸着不可能出现了。——2019年部分教育全局。
####新操作
1、SharePoint 访问报错
```markdown
https://xxx.sharepoint.com/_layouts/15/Throttle.htm#1033

Something's not right
The page you requested is temporarily unavailable. We apologize for the inconvenience, please check back in a few minutes.
```
由于OneDrive for Business 是SharePoint的子站点之一，因此任何一个子账户试图访问自己的OneDrive，均会显示此错误，据大佬介绍，原因是微软将其判定为欺诈的组织的SharePoint访问阈值降为0，导致无法访问组织SharePoint。
本次可能不是微软下手最广的一次，但是微软下手最狠的一次，数据理论上无法取回，但是有人不断尝试与微软沟通，最好的结果是得到48H来取回数据，而购买正规商业许可证并不能改变SharePoint的限额状态。
出现问题的大多数为**公开分享**子账户的**教育**全局，少数E3 MSDN全局(有的刷了教育许可证)。
2、Coming Soon......

# 关于使用
### Onedrive
SharePoint 系列许可给予用户SharePoint、微软Onedrive网盘的使用权利，其中OneDrive是SharePoint的子站点之一。上述订阅基本上均可使用OneDrive/SharePoint，在默认的情况下最高有5T的容量（管理员设置，A1无管理默认1T），在使用到90%(4.5T)以上时，管理员可提交工单申请扩容至25T，SharePoint的使用请参考微软官方文档。
### Office最新的桌面版本
**Office最新的桌面版本**给予用户激活office365桌面版的权限，一般最多可以在**5 台电脑或 Mac、5 个平板电脑以及智能手机**上安装并激活office桌面版全家桶，并持续享受更新，关于office365与office2019等有什么不同，可以在[官网](https://support.office.com/en-us/article/what-s-the-difference-between-office-365-and-office-2019-ed447ebf-6060-46f9-9e90-a239bd27eb96?ui=en-US&rs=en-US&ad=US)查看。
### Office套件在线及移动端
上述订阅基本上大部分可使用Office套件在线及移动端。


# Q & A

**初次使用的账户，需要登陆[office官网](office.com)，并单击OneDrive，来初始化OneDrive。**

## 1、这个东西可以于Microsoft个人账户绑定吗？
不可以，微软账户目前分为两种，一种是个人账户，另一种是工作与学校账户，二者相互独立，不可绑定，以上提到的office365均为工作与学校账户，如想使用个人账户享受office365服务，请在微软[官网](https://www.microsoft.com/en-/microsoft-365/compare-all-microsoft-365-products)查看、购买。

## 2、会翻车吗？
教育订阅目前拿出来卖的，大多数并不正规，而用户也无法得知其正规性，因此，除非是正规学校的订阅，否则都存在翻车的可能。

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

