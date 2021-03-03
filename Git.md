# Git

![image-20210202184125199](C:\Users\mengchong\AppData\Roaming\Typora\typora-user-images\image-20210202184125199.png)

配置码云SSH免密登录命令，回车三次：

ssh-keygen -t rsa -C "13206451612@163.com"

![image-20210202184630083](C:\Users\mengchong\AppData\Roaming\Typora\typora-user-images\image-20210202184630083.png)

查看完整秘钥命令：

cat ~/.ssh/id_rsa.pub

配置码云SSH公钥

![image-20210202184938402](C:\Users\mengchong\AppData\Roaming\Typora\typora-user-images\image-20210202184938402.png)

使用命令测试是否成功

ssh -T git@gitee.com

![image-20210202185143452](C:\Users\mengchong\AppData\Roaming\Typora\typora-user-images\image-20210202185143452.png)

以后通过git客户端推送至码云则不需要填写账号和密码了