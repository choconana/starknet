# Starknet 残酷共学

> Starknet 残酷共学 by LXDAO & Starknet Astro & AAStar

## 什么是残酷共学（Intensive Co-learning）？

残酷共学是由 [Bruce Xu](https://twitter.com/brucexu_eth) 首创的一种学习模式，目前由 [LXDAO](https://lxdao.io/) 组织并运营残酷共学品牌。
共学有很多种，「残酷共学」与之不同的是「残酷」：

- 你必须每天围绕某个「共学主题」进行学习，每周只有两次请假机会，通常每天至少需要花费半个小时（最好一个小时）来学习。
- 你必须提交你的学习证明（按照共学内容设计）到这个「仓库」来证明你今天学习了。
- 如果你没有完成上面两点，你会立刻被踢掉并且标记为 ❌ 失败。
- 每期残酷共学以 4 周为一个周期，第一周为共学启动报名和熟悉共学规则，第二周到第四周将正式启动共学，为期 21 天，中途不得加入。
- 共学方向包括不限于：英语、以太坊、Web3 技术、DAO、加密思潮等，自由自主发起。共学的过程包括且不限于：观看视频、阅读书籍与文章、项目实战等。

报名方式是完全基于 GitHub 的流程，通过提交 PR 进行申请，合并 PR 之后拥有更新权限。如果你不熟悉 GitHub 和 Git 的操作，请先自行学习。通常还会有一个小型的 Telegram 交流群方便交流。

关于更多「残酷共学」的介绍请参见：https://forum.lxdao.io/t/topic/1654

关于更多正在发生的残酷共学请参见：https://intensivecolearn.ing/

如果你有任何有关残酷共学的疑问或者想法，请到 [残酷共学 Telegram 群](https://t.me/LXDAO/6215) 联系我们。

## Starknet 残酷共学

Starknet 残酷共学是由 LXDAO、Starknet Astro、AAStar 联合发起，旨在帮助大家更好地了解、学习、部署 Starknet 网络并加以实战。

## 共学内容


主要参考
Starknet Book
cairo book
# 工具准备（前面应该讲过了，略过，或者补充前面没讲的）

asdf(可选) [Getting Started | asdf (asdf-vm.com)](https://asdf-vm.com/guide/getting-started.html#official-download)
scarb [Scarb, the Cairo and StarkNet development toolchain (swmansion.com)](https://docs.swmansion.com/scarb/)
starkli [Starknet 之书 - The Starknet Book](https://book.starknet.io/zh-cn/title-page.html)
Katana [Katana: 本地节点 - The Starknet Book](https://book.starknet.io/zh-cn/ch02-05-katana.html)

# 编写合约

（看时间，可以copy也可以手写）
有两个版本，用openzepplin的和自己写的，二选一

- 用foundry来开发和测试
# 部署合约

- 部署到katana
- 部署到测试网
# 验证合约
- sncast verify
# 与合约交互
- 区块浏览器
- 前端
# 前端代码（略）


## 共学时间

- 报名截止时间：9.9 - 9.15
- 本期共学开始时间：9.18
- 本期共学持续时间：21 天（我们默认为 21 天，21 天为养成一个新习惯的周期，可根据自己的内容和课程来制定，但不易过长或过短）

## 共学规则

- 报名规则：请在报名截止时间前进行报名，共学一旦开始后，不得中途加入
- 打卡规则：建议你每天学习 30 ～ 60 分钟，并将学习笔记提交，我们会自动更新你的打卡状态，每周有两次请假的机会，超过后状态变为 ❌，视为本次共学失败
- 激励规则：（如果有具体的激励方式请写明）（没有激励方案默认文案参考：通过本次共学学到的知识，就是你给自己最好的激励！）
- 考核规则：（如果有具体的考核方式请写明，没有就不写）

## 如何报名和打卡？

因为残酷共学的报名和打卡是基于 GitHub 进行开展的，如果你是非开发者或者对 git 操作不熟悉，请先阅读此文档：[残酷共学 GitHub 新手教程](https://www.notion.so/lxdao/GitHub-53fca5ba49bb40c69e4e40e69f58f416)

- 报名:

  - Step01：Fork 本仓库。
  - Step02：复制 Template.md 创建你的个人笔记文件，并根据文档指引填写你的信息，并将文件重命名为你的名字：YourName.md。
  - Step03：创建一个 PR 到当前仓库，本残酷共学助教会对你的 PR 进行 review，review 通过后，你的 PR 会被 merge 到 main 分支，这个时候你会收到邀请加入这个仓库 contribution 的邮件，接受邀请后，你会自动获得 main 分支的 push 权限。
  - Step04：完成以上三个步骤，恭喜你报名成功，后续就可以将你的学习记录直接 push 到 main 分支进行更新。
  - 请加入微信群组保持交流：。加入群组后请在群里报到一下方便助教记录。

- 打卡：
  - 报名成功后，你将拥有 main 分支的 push 权限，你需要将每天学习笔记按日期更新到你的 YourName.md 文档中，提交更新后，我们会自动更新你的打卡状态到下面的打卡记录表。
  - 如果你不在 UTC+8 时区，需要添加时区 code 到你的 YourName.md 文件的开始，错误的时区设置可能会使自动化打卡脚本错误计算打卡时间，具体请参考：https://github.com/IntensiveCoLearning/template/blob/main/Template.md?plain=1#L1
  - 当你提交笔记时，请确保以下几点，否则打卡可能会失败：
    - 在 YourName.md 文档，请将笔记内容放到以下代码块中，且 `<!-- Content_START -->` 和 `<!-- Content_END -->` 不能删除:
    ```
    <!-- Content_START -->
    ### 日期
    笔记内容
    <!-- Content_END -->
    ```
    - 日期格式为 `### 2024.07.11`，请不要随意更改

## {本期残酷共学名字}打卡记录表

✅ = Done ⭕️ = Missed ❌ = Failed

<!-- START_COMMIT_TABLE -->

| Name(GitHub ID) | 9.18 | 9.19 | 6.26 | 6.27 | 6.28 | 6.29 | 6.30 | 7.01 | 7.02 | 7.03 | 7.04 | 7.05 | 7.06 | 7.07 | 7.08 | 7.09 | 7.10 | 7.11 | 7.12 | 7.13 | 7.14 |
| --------------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|                 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |

<!-- END_COMMIT_TABLE -->

<!-- STATISTICALDATA_START -->
<!-- STATISTICALDATA_END -->

> 如果你是此次共学发起人，请进行以下操作进行自动化发放权限的设置，完成后请将这一部分内容从你的仓库中删掉。

### 为您的组织 【残酷共学营】 创建具有邀请协作者权限的个人访问令牌

要创建具有邀请协作者权限的个人访问令牌，请按照以下步骤操作：

1. 导航到您的个人设置: 转到 https://github.com/settings/profile 并登录您的 GitHub 帐户。

2. 访问个人访问令牌页面: 在左侧菜单中，单击 “开发者设置”，然后选择 “个人访问令牌”。

3. 创建新令牌: 点击 “生成新令牌” 按钮。选择 classic 的

4. 命名您的令牌: 在 “令牌名称” 字段中输入一个描述性名称，例如 `invite-collaborators`。

5. 选择适当的范围: 在 “范围” 部分，选择授予您的令牌所需的权限。对于邀请协作者，您需要授予以下范围：

- `repo:invite`：允许您的令牌创建存储库邀请。最好是给这个令牌赋予 repo 总权限
- `admin:org` 权限的用户才能创建具有邀请协作者权限的个人访问令牌。

6. 将令牌值添加到存储库 secret: 按照上述步骤将您的个人访问令牌值添加到您的存储库 secret 中，并将名称设置为 `PAT_WITH_INVITE_PERMISSIONS`。

![image](https://github.com/user-attachments/assets/d7c06540-9076-4557-b911-e5e484a742bb)

### 配置共学信息配置变量

1. 配置这四个仓库变量(Repository variables)，注意不要添加**换行**，**空格**符号

| Field Name  | Value                     | Comments                        |
| ----------- | ------------------------- | ------------------------------- |
| START_DATE  | 2024-06-24T00:00:00+00:00 | Start time                      |
| END_DATE    | 2024-07-06T23:59:59+00:00 | End time                        |
| FIELD_NAME  | EICL1st· Name             | Field name in the readme        |
| FILE_SUFFIX | _EICL1st.md_              | Shared learning activity number |

![image](https://github.com/user-attachments/assets/d5b6f504-9eea-4215-9848-056fc33f00f8)
