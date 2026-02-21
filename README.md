# MagicMini - 游戏扫码登录助手  [**FREE免费**]

![版本](https://img.shields.io/badge/Version-2.7-blue?style=for-the-badge&logo=appveyor)
![平台](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows)
![最后提交](https://img.shields.io/github/last-commit/GuGuNiu/MagicMimi?style=for-the-badge&logo=github)

  <a href="https://github.com/GuGuNiu/MagicMimiTools">
    <img src="https://count.getloli.com/get/@GuGuNiu-MagicMimiTools?theme=moebooru" alt="Visitor Count" />
  </a>

你是否厌倦了在看直播中每次都需要拿出手机进行抢码登录？MagicMini 将这个过程自动化，助你轻松抢到码。你无需在复杂的找怎么获取账户Cookie了 MagicMini 同样的自动完成了这一步。

---

## ✨ 功能特性

*   **多账户支持**：内置账户管理器。
*   **高自定义性**：
    *   可自由拖动和缩放扫描识别区域。
    *   可锁定扫描框位置。
    *   可自定义登录延迟。
*   **安全与隐私**：
    *   所有账户信息均加密存储在本地。
    *   所有登录验证流程均在本地与官方服务器直接交互，不经过任何第三方服务器。
    
## 📸 软件截图

![image.png](https://s2.loli.net/2025/09/22/Vfe8IBozMDTpkbl.png)

## 🚀 如何使用

####  1.首次配置 - 添加账户

1.  打开软件，点击 **“账户管理”** 按钮。
2.  在账户管理界面，点击 **“新增”**。
3.  为你的账户设置一个**昵称**（例如：“我的大号”）。
4.  获取并粘贴你的 **Stoken**。你有两种方式获取：
    *   **（推荐）使用扫码功能**：点击 **“扫码获取Stoken”**，使用App扫描弹出的二维码，即可自动获取并填充。
    *   **手动获取**：通过其他方式获取到你的Stoken字符串，然后粘贴到输入框中。
5.  点击 **“保存”**。程序会自动从Stoken中提取UID并保存。

#### 2.定位扫描框

1.  此时主窗口会隐藏，屏幕上会出现一个**绿色**的半透明方框。
2.  **拖动并调整**这个方框的大小，使其**刚刚好**覆盖住云游戏中出现的二维码区域。
3.  定位好后，可以点击主界面的 **“锁定扫描框”** 按钮，下次启动时就无需再次调整。

#### 3.自动登录！

一切就绪！现在，当游戏界面出现登录二维码时，MagicMini 会自动检测到它，并完成登录操作。你会在悬浮日志窗口看到整个过程的实时反馈。

## 📝 使用须知

本项目仅供学习和技术交流。请在遵守游戏服务商的用户协议的前提下使用。请在下载后的24小时内删除。

*   [PySide6](https://www.qt.io/qt-for-python) - 用于构建图形用户界面。
*   [OpenCV-Python](https://github.com/opencv/opencv-python) & [Pyzbar](https://github.com/NaturalHistoryMuseum/pyzbar) - 用于二维码的识别。
