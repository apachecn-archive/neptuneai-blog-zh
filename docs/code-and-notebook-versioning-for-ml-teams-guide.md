# ML 团队的代码和笔记本版本控制[工具]

> 原文：<https://web.archive.org/web/https://neptune.ai/blog/code-and-notebook-versioning-for-ml-teams-guide>

作为一名数据科学家或机器学习工程师，你可能经历过这种情况:

你开始在你的 Jupyter 笔记本上写代码，做你的探索，预处理你的数据，建立你的模型并保存它们…但是然后你[失去了跟踪哪个代码](https://web.archive.org/web/20221206030524/https://www.quora.com/What-do-you-do-when-your-code-gets-so-large-that-you-start-losing-track-of-which-class-does-what)和笔记本版本是最好的。

有传统的工具，像 git 和其他源代码和笔记本版本管理系统，但是它们并不特别适合在开发和实验阶段提高 ML 团队的生产力。

这就是为什么在这篇文章中，**我将列出一些工具，它们将为你和你的团队提供一个更有条理的平台，让你拥有和使用不同版本的实验笔记本**，提高你的生产力和效率(包括你整个团队的生产力和效率)。

到本文结束时，您应该已经:

*   了解对您的笔记本进行版本管理的必要性。
*   了解选择笔记本版本控制工具时要考虑的因素。
*   了解管理笔记本和代码版本的 5 大工具。

选择笔记本版本管理工具或平台时，以下是需要考虑的最重要的几点:

*   **笔记本检查点/提交:**您应该能够恢复到您版本化的笔记本中以前的检查点，并比较不同检查点之间的变化。
*   **比较不同的笔记本:**你应该能够比较不同笔记本之间的差异和变化。
*   **团队协作:**您应该能够通过共享、笔记本中的评论和聊天功能(这样可以避免不必要的会议)、笔记本中的结果描述、笔记本版本与团队进行的实验之间的直接链接以及其他协作功能，在各种笔记本版本上与队友高效协作。
*   **定价选项:**工具/平台是免费的还是付费的？付费工具有哪些选择和不同的方案？它们与开源工具相比如何？

以下是对您的笔记本进行版本管理以有效管理实验的 5 大工具。

|  | Neptune.ai | 评论 NB | SageMaker Studio | nedime | 彗星 |
| --- | --- | --- | --- | --- | --- |
| 

**笔记本检查点/提交**

 | 

提供存储笔记本检查点的支持。

 | 

与 GitHub 集成良好，但不存储检查点文件。

 | 

存储笔记本检查点，跟踪新提交。

 | 

跟踪每个新的检查点并提交。

 | 

不存储或跟踪检查点文件或提交。

 |
| 

**笔记本对比功能**

 | 

支持比较不同笔记本和笔记本版本。

 | 

仅跟踪一个笔记本中的更改，但不提供跨笔记本版本比较。

 | 

为笔记本提供笔记本差异支持，但不支持跨笔记本版本比较。

 | 

可以比较不同笔记本和版本，甚至可以将所有改动合并到一个笔记本中。

 | 

不提供笔记本对比功能。

 |
|  | 

轻松共享和跟踪笔记本数据，从笔记本作者到描述、上次保存检查点的时间以及相关实验。

 | 

非常适合笔记本代码审查和无缝团队协作。

 | 

受限笔记本链接分享选项，只有 AWS 授权用户，不能在笔记本内发表评论进行团队交流。

 | 

不支持链接共享，但与现有 Git 工作流集成良好。

 | 

团队协作有利于机器学习项目管理 SaaS。

 |
|  |  | 免费用于开源和教学目的，10 人以下的团队起价 79 美元。 | 

AWS 用户免费，但您需要为运行笔记本工作负载的计算实例付费。

 | 

开源；完全免费。

 | 

为个人用户提供免费的有限功能，最多 5 人的团队起价 179 美元。

 |

现在，让我们详细回顾一下。

如果你正在寻找一个可以管理你所有实验元数据和你团队开发过程的平台，只需看看 Neptune.ai. Neptune 现在是 MLOps 的元数据存储，为运行大量实验的研究和生产团队构建。它对于管理不同的笔记本版本也非常有用，并在一个选项卡中向您显示不同的笔记本版本以及它们的创建者。Neptune.ai 客户端也可以帮助您管理本地笔记本电脑。

#### 使用 Neptune.ai 的笔记本检查点/提交

Neptune.ai 不仅可以有效地管理各种笔记本版本，还可以管理每个笔记本的检查点文件，以便您可以跨检查点跟踪更改和差异。

您还可以比较两个检查点之间的差异和变化。

#### 使用 Neptune.ai 平台比较不同的笔记本

除了比较检查点，您还可以比较来自不同或相同实验的不同笔记本版本。通过这种方式，你和你的团队可以做出最明智的决策，包括其他功能，如跟踪日志、指标和来自实验的其他元数据，所有这些都由 Neptune.ai 提供

#### 与 Neptune.ai 的团队协作

除了将所有不同的笔记本版本放在一个地方，包括元数据(执行时间、实验指标)，Neptune.ai 还通过向不同的笔记本版本添加描述，以类似 git 的格式保持您的组织和协作。

Neptune.ai 提供了一个丰富的可视化仪表板，让您和您的团队了解谁在您的 ML 实验笔记本的任何特定阶段工作，他们最后一次工作的时间，以及他们对笔记本的易读描述，因此您可以一目了然。

您可以与团队中的任何人共享您的笔记本版本仪表板。这可以帮助您的团队保持高效工作，并从笔记本电脑版本中快速获取最相关的详细信息。

如果需要优先在内部运行所有工作负载，Neptune.ai 也可以在内部托管，以便您的团队进行协作。

#### Neptune.ai 的定价选项

现在你可能会认为这个高效的笔记本版本管理平台的成本很高，对吗？幸运的是，它没有。如果你想将该平台用于你的个人项目，或者工作或研究，Neptune.ai 免费为你提供 100GB 的存储空间，用于存储你的实验笔记本和元数据。

如果你有一个教育机构或者非营利组织，Neptune 免费向你的团队提供他们的整个平台。对于商业机构来说，是有偿的。

如果你在大公司工作，担心每月的费用，你可以随时联系 Neptune.ai，获得更定制的方案。点击查看价格选项[。](/web/20221206030524/https://neptune.ai/pricing)

#### Neptune.ai 入门

迫不及待想开始？太好了！事实上，您现在就可以查看笔记本管理选项卡，并通过点击此处来使用它[。如果你喜欢，](https://web.archive.org/web/20221206030524/https://ui.neptune.ai/neptune-ai/credit-default-prediction/notebooks)[注册](/web/20221206030524/https://neptune.ai/register)，让它成为你的。

ReviewNB 是数据科学社区中最流行的 Jupyter 笔记本工具之一。这是一个 GitHub 验证的应用程序，为笔记本电脑提供了完整的代码审查工作流程。它与 Git 和 Github 很好地集成在一起，并有目的地围绕审查笔记本中的代码而构建。

#### 笔记本检查点/提交

因为 ReviewNB 与 GitHub 集成得很好，所以在相互比较时，它提供了各种检查点、提交(甚至是拉请求)之间的丰富差异。您可以直接从您或团队中的任何其他人那里看到任何提交或拉取请求的丰富笔记本差异。

#### 使用 ReviewNB 比较不同的笔记本

遗憾的是，使用 ReviewNB，您无法比较不同笔记本之间的变化，只能在一个特定的笔记本中进行比较。例如，您可能想要比较使用特定类型预处理的笔记本版本与使用不同类型预处理的笔记本版本。这在 ReviewNB 中是做不到的(如果需要的话 Neptune 会做)。

#### 使用 ReviewNB 进行团队协作

ReviewNB 是在团队协作的基础上构建的。事实上，在他们的主页上，你会注意到该平台针对数据科学协作进行了简化。通过代码审查等功能，ReviewNB 使数据科学团队能够轻松地在任何笔记本单元上撰写评论，提出澄清性问题，并在笔记本单元的上下文中提供反馈。

对于每个打开的新评论或评论，团队可以通过电子邮件直接获得通知。您可以在笔记本 diff 上发表评论以讨论更改，打开每个新评论的讨论主题，并跟踪对话主题。

如果您需要在内部运行所有工作负载，还可以在内部托管 ReviewNB，以便您的团队进行协作。要进行设置，您可以在这里[请求安装](https://web.archive.org/web/20221206030524/https://forms.gle/GJz71UkJ4x1R1boE8)。

#### 评论的定价选项

ReviewNB 是免费的，可以开源使用，也可以用于教育目的(如果你有*)。edu* 邮箱，也可以[报名参加免费发售](https://web.archive.org/web/20221206030524/https://www.reviewnb.com/#pricing)。最多 10 个用户的小团队每月 79 美元，最多 30 个用户的企业每月 249 美元。与 Neptune.ai 选项一样，对于具有无限功能的大型组织，您可以联系团队。

#### ReviewNB 入门

如果你有一个有效的 GitHub 账户，你可以[在这里](https://web.archive.org/web/20221206030524/https://github.com/marketplace/review-notebook-app/plan/MDIyOk1hcmtldHBsYWNlTGlzdGluZ1BsYW4yMDIz#pricing-and-setup)注册。[文档](https://web.archive.org/web/20221206030524/https://docs.reviewnb.com/)组织得很好，便于你开始使用。

根据[官方网站](https://web.archive.org/web/20221206030524/https://aws.amazon.com/sagemaker/studio/)，亚马逊 SageMaker Studio 提供了一个单一的基于网络的可视化界面，您可以在其中执行所有 ML 开发步骤，将数据科学团队的生产力提高了 10 倍。

SageMaker Studio 为您提供了对构建、训练和部署模型所需的每个步骤的完全访问、控制和可见性。显然，它是由 AWS 云提供支持的，因此您只能通过适当的 AWS 授权来访问它。

#### 使用 AWS SageMaker Studio 的笔记本检查点/提交

就像普通的 Jupyter 笔记本一样，SageMaker studio 允许您手动保存笔记本检查点，因此您可以根据需要恢复它们。检查点文件存储在 S3 存储桶中，它是在您创建新环境时自动创建的。您可以使用检查点比较功能来查看最新笔记本版本和检查点文件之间的更改。所有的笔记本元数据也由 Amazon SageMaker 管理。

如果从 Git 存储库中打开一个笔记本，您可以查看该笔记本和上一次 Git 提交之间的差异。

#### 使用 aws pagemaker studio 比较不同的笔记本电脑

同样使用 AWS SageMaker studio，您不能比较不同笔记本之间的变化，而只能在一个特定的笔记本中通过使用任何笔记本差异功能(在 studio 中)来进行比较。

检查一下 [SageMaker Sudio 和 Neptune](/web/20221206030524/https://neptune.ai/vs/sagemakerstudio) 有什么区别

#### 使用 aws pagemaker studio 进行团队协作

使用 AWS SageMaker，您可以执行所有 ML 开发活动，包括笔记本、实验管理、自动模型创建、调试以及模型和数据漂移检测。你可以和你的队友分享你的亚马逊 SageMaker Studio 笔记本。共享的笔记本是副本，您不能修改共享的原始笔记本。

要让您的团队成员进行更改，他们必须为您的原始笔记本创建一个新副本。如果您想要共享您的最新版本，您必须创建新的快照，然后共享它。您也可以决定不包括单元运行的输出。

它有一个很好的 GitHub 集成特性，您可以包含到包含笔记本的 Git 存储库的链接，然后您和您的同事可以协作并为同一个 Git 存储库做出贡献。您的共享选项也非常安全，因为您可以为您希望能够访问您的共享笔记本的特定同事提供 IAM 身份验证。

有了 SageMaker studio，你就不会像我们在 Neptune.ai 和 ReviewNB 上看到的那样，有闲功夫在同事分享的笔记本上留下评论。如果你想做些改变，你必须创建一个新的笔记本副本，这本身就相当有压力和低效。

#### AWS SageMaker Studio 的定价选项

使用 AWS Studio SageMaker 是免费的，但您需要为运行笔记本的计算实例支付标准 SageMaker 价格。

#### aws pagemaker studio 入门

要访问 AWS SagMaker Studio，您必须拥有一个 AWS 帐户，IAM 授权访问 SageMaker。您可以观看 Julien Simons 的网上研讨会,了解 SageMaker studio 的其他产品。您可能希望检查定价，以了解您的免费层或组织计费是否支持任何标准实例。

nbdime 提供了区分和合并笔记本的工具。它是完全开源的，可以在本地工作。它很容易安装非常有用的文件，并有一个活跃的社区。

#### 使用 nbdime 的笔记本检查点/提交

Nbdime 与“git”版本控制有很好的集成，您可以设置它与本地“git”客户端一起工作，因此 git diff & git merge 命令使用 nbdime。ipynb 文件。通过 git 集成，您可以在本地使用 Jupyter 笔记本，并在提交到存储库之前运行“git diff”来查看笔记本发生了什么变化。

#### 使用 nbdime 比较不同的笔记本电脑

使用 nbdime，您可以以终端友好的方式比较两个或更多笔记本版本之间的差异，甚至可以合并多个笔记本，冲突会自动解决。在比较笔记本、图表或其他数据之间的差异时，您也可以获得丰富的视觉体验。

#### 使用 nbdime 的团队协作

凭借其与“git”和“nbmerge”三路合并笔记本自动解决冲突的出色集成，“nbdime”可能是 Jupyter 笔记本最好的完全免费版本控制工具，尤其是对于已经熟悉 git 的团队而言。

#### nbdime 的定价选项

“nbdime”是完全开源的，对各种规模的团队都是免费的。唯一的缺点是您只能在本地使用它，但是如果您和/或您的团队已经将 git 整合到您的工作流中，采用它应该不是一件麻烦的事情。

#### ` nbdime '入门

` nbdime '很容易安装。开始的最好地方是[文档](https://web.archive.org/web/20221206030524/https://nbdime.readthedocs.io/en/latest/)。

我们对代码和笔记本进行版本控制的最后一个工具是 Comet。Comet let's 数据科学团队跟踪、比较、解释和优化他们的实验和模型，为机器学习带来效率、透明度和可再现性。它提供了一个自托管和基于云的元机器学习平台，让数据科学家和团队跟踪、比较、解释和优化实验和模型。

探索[彗星和海王星](/web/20221206030524/https://neptune.ai/vs/comet)的区别

#### 使用 Comet 的笔记本检查点/提交

就版本化笔记本的体验而言，Comet 达不到上面列出的其他选项。与 Neptune.ai 相比，您的检查点文件也不会被保存。

我认为 Comet 实际上是版本化 Python 代码的最佳工具(从这个列表中的一组工具中),并且可以比较各种代码实验中所做更改的差异(当您想要将实验推向生产时，这非常有用)。然而，对于笔记本电脑来说，从数据探索到模型构建，不同的团队在不同的项目阶段工作，它在提供丰富的 Jupyter 笔记本体验方面不如 Neptune.ai 这可能会使团队协作和沟通变得困难。

#### 使用 Comet 的团队协作

Comet 是在开发和生产中管理机器学习项目的最佳工具之一。您可以与您的队友共享您的版本化笔记本，但 Jupyter 笔记本的功能和支持是有限的。您只知道有限的信息，如谁编写了什么笔记本、执行时间、各种版本等等。虽然 Comet 保存了使用 Jupyter 笔记本运行的实验的执行顺序代码，但合作者可以轻松地复制任何实验。

Comet 会自动与项目的 git 库集成，所以如果您的团队已经习惯了“git”工作流，集成 Comet 会很容易。

#### Comet 的定价选项

对于上面列出的所有选项，Comet 是最昂贵的平台。虽然它对单个用户是免费的，但是如果你有一个团队并且想要额外的功能，你可能每月要支付 179 到 249 美元。

你可能想仔细考虑一下你的选择。您可以点击查看[定价页面了解更多信息。](https://web.archive.org/web/20221206030524/https://www.comet.ml/site/pricing/)

#### Comet 入门

要开始使用 Comet，你必须[注册他们的一个定价计划](https://web.archive.org/web/20221206030524/https://www.comet.ml/site/pricing/)。除了 Neptune.ai 的文档之外，[文档](https://web.archive.org/web/20221206030524/https://www.comet.ml/docs/)是我见过的最有条理的文档之一。

## 最后的想法和下一步

我真的希望这篇文章能帮助你理解对你的实验笔记本进行版本控制的必要性，并选择一个适合你或者你和你的团队的平台。

我鼓励你根据自己的需求选择一个平台，在接下来的几天里使用，看看它是否适合你和/或你的团队。

### 参考

1.  [**如何对 Jupyter 笔记本进行版本控制|作者 Amit Rathi |走向数据科学**](https://web.archive.org/web/20221206030524/https://towardsdatascience.com/how-to-version-control-jupyter-notebooks-ccf0be144319)
2.  [**亚马逊 SageMaker Studio——机器学习的第一个 IDE 亚马逊 Web 服务**](https://web.archive.org/web/20221206030524/https://aws.amazon.com/sagemaker/studio/)
3.  [**NBD ime-Jupyter 笔记本的区分和合并-NBD ime 3 . 0 . 0 . B1 文档**](https://web.archive.org/web/20221206030524/https://nbdime.readthedocs.io/en/latest/)
4.  [**FAQ——彗星**](https://web.archive.org/web/20221206030524/https://www.comet.ml/site/faq/)
5.  [**彗星企业:两分钟演示**](https://web.archive.org/web/20221206030524/https://youtu.be/iYb9UPkymAg)