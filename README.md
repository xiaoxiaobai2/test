$ git add runoob-test.txt 
$ git commit -m "添加到远程"
master 69e702d] 添加到远程
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 runoob-test.txt

$ git push origin master    # 推送到 Github

git pull origin master --allow-unrelated-histories #加上后面这个选项允许不相关历史提交

创建项目的SSH Key

ssh-keygen -t rsa -C "778998010@qq.com"

设置当前分支为默认分支
git config --global push.default "current"

生成 id_ras.pub（公钥） 和 id_rsa(私钥)

git bush here
(先查看是否拥有)
1.输入：cd ~/.ssh

2.然后输入ls查看秘钥列表：

（创建公钥和私钥）
1.输入命令：cd  ~

2.然后输入：ssh-keygen.exe

然后按回车，再次按回车，在回车，按三次回车：（不设置密码）
复制公钥到 github
