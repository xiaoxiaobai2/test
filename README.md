$ git add runoob-test.txt 
$ git commit -m "添加到远程"
master 69e702d] 添加到远程
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 runoob-test.txt

$ git push origin master    # 推送到 Github

git pull origin master --allow-unrelated-histories #加上后面这个选项允许不相关历史提交

创建项目的SSH Key

ssh-keygen -t rsa -C "778998010@qq.com"
