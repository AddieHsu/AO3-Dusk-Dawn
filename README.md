一款为 Archive of Our Own (AO3) 设计的暖色调皮肤，能自动根据设备的系统设置，在浅色和深色模式之间无缝切换。

## ☀️ 浅色模式 - Dawn 预览

<table>
  <tr>
    <td><img width="564.5" height="497.5" alt="image" src="https://github.com/user-attachments/assets/f0c66009-7533-41c5-b102-04e85bb42d12"></td>
    <td><img width="564.5" height="497.5" alt="image" src="https://github.com/user-attachments/assets/36b44de2-cc7a-4e87-8645-b36637db6030"></td>
  </tr>
</table>

## 🌙 深色模式 - Dusk 预览

<table>
  <tr>
    <td><img width="564.5" height="497.5" alt="image" src="https://github.com/user-attachments/assets/89ca3ab4-607b-4dfe-b730-0e43252cf7bd"></td>
    <td><img width="564.5" height="497.5" alt="image" src="https://github.com/user-attachments/assets/781f04ab-d005-4d41-a62f-5c574f4c466c"></td>
  </tr>
</table>


---

## ✨ 主要特色
* **深浅主题全自动切换：** 无需手动操作，跟随系统自动应用相应主题。
* **护眼界面：** 浅色和深色模式均采用了温暖的棕色调，提升阅读体验更护眼。
* **UI优化**：标签和文本框更现代、美观、可读性更强。
* **字号调整**：调整了正文字号，使之更适于移动端阅读。


---

## 🚀 安装指南 (重要!)
- 使用AO3的Parent Skin功能来实现自动切换，需要在 AO3 上**创建三个独立的皮肤**，并按特定顺序将它们链接在一起。
- **请确保自己有可登录AO3主站的账号**：目前只能在AO3主站使用（因为需要用到用户的自定义CSS功能），暂不支持镜像站/游客状态使用。
### 第 1 步：创建浅色主题
1.  转到 **My Skins**-> **Create Site Skin** 。
2.  **Title:** `Dusk & Dawn (Light)`（只是示例！请起一个不和其他人重复的标题1）
3.  **CSS:** 将“Light Mode.CSS”**文件中的所有代码**完整粘贴进去。
4.  **【关键步骤】**
    * 向下滚动到 **Advanced，点击Show**。
    * 在 **Media** 框中，勾选：`(prefers-color-scheme: light)`
5.  点击 **Submit** 。
### 第 2 步：创建深色主题
1.  转到 **My Skins** -> **Create Site Skin**。
2.  **Title:** `Dusk & Dawn (Dark)`（请起另一个不和其他人重复的标题2）
3.  **CSS:** 将“Dark Mode.CSS”**中的所有代码**完整**粘贴进去。
4.  **【关键步骤】**
    * 向下滚动到 **Advanced，点击Show**。
    * 在 **Media** 框中，勾选：`(prefers-color-scheme: dark)`
5.  点击 Submit。
### 第 3 步：创建自动切换主题
1.  转到 **My Skins** -> **Create Site Skin**。
2.  **Title:** `Dusk & Dawn (Auto)`（请起另一个不和其他人重复的标题3）
3.  **CSS:**
    * 请在 CSS 框中粘贴以下这**一条**CSS规则（为了通过 AO3 的CSS验证器，这个框不能为空）：
    ```css
    html {
      --my-skin-is-active: 1;
    }
    ```
4.  **【关键步骤】**
    * 向下滚动到 **Advanced，点击Show**。
    * 找到 **Add Parent Skin**，选择在第 1 步创建的浅色主题。
    * 再次点击 "Add Parent Skin"按钮，选择在第 2 步创建的深色主题。
5.  点击 **Save** (保存)。
### 第 4 步：应用主题
1.  回到 **My Skins**页面。
2.  在 **"Your site skin"** 中，选择在第 3 步中创建的主题：`ao3 - Dusk & Dawn (Actual)`，点击 **USE**。
现在每当你登录自己的AO3账号，主题就可以跟随系统进行切换了！
---

## 📄 许可
本皮肤基于 [MIT License](LICENSE) 授权。请自由地使用、修改和分发！
