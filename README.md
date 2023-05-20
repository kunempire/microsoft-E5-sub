# guidance
https://www.bilibili.com/video/BV1rs4y197A5

高清重置版本：已经去隐私信息，审核大大辛苦了(◦˙▽˙◦)

2023年4月25日更新公告：最新的onedrive5T网盘申请教程请看：BV1Rs4y197pU

上述使用了GitHub的订阅开发者账号方法，采用双保险，更加稳定。此处推荐。

2023为什么我推荐你使用Microsoft365办公-效率之神，你觉得OneDrive没用那是你没用好

# 主要涉及的网址
进入开发者官网：https://developer.microsoft.com/en-us/microsoft-365/dev-program

应用平台：https://portal.azure.com

# 工具
green-hub

# import repository
You should import repository "https://github.com/vcheckzen/KeepAliveE5.git"

Set the following repo secrets, disable the security defaults of your E5 admin accounts, then trigger `Register APP` workflow manually. Read [The Intro](https://logi.im/script/permanently-keeping-an-office-e5-account.html) for step by step instructions.

| Name   | Value                                                             |
| ------ | ----------------------------------------------------------------- |
| PAT    | Github personal access token with `workflow` permission           |
| USER   | E5 admin emails line separated, no leading and trailing spaces    |
| PASSWD | E5 admin passwords line separated, no leading and trailing spaces |

三个指标：

PAT的值为上文申请的PAT密钥；

USER的值为申请的E5管理员账号，支持多个，每行一个。

PASSWD的值为E5管理员账户密码，支持多个，每行一个。

注意和USER值顺序一致。

<p align="right"><code>version@202305070221</code></p>
