---
lang: zh-cn
title: 开源的法律保护
description: 对于开源你应该了解的所有法律知识。
class: legal
order: 10
image: /assets/images/cards/legal.png
related:
  - contribute
  - leadership
---

## 理解开源的法律含义

向世界分享你们具有创造性的工作，是一个多么令人激动和有价值的经历。这也意味着你们
必须担心一堆你们不清楚的法律问题。幸运的是，你们不必从头开始。我们已经涵盖了你们
的法律需求。（在你们行动前，请确定阅读了我们的[免责声明](/notices/)。）

## 为什么人们这么关心开源的法律方面问题？

很高兴你们提问了！当你们做创造性工作（例如写作，图形或代码）时，该作品默认为专有
版权（copyright）。也就是说，法律承认你们是你们作品的作者，他人在没有经得你们同
意的情况下不能使用你们的工作。

一般来说，这意味着没有人可以在没有你们授权的情况下使用，复制，分发或者修改你们的
工作。

然而，开源有着不一样的情况。因为作者希望他人使用，修改以及分享他们的工作。但因为
法律默认依然是专有版权（copyright），所以你们需要一个明确说明这些权限的协议。

如果你们不应用开源许可协议，那么对你们项目做出贡献的人也都将成为其工作的专属版权
（copyright）所有者。这意味着没有人（也包括你们）可以使用，复制，分发后者修改他
们的贡献，

最后，你们的项目可能和你们不知道的许可证要求存在依赖关系。你们的项目社区，或者�
们的雇主政策也可能要求你们使用特定的开源许可协议。我们将在下面介绍这些情况。

## Github 上的公开项目都是开源的吗？

当你们在 GitHub
上[创建一个新项目](https://help.github.com/articles/creating-a-new-repository/)
时，你们可以选择将仓库设置成**private**或者**public**。

![Create repository](/assets/images/legal/repo-create-name.png)

**公开你们的 GitHub 项目与许可你们的项目是不同的。**公开项目是
由[GitHub 的服务条款](https://help.github.com/articles/github-terms-of-service/#f-copyright-and-content-ownership)保
护，它允许他人浏览以及 fork 你们的项目，但是没有你的授权大家是不能使用你的工作成
果的。

如果你们想让他人使用，复制，修改你们的项目，或者参与贡献你们的项目，那么你们的项
目就需要包含一个开源许可协议。例如，即使你们的项目是公开的，但没有你们的授权，一
些人是不能合法在他们的代码中使用你们 GitHub 项目中的任何部分。

## 如何保护我们的项目

你们很幸运，开源许可协议已经是标准化而且易于使用的。你们可以直接复制粘贴一个已经
存在的许可协议到你们的项目里。

[MIT](https://choosealicense.com/licenses/mit/)，[Apache 2.0](https://choosealicense.com/licenses/apache-2.0/)和[GPLv3](https://choosealicense.com/licenses/gpl-3.0/)都
是非常流行的开源许可协议，但是也有其它选择。你们可以
在[choosealicense.com](https://choosealicense.com/)上找到这些许可协议的全部文本
，同时说明了如何使用他们。

当你们在 GitHub 上创建了一个新项目，你们会
被[要求添加一个许可协议](https://help.github.com/articles/open-source-licensing/)。

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/benbalter?s=180" class="pquote-avatar" alt="avatar">
  一个标准化的许可协议可以作为没有法律培训的人员的代理，以准确地知道他们可以和不能用软件做什么。除非绝对要求，否则应避免使用定制，修改或非标准术语，这将成为他人使用代码的障碍。
  <p markdown="1" class="pquote-credit">
— @benbalter, ["Everything a government attorney needs to know about open source software&nbsp;licensing"](https://ben.balter.com/2014/10/08/open-source-licensing-for-government-attorneys/)
  </p>
</aside>

## 我的项目适合什么样的开源许可?

如果你们是从头开始的，那么使
用[MIT License](https://choosealicense.com/licenses/mit/)，不容易出错。它很短，
很容易理解，并允许任何人做任何事情，只要他们保留许可证的副本，包括你们的版权声明
。如果你们需要，您们能够根据不同的许可协议发布项目。

否则，为项目选择合适的开源许可协议，取决于你们的目标。

你们的项目非常可能有（或将有）**依赖**。例如，如果你们开源了一个 Node.js 的项目
，你们将可能使用来自 npm（Node Package Manager）的库。你们依赖的这些库都有它们自
己的开源许可协议。如果他们的许可协议"允许"（对使用，修改和分享给予公共权限，而对
有关项目的许可协议没有要求），这样你们就可以使用任何你们想要的许可协议。共同允许
许可协议包括 MIT，Apache 2.0，ISC 和 BSD。

另一方面，如果你们的依赖中有一个的许可协议是"强硬的 copyleft"（也给予公众相同的
权限，但条件是有关项目得使用同样的许可协议），那么你们的项目将必须使用与之相同的
许可协议。copyleft 许可协议包括 GPLv2，GPLv3 和 AGPLv3。

你们也会想要考虑你们希望的社区使用以及为你们的项目做贡献：

- **你们是否想让你们的项目成为其它项目的依赖？**在你们的相关社区最好尽可能使用最
  流行的许可协议。例如
  ，[MIT](https://choosealicense.com/licenses/mit/)是[npm libraries](https://libraries.io/search?platforms=NPM)使
  用的最流行的许可协议。
- **你们的项目是否想吸引大企业？**大型企业可能需要所有贡献者的明确专利许可。在这
  种情况下，[Apache 2.0](https://choosealicense.com/licenses/apache-2.0/)适合�
  们。
- **你们的项目是否想吸引不愿自己的贡献用于其它同类型软件的贡献者
  ？**[GPLv3](https://choosealicense.com/licenses/gpl-3.0/)和[AGPLv3](https://choosealicense.com/licenses/agpl-3.0/)适
  合你们。

你们的公司可能为自己的项目准备了特定的许可协议。例如，它可能需要宽松的许可证，以
便公司可以在公司的闭源产品中使用你们的项目。或者你们的公司要求严格的 copyleft 许
可协议和一份附加的贡献者协议，以便除了你们公司以外，没有人能在封闭源代码的软件中
使用你们的项目。或者你们的公司可能有与标准，社会责任或透明度相关的某些需求，其中
任何一个都可能需要特定的许可策略。与�
们[公司的法律部门](#公司的法律团队需要知道什么)谈谈。

当你们在 GitHub 上创建了一个新项目，它给你们提供了选择许可协议的选项。包括上面提
到的可以使你们的 GitHub 项目开源的许可协议。如果你们想要了解其他选择，可以通过查
阅[choosealicense.com](https://choosealicense.com)找到适合你们项目（即使
它[不是软件](https://choosealicense.com/non-software/)）的许可协议。

## 如果我想修改开源许可该怎么办?

大多数项目绝不需要更换许可协议。但是情况偶尔有变。

例如，随着你们项目的壮大，它添加了新的依赖或用户，或者你们的公司改变了策略，或者
其他的要求要更换不同的许可协议。如果你们在开始项目的时候没有添加许可协议，那么再
添加一个许可协议和更换许可协议是一样的效果。当你们要添加或者更换项目的许可协议时
，需要考虑以下三件事：

**这件事很复杂。**确定许可协议的兼容性和合规性，以及谁拥有版权，这会非常快速地变
得复杂和混乱。为新的发布和贡献选择一个新的且合适的许可协议与重新许可已存在的贡献
是不同的。一旦你们有任何想改变许可协议的想法，请首先让法律团队知道。即使你已经或
可以获得项目版权所有者的许可证更改许可，请考虑更改对项目的其他用户和贡献者的影响
。将更换许可协议视为"管理事件"，只有通过与项目的利益相关者进行明确的沟通和咨询，
才更有可能顺利进行。请谨记，从一开始就为你们的选择和使用合适的许可协议。

**你们的项目已经有了许可协议。**如果项目的现有许可证与您要更改的许可证兼容，则可
以开始使用新许可证。这是因为如果 A 许可协议与 B 许可协议兼容，你们将遵守 A 的条
款，同时遵守 B 的条款（但不一定反之亦然）。因此，如果你们目前正在使用许可型的许
可协议（例如 MIT），则可以更改为具有更多条件的许可协议，只要你们保留 MIT 许可协
议的副本和任何相关的版权声明（即继续遵守 MIT 许可协议的最低条件）。如果你们现在
的许可协议不是许可型的（例如，copyleft 或者你们还没有许可协议）以及你们不是版权
的唯一所有者，那么你们不能将许可协议改为 MIT。基本上，只要是使用的许可型的许可协
议，版权所有者能事先更换许可协议。

**你们的项目已经有版权所有者。**如果你们是你们项目的唯一贡献者，然后你们或者你们
的公司是项目版权的唯一所有者。你们可以添加或更换任何你们或者你们公司心仪的许可协
议。不然你们需要取得其他版权所有者的同意。他们是谁？他们是已经参与你们项目提交的
人。但有些情况是项目版权掌握在这些人的雇主手中。在某些情况下，人们只是做了*微小
的*贡献，但没有硬性规定，在一些行代码下的贡献不受版权保护。对与这样的情况该怎么
办？对于一个相对较小以及年轻的项目来说，取得所有贡献者对更换许可协议的同意是可行
的。但对于大项目和老项目来说，你们必须寻求很多贡献者以及他们继承者的共识
。Mozilla 花费了多年(2001-2006)重新授权 Firefox，Thunderbird 和相关软件。

或者，你们可以让贡献者事先同意（通过额外的贡献者协议 - 见下文）在某些条件下更改
某些许可协议，这些更改将超过现有的开源许可协议。这会改变许可协议改的复杂性。如果
在执行许可协议更改时，你们仍然想要和项目利益相关者进行沟通，你们需要从你们律师那
得到更多帮助。

## 我们的项目需要额外的贡献者协议吗？

可能不要。对于大多数的开源项目，一个开源许可协议可作用与所有贡献者和用户。

贡献者协议会给维护者带来额外的管理工作。这些协议增加了多少工作得取决去项目和实施
。简单的协议可能要求贡献者确认和点击，在项目的开源许可协议下他们有权利贡献。更复
杂的协议可能需要法律的审查和贡献者的雇主的签字。

此外，贡献者协议有时被认为对项目社区不友好。他们也增加了人们参与社区的障碍。

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/bcantrill?s=180" class="pquote-avatar" alt="avatar">
    我们已经删除了Node.js的CLA。这样做降低了Node.js贡献者的参与门槛，从而吸引更多的贡献者。
  <p markdown="1" class="pquote-credit">
— @bcantrill, ["Broadening Node.js Contributions"](https://www.joyent.com/blog/broadening-node-js-contributions)
  </p>
</aside>

一些情况下你们可能想要为你们的项目考虑一个额外的贡献协议：

- 你们的律师想要所有的贡献者明确接受贡献者条款，或者因为他们觉得只有开源许可协议
  还远远不够。如果这是唯一的问题，那么有肯定项目开源许可协议的贡献者协议就足够了
  。[jQuery 个人贡献者许可协议](https://contribute.jquery.org/CLA/)就是一个很好
  的轻量级的个人贡献者协议。对于一些项目来说
  ，[Developer Certificate of Origin](https://github.com/probot/dco)是一个很好的
  先择。
- 你们的项目使用的开放源许可协议不包括明确的专利授权（如 MIT），你们需要所有贡献
  者的专利授权，这些可能适合用于你们公司的专利组合或者项目的其他贡献者和用户
  。[Apache 个人贡献者许可协议](https://www.apache.org/licenses/icla.txt)是一种
  常用的附加贡献者协议，其具有与 Apache 许可 2.0 中的专利许可相同的专利许可。
- 如果你们的项目使用的是 copyleft 许可协议，但你们也需要分发项目的专有版本。那�
  们需要每个贡献者分配版权给你们或者授予你们许可权
  。[MongoDB 贡献者协议](https://www.mongodb.com/legal/contributor-agreement)就
  是这中类型的。
- 你们认为你们的项目在其有效期内需要更换许可协议，以及事先得到贡献者的同意。

如果你的项目确实需要使用额外的贡献者协议，请考虑使
用[CLA 助手](https://github.com/cla-assistant/cla-assistant)等集成来最大限度地减
少贡献者分心。

## 公司的法律团队需要知道什么？

作为一名公司的雇员，如果你们在发布一个开源项目，你们首先需要让法律团队知道。即使
是个人项目，请考虑让他们知道。你们可能和公司有一个"员工知识产权协议"，这给了公司
一些对你们项目的控制权，特别是当项目和公司的业务有着很多的联系或者你们使用公司的
资源发展项目。你的公司 _应该_ 很容易地给你许可，也许已经通过一个员工友好的知识产
权协议或公司政策。如果不是这样，你么可以谈判（例如，解释你们的项目为公司的专业学
习和发展目标服务），或者你们在找到一个更好的公司前停止你们项目的工作。

**如果你们的开源项目是为了你们的公司，**那么绝对要让他们知道。根据公司的业务需求
和专业知识，你们的法律团队可能已经制定了有关开放源代码许可协议（以及可能还有其他
贡献者协议）的政策，以确保您的项目符合其依赖关系的许可协议。如果不是这样，你们和
他们很幸运！你们的法律团队应该渴望与你们合作，把这个东西搞清楚。你们需要思考这些
事：

- **第三方资源：**你们的项目有其他人创建的依赖或者使用他人的代码？如果这些事开源
  项目，你们需要遵守第三方资源的开源许可协议。首先，选择与第三方资源的开放源许可
  协议一起使用的许可协议（见上文）。如果你们的项目修改或者发布第三方开源资源，那
  么你们法律团队还想知道你们符合第三方开源许可协议的其他条件，例如保留版权声明。
  如果你们使用了其他没有开源许可协议的代码，那么你们可能会要求第三方资源的维护
  者[添加一个开源许可协议](https://choosealicense.com/no-license/#for-users)，要
  是你们得不到许可，你们只能停止使用他们的代码。

* **商业机密：**请考虑项目中是否有公司不想对外公开的东西。如果是这样的话，你们只
  能开源项目的一部分，得保护好公司的商业机密。

* **专利：**你们公司是否申请了与你们项目有关的专利？如果开源源代码，这会对公司的
  专利进行[公开披露](https://en.wikipedia.org/wiki/Public_disclosure)。可悲的是
  ，你们可能被要求等待（或者公司会重新思考应用程序）。如果你们期望从拥有大量专利
  组合的公司的员工那里得到贡献，们的法律团队可能希望你们使用来自贡献者的明确专利
  授权的许可协议（例如 Apache 2.0 或 GPLv3）或其他贡献者协议（见上文）。

* **商标：**认真检查你们的项目
  名[没有与已经存在的商标冲突](https://github.com/liadbiz/opensource-contribute-guide-chinise/blob/master/github-open-source-guide-02.md#避免命名冲突)。
  如果你们将自己公司的商标用于项目，请检查它有没有造成冲突
  。[FOSSmarks](http://fossmarks.org/)是在自由和开源项目的背景下理解商标的实用指
  南。

* **隐私：**你们的项目是否收集了用户数据并存储到公司的服务器？你们的法律团队可以
  帮助你们遵守公司政策和外部法规。

如果你们发布了公司的第一开源项目，为了能通过，以上这些绰绰有余（不要担心，大多数
项目不会引起重大关注）。长期来说，们的法律团队可以做更多的事情，以帮助公司从开源
中获得更多，并保持安全：

- **员工贡献策略：**考虑制定一个公司策略，指明你们的员工如何为开源项目贡献。明确
  的政策将减少你们员工的迷惑，并帮助他们为公司的最佳利益向开源项目做贡献，无论是
  作为他们工作的一部分还是在自由时间。Rackspace
  的[Model IP 和开源贡献策略](https://processmechanics.com/2015/07/23/a-model-ip-and-open-source-contribution-policy/)就
  是很好的示例。

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/vanl?s=180" class="pquote-avatar" alt="avatar">
  放弃与补丁相关的知识产权以构建员工知识库和信誉。它表明，公司关心员工的发展，以及让员工有种被赋权和自主的感觉。所有这些好处还导致更高的士气和更好地保留员工。
  <p markdown="1" class="pquote-credit">
— @vanl, ["A Model IP and Open Source Contribution Policy"](https://processmechanics.com/2015/07/23/a-model-ip-and-open-source-contribution-policy/)
  </p>
</aside>

- **发布什么
  ：**[（几乎） 所有？](http://tom.preston-werner.com/2011/11/22/open-source-everything.html)如
  果你们的法律团队了解并投资于你们公司的开源策略，他们将是你们最好的帮助，而不是
  阻碍你们的努力。
- **合规性：**即使你们公司没有发布任何开源项目，他们也会使用别人的开源软件
  。[意识和过程](https://www.linuxfoundation.org/blog/2015/06/why-companies-that-use-open-source-need-a-compliance-program/)可
  以避免麻烦，产品延迟发布和诉讼。

<aside markdown="1" class="pquote">
  组织必须具有适合["允许"和"copyleft"]类别的许可协议和合规性策略。首先，记录适用于你们所使用的开源软件的许可条款（包括子组件和依赖项）。
  <p markdown="1" class="pquote-credit">
— Heather Meeker, ["Open Source Software: Compliance Basics And Best Practices"](https://techcrunch.com/2012/12/14/open-source-software-compliance-basics-and-best-practices/)
  </p>
</aside>

- **专利：**你们的公司可能希望�
  入[开放发明网络](http://www.openinventionnetwork.com/)，一个共享的专利防御池，
  以保护成员使用主要开源项目，或探索其他替代专利许可。

- **管理：**特别是当如果将项目转移到公司以外的法律实体是有意义的。
