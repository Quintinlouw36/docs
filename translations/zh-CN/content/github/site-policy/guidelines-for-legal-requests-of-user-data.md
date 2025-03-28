---
title: 用户数据法律要求指南
redirect_from:
  - /law-enforcement-guidelines
  - /articles/guidelines-for-legal-requests-of-user-data
versions:
  fpt: '*'
topics:
  - Policy
  - Legal
---

您是否是对可能涉及 GitHub 上托管的用户内容进行调查的执法人员？ 或许您是一个具有隐私意识的人，想知道我们与执法部门分享什么信息，以及在什么情况下分享信息。 无论您是哪种身份，都应该参阅本文内容。

在这些指南中，我们略微提供了一些 GitHub 的背景信息，简单介绍了 GitHub 及其拥有的数据类型，还有我们披露私人用户信息的条件。 但在我们了解详细信息之前，您可能需要先了解以下几个重要细节：

- 我们将[**通知受影响的用户**](#we-will-notify-any-affected-account-owners)有关其帐户信息的任何请求，除非法律或法院命令禁止这样做。
- 如果没有[有效的法院命令或搜查令](#with-a-court-order-or-a-search-warrant)，我们不会披露**位置跟踪数据**，如 IP 地址日志。
- 如果没有有效的[搜查令](#only-with-a-search-warrant) ，我们不会披露任何**私有用户内容**，包括私有仓库的内容。

## 关于这些指南

我们的用户信任他们的软件项目和代码——往往是他们最宝贵的业务或个人资产。 维持这种信任对我们来说至关重要，因此要确保用户数据的安全、可靠和私密。

虽然我们绝大多数用户利用 GitHub 的服务创办新企业、开发新技术和改善人类生活，但我们认识到，我们有数以百万计的用户遍布全球，其中难免会有一些心怀不轨之人。 在这些情况下，我们希望帮助执法部门履行其保护公众的法定职责。

通过为执法人员提供指南，我们希望在用户隐私与正义之间实现某种平衡。 我们希望这些指南将帮助明确双方的期望，并提高 GitHub 内部流程的透明度。 我们的用户应该知道，我们重视他们的私人信息，并且会尽力保护这些信息。 这至少意味着只有在符合适当法律要求的情况下才向第三方披露数据。 出于同样原因， 我们还希望培训专业执法人员了解 GitHub 系统，以便他们能够更有效地定制其数据请求，并且只针对进行调查所需的信息。

## GitHub 术语

在要求我们披露数据之前，了解我们系统的实施方式很有用。 GitHub 使用 [Git 版本控制系统](https://git-scm.com/video/what-is-version-control)托管数百万数据仓库。 GitHub 上的仓库——可能是公共或私有——常用于软件开发项目，但也常用于研究各种内容。

- [**用户**](/articles/github-glossary#user) — 用户在我们的系统中表示为个人 GitHub 帐户。 每个用户都有自己的个人资料，可以拥有多个仓库。 用户可以创建或受邀加入组织，也可以在其他用户的仓库上进行协作。

- [**协作者**](/articles/github-glossary#collaborator) — 协作者是受到仓库所有者邀请参与其项目的用户，可以读取和写入参与的仓库。

- [**组织**](/articles/github-glossary#organization) — 组织是由两个或以上用户组成的组，通常对应实际的组织，如企业或项目。 它们由用户管理，可以包含仓库和用户小组。

- [**仓库**](/articles/github-glossary#repository) — 仓库是最基本的 GitHub 元素之一。 它们很容易被想象为项目的文件夹。 仓库包含所有项目文件（包括文档），并存储每个文件的修订历史记录。 仓库可以有多个协作者，并由管理员酌情决定是否可以公开查看。

- [**页面**](/articles/what-is-github-pages) — GitHub 页面是由 GitHub 免费托管的公共网页，用户可以轻松地通过存储在其仓库中的代码发布。 如果用户或组织有一个 GitHub 页面，该页面通常可以在 `https://username.github.io` 这样的网址上找到，或其网页可能已映射到其自定义域名。

- [**Gist**](/articles/creating-gists) — Gists 是源代码或其他文本的片段，用户可用来存储想法或与朋友共享。 像普通的 GitHub 仓库一样，Gist 也是通过 Git 创建的，所以它们会自动设置版本、可复刻、可下载。 Gist 可以是公共的，也可以是秘密的（只能通过已知 URL 访问）。 公共 Gist 无法转换成秘密 Gist。

## GitHub.com 上的用户数据

以下是我们维护的 GitHub 上用户和项目数据类型的非详尽清单。

- <a name="public-account-data"></a>
**公共帐户数据** — GitHub 上有各种关于用户及其仓库的公开信息。 用户配置文件可在 `https://github.com/username` 这样的网址上找到。 用户配置文件显示用户何时在 GitHub.com上创建帐户及其在 GitHub.com 上的公共活动和社交互动的信息。 公共用户配置文件还可以包括用户可能已经选择公开分享的其他信息。 所有用户公共配置文件显示：
  - 用户名
  - 用户已加星标的仓库
  - 用户关注的其他 GitHub 用户
  - 关注他们的用户

  （可选）用户也可以选择公开分享以下信息：
  - 他们的真实姓名
  - 头像
  - 关联公司
  - 他们的位置
  - 公共电子邮件地址
  - 他们的个人网页
  - 用户是其成员的组织（*取决于组织或用户偏好*）

- <a name="private-account-data"></a>
**私人帐户数据** — GitHub 也收集和维护我们[隐私政策](/articles/github-privacy-statement)中概述的用户相关特定私密信息。 可能包括：
  - 私人电子邮件地址
  - 付款详细信息
  - 安全访问日志
  - 与私有仓库交互的数据

  要了解 GitHub 收集的私人帐户信息类型， 可以访问您的 {% data reusables.user-settings.personal_dashboard %} 并浏览左侧菜单栏中的区域。

- <a name="organization-account-data"></a>
**组织帐户数据** — 有关组织及其管理用户和仓库的信息发布于 GitHub。 组织配置文件可在 `https://github.com/organization` 这样的网址上找到。 公共组织配置文件还可以包括所有者可能已经选择公开分享的其他信息。 所有组织公共配置文件显示：
  - 组织名称
  - 所有者已加星标的仓库
  - 作为组织所有者的所有 GitHub 用户

  （可选）管理用户也可以选择公开分享以下信息：
  - 头像
  - 关联公司
  - 他们的位置
  - 直接成员和团队
  - 协作者

- <a name="public-repository-data"></a>
**公共仓库数据** — GitHub 上具有数以百万计的开源软件项目。 您可以浏览几乎任何公共仓库（例如 [Atom 项目](https://github.com/atom/atom)，以了解 GitHub 收集和维护的仓库相关信息。 可能包括：

  - 代码本身
  - 代码的旧版本
  - 项目的稳定版本
  - 协作者、贡献者和仓库成员的信息
  - Git 操作日志，如提交、分支、推送、拄取、复刻和克隆。
  - 与 Git 操作相关的对话，例如对拉取请求或提交的评论
  - 项目文档，例如议题和维基页面
  - 显示对项目的贡献和贡献者网络的统计数据和图表

- <a name="private-repository-data"></a>
**私有仓库数据** — GitHub 对私有仓库收集和维护的数据类型与公共仓库相同，不同的是，只有特别邀请的用户才可访问私有仓库数据。

- <a name="other-data"></a>
**其他数据** — 此外，GitHub 还收集分析数据，如页面访问和我们用户偶尔自愿提供的信息（例如与我们支持团队的通信、调查信息和/或网站注册）。

## 我们将通知任何受影响的帐户所有者

我们的政策是通知用户有关其帐户或仓库的任何待处理请求，除非法律或法院命令禁止我们这样做。 在披露用户信息之前，我们将作出合理的努力通知任何受影响的帐户所有者，包括向他们经验证的电子邮件地址发送邮件，向他们提供传票、法院命令或逮捕令的副本等，以便他们有机会根据自己的意愿对法律程序提出质疑。 在（极少的）紧急情况下，如果我们确定延迟通知对于防止死亡或严重伤害或持续的调查是必要的，我们可能延迟通知。

## 非公开信息的披露

根据我们的政策，仅当用户同意或在收到有效传票、民事调查要求、法院命令、搜查令或其他类似有效法律程序时，才会披露与民或事刑事调查有关的非公开用户信息。 在某些紧急情况（见下文）下，我们也可能分享有限的信息，但只能与情况的性质相对应，超出此范围则需要法律程序。 GitHub 保留对任何非公开信息请求提出异议的权利。 如果 GitHub 同意应合法请求提供非公开信息，我们将对请求的信息进行合理的搜寻。 以下是我们会同意提供的信息类型，具体取决于我们所服务的法律程序的类型：

- <a name="with-user-consent"></a>
**经用户同意** — GitHub 将应请求直接向用户（若为组织帐户，则为组织所有者）或指定的第三方（一旦 GitHub 确信用户已核实其身份并得到用户同意）提供私人帐户信息。

- <a name="with-a-subpoena"></a>
**有传票** — 如果收到与官方刑事或民事调查相关的有效传票、民事调查要求或类似法律程序，我们可以提供某些非公开帐户信息，其中可能包括：

  - 与帐户关联的名称
  - 与帐户关联的电子邮件地址
  - 帐单信息
  - 注册日期和终止日期
  - 帐户注册时的 IP 地址、日期和时间
  - 用于在指定时间或与调查有关的事件中访问帐户的 IP 地址

若为组织帐户，我们可以提供帐户所有者的姓名和电子邮件地址，以及创建组织帐户时的日期和 IP 地址。 我们不会产生关于组织帐户的其他成员或贡献者（如果有）的任何信息，或者关于识别的帐户所有者的任何其他信息，除非收到这些特定用户的后续请求。

请注意，可用的信息因个案而异。 用户可选择提供一些信息。 在另一些情况下，我们可能没有收集或保留信息。

- <a name="with-a-court-order-or-a-search-warrant"></a>
**有法院命令*或*搜查令** — 我们不会披露帐户访问日志，除非收到以下指令的要求： (i) 根据 18 U.S.C. 第 2703(d) 条签发的法院命令，有具体而明确的事实表明，有合理的理由相信所要求的信息与正在进行的刑事调查有关； 或 (ii) 根据《联邦刑事诉讼规定》(Federal Rules of Criminal Procedure) 或同等国家搜查程序签发的搜查令，上面显示可能的原因。 第 2703(d) 条签发的法院命令，有具体而明确的事实表明，有合理的理由相信所要求的信息与正在进行的刑事调查有关； 或 (ii) 根据《联邦刑事诉讼规定》(Federal Rules of Criminal Procedure) 或同等国家搜查程序签发的搜查令，上面显示可能的原因。 除了上述非公开用户帐户信息之外，我们根据法院命令或搜查令提供的帐户访问日志信息可能包括：

  - 显示用户在一段时间内移动的任何日志
  - 帐户或私有版本库设置(例如，哪些用户拥有特定权限等）
  - 用户或 IP 特定分析数据，如浏览历史记录
  - 帐户创建以外或指定时间和日期的安全访问日志

- <a name="only-with-a-search-warrant"></a>
**仅限于搜查令** — 我们不会披露任何用户帐户的私人内容，除非根据《联邦刑事诉讼规定》或同等国家搜查令规定程序签发的搜查令要求披露，搜查令上显示了可能的原因。 除了上述非公开用户帐户信息和帐户访问日志，我们还将根据搜查令提供私人用户帐户内容，可能包括：

  - 秘密 Gist 的内容
  - 私有仓库中的源代码或其他内容
  - 私有仓库的贡献和协作记录
  - 私有仓库中的通信或文档（例如议题或维基）
  - 任何用于身份验证或加密的安全密钥

- <a name="in-exigent-circumstances"></a>
**在紧急情况下** — 如果我们在某些紧急情况下收到要求提供信息的请求（如果我们认为有必要披露信息以防止涉及人员死亡或严重人身伤害危险的紧急情况），我们可能会披露我们认为对执法部门处理紧急情况必要的有限信息。 对于超出此范围的任何信息，如上所述，我们需要传票、搜查令或法院命令才会披露。 例如，没有搜查令时，我们不会披露私有仓库的内容。 在披露信息之前，我们会确认请求来自执法机构，当局发出了正式通知，概述了紧急情况以及所要求的信息将如何有助于处理紧急情况。

## 费用补偿

根据州和联邦法律，GitHub 可以要求补偿与遵守有效法律要求（如传票、法院命令或搜查令）相关的费用。 我们只收取部分费用，这些补偿只包括我们为遵守法律命令而实际发生的一部分费用。

虽然我们在紧急情况下不收费，但除非法律另有要求，否则我们将根据以下安排要求补偿为满足所有其他法律要求产生的费用：

- 最多 25 个标识符的初始搜索：免费
- 最多 5 个帐户的订阅者信息/数据制作：免费
- 为 5 个以上帐户制作订阅者信息/数据：每个帐户 20 美元
- 二次搜索：每次搜索 10 美元

## 数据保存

在美国执法部门发出与官方刑事调查相关的正式要求后， 以及签发法院命令或其他程序之前，我们将采取步骤保存长达 90 天的帐户记录。

## 提交请求

请将请求发送到：

```
GitHub, Inc.
c/o Corporation Service Company
2710 Gateway Oaks Drive, Suite 150N
Sacramento, CA 95833-3505
```

抄送件可通过电子邮件发送给 legal@support.github.com。

请求请尽可能具体，包含以下信息：

- 关于发出信息请求的机构的完整信息
- 负责代理的名称和证章/ID
- 正式电子邮件地址和联系电话号码
- 相关的用户、组织、仓库名称
- 相关的任何页面、gist 或文件的 URL
- 您需要的记录类型描述

请留出至少两周时间给我们审查您的请求。

## 外国执法部门的请求

作为一家设在加利福尼亚的美国公司，GitHub 不必根据外国当局签发的法律程序向外国政府提供数据。 希望向 GitHub 索取信息的外国执法官员应与美国司法部刑事司国际事务办公室联系。 GitHub 将迅速答复美国法院通过司法互助条约（“MLAT）或委托调查书发出的请求。 法院通过司法互助条约（“MLAT）或委托调查书发出的请求。

## 问题

您是否有其他问题、评论或建议？ 请联系 {% data variables.contact.contact_support %}。
