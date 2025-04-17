# 将示例数据与 Microsoft 365 Copilot 配合使用

在这些实验室中，我们将为 Microsoft 365 Copilot 创建引用以下文件的提示：

- [Promotion Plan for Chai Tea in Latin America.docx](https://go.microsoft.com/fwlink/?linkid=2269126)
- [神秘香料臻品印度奶茶市场分析报告.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [2023 年 Contoso 印度奶茶市场趋势.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

为确保这些文件后续可供 Microsoft 365 Copilot 访问，我们首先会将其上传到 OneDrive。

## 将文件上传到 OneDrive

按照以下步骤将所需的所有文件上传到 **OneDrive**：

1. 使用本地**管理员**帐户和密码 `Pa55w.rd` 登录到租户提供程序提供的虚拟机。

2. 在 Windows 搜索栏中输入 **OneDrive**，即可打开 **OneDrive** 应用程序。

3. 在**电子邮件地址**提示处，输入 userx@yourtenant.onmicrosoft.com（由租户提供方提供），然后选择“登陆”****。

4. 在“**输入密码**”屏幕上，输入 Password1（由租户提供程序提供），然后选择“**登录**”。

5. 如果系统提示**是否自动登录到此设备上的所有桌面应用和网站？**，请选择**是，所有应用**。

6. 打开 OneDrive 文件夹。
   
7. 在“**文件资源管理器**”的新实例中，选择“**此电脑**” > “**本地磁盘 (C:)**”，然后打开“**MS-4018 ResourceFiles**”文件夹。

8. 选择“**MS-4018 ResourceFiles**”文件夹中的所有文件，然后将其拖放到 OneDrive 文件夹。

9. 上传完成后，应该会在屏幕底部中央看到“**已上传 3 个项目到‘我的文件’**”。


### 引用文件

从 Copilot 引用文件时，你可能会发现，无法从提供的建议中找到某些文件。 有时会出现这种情况，因为 Copilot 的某些体验只能引用最近使用 (MRU) 列表中的文件，而其他体验则可以让你浏览 OneDrive 查找文件。 将它们添加到该列表非常简单，就像在相应的 Microsoft 365 应用中打开它们一样简单。  打开后，它们应显示在 MRU 列表中。

> [!IMPORTANT]
> Microsoft 365 Copilot 将仅处理保存到 OneDrive 的文件。 如果文件存储在本地电脑上，则需要将其移动到 OneDrive 才能激活 Copilot。

随着本实验室的深入，你将有机会针对这些文件尝试其他提示，我们鼓励你执行此操作，以探索和增强提示技能。
