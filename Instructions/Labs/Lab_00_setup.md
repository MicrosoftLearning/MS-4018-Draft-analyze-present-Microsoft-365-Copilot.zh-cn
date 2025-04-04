# 将示例数据与 Microsoft 365 Copilot 配合使用

在这些实验室中，我们将为 Microsoft 365 Copilot 创建引用以下文件的提示：

- [Promotion Plan for Chai Tea in Latin America.docx](https://go.microsoft.com/fwlink/?linkid=2269126)
- [神秘香料臻品印度奶茶市场分析报告.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [2023 年 Contoso 印度奶茶市场趋势.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

为确保这些文件后续可供 Microsoft 365 Copilot 访问，我们首先会将其上传到 OneDrive。

## 将文件上传到 OneDrive

按照以下步骤将所需的所有文件上传到 **OneDrive**：

1. 使用本地**管理员**帐户和密码 `Pa55w.rd` 登录到租户提供程序提供的虚拟机。

2. 在 Windows 任务栏上，选择“**Microsoft Edge**”。

3. 在地址栏中输入`https://onedrive.live.com/login`。

4. 在“**欢迎使用 Microsoft 365**”下，选择“**登录**”。

5. 在“**登录提示符**”处，输入userx@yourtenant.onmicrosoft.com（由租户提供程序提供），然后选择“**下一步**”。

6. 在“**输入密码**”屏幕上，输入 Password1（由租户提供程序提供），然后选择“**登录**”。

7. 如果系统提示“**保持登录**”，请选择“**不再显示**”，然后选择“**是**”。

8. 在 **OneDrive** 的左上角，选择“**+**”（添加新的）>“**文件上传**”。

    ![添加新文件的屏幕截图](../Labs/Media/add_new.png)

9. 在**文件资源管理器**中，选择“**此电脑**” > “**本地磁盘 (C:)**”并打开 **ResourceFiles** 文件夹。

10. 选择 **ResourceFiles** 文件夹中的所有文件，然后选择“**打开**”以将其上传到 **OneDrive**。

11. 上传完成后，应该会在屏幕底部中央看到“**已上传 29 个项目到‘我的文件’**”。

12. 保持 **Edge** 打开，然后继续执行下一个任务。

### 引用文件

从 Copilot 引用文件时，你可能会发现，无法从提供的建议中找到某些文件。 有时会出现这种情况，因为 Copilot 的某些体验只能引用最近使用 (MRU) 列表中的文件，而其他体验则可以让你浏览 OneDrive 查找文件。 将它们添加到该列表非常简单，就像在相应的 Microsoft 365 应用中打开它们一样简单。  打开后，它们应显示在 MRU 列表中。

> [!IMPORTANT]
> Microsoft 365 Copilot 将仅处理保存到 OneDrive 的文件。 如果文件存储在本地电脑上，则需要将其移动到 OneDrive 才能激活 Copilot。

随着本实验室的深入，你将有机会针对这些文件尝试其他提示，我们鼓励你执行此操作，以探索和增强提示技能。
