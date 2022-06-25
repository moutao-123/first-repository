# typora使用





## 关联git与github

### github部分

#### 公钥创建

如果第一次使用github一定要记得在本地创建一个公钥，保证本地和远端的github是可以连接的，类似于本地需要账号和密码登录远端。



终端中输入"ssh-keygen -o"(下面的密码可以写可以不写)

找到并复制下图选中的地方

![image-20220625161657300](C:/Users/34265/AppData/Roaming/Typora/typora-user-images/image-20220625161657300.png)

GitHub官网-->"settings"-->"SSH and GPG keys"

首先，创建一个仓库。



### git部分

#### 下载

在[Git (git-scm.com)](https://git-scm.com/)中下载git

#### 设置

打开GitBash输入以下命令：

```bash
 git config --global user.name "Your Name"       //Your Name:你的昵称
 git config --global user.email "email@example.com"  //email@example.com:你的邮箱
```

#### 使用

首先，在你想记录内容更改的文件夹中进入GitBash（或者直接在GitBash中利用cd命令进入）

## typora图传github

### 设置PicGo-Core

"打开typora" --> "文件" --> “偏好设置” --> "图像" --> ”上传服务设定“ 后面的选项卡中的 "PicGo-Core(command line)" --> "下载并更新"

### 将PicGo与github账户的仓库相关联

1. 在电脑文件中进入“C:\Users\你电脑的用户名\AppData\Roaming\Typora\picgo\win64”的路径
2. 以cmd命令打开当前文件夹
3. 在终端里输入“picgo set uploader”命令
4. 通过移动光标选择"github",然后回车
5. 在"repo:"后输入       "A"/B"      (A : 自己的github的名字)(B : github中存图片的仓库的名字)
6. "branch:"后输入    "main" 
7. "token:" (**token的获取办法:**    github官网 --> "settings" --> "<>Developer setting" --> "personal access tokens" --> "Generate new token" --> 写上Note的内容后，选中" Select scpoes "  的 "repo"  -->  "Generate token" --> 复制绿色背景中的一串英文)
8. "customUrl:"后输入"https://cdn.jsdeliver.net/gh/你的github名字/你要存图片的仓库名"
9. 输入"picgo use uploader"命令
10. 通过移动光标选择"github",然后回车

 



![image-20220625022646364](https://cdn.jsdelivr.net/gh/moutao-123/first-repository/picture/image-20220625022646364.png)

