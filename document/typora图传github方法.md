1、"打开typora" --> "文件" --> “偏好设置” --> "图像" --> ”上传服务设定“ 后面的选项卡中的 "PicGo-Core(command line)" --> "下载并更新"

2、在电脑文件中进入"C:\Users\你电脑的用户名\AppData\Roaming\Typora\picgo\win64"的路径     -->     以cmd命令打开当前文件夹    -->    在终端里输入“picgo set uploader”命令    -->    通过移动光标选择"github",然后回车    -->    在"repo:"后输入       "A"/B"      (A : 自己的github的名字)(B : github中存图片的仓库的名字)    -->    "branch:"后输入    "main"    -->    "token:" (下文讲解) -->"customUrl:"后输入”https://cdn.jsdeliver.net/gh/你的github名字/你要存图片的仓库名“ -->输入"picgo use uploader"命令  --> 通过移动光标选择"github",然后回车



token的获取办法：github官网-->"settings"-->"<>Developer setting"-->"personal access tokens"-->"Generate new token"-->写上Note的内容后，选中" Select scpoes "  的 "repo" --> "Generate token"-->复制绿色背景中的一串英文



![image-20220625022646364](https://cdn.jsdelivr.net/gh/moutao-123/first-repository/picture/image-20220625022646364.png)

