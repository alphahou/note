### heroku简单部署

---

```
cd project.git // 进入git仓库所在文件夹
heroku login // 登录heroku
heroku create // 将此项目链接到heroku
git push heroku master // 将项目推送至远程heroku
heroku ps:scale web=1 // 申请一个dyno
heroku open // 打开heroku的服务器
heroku run bash // 进入heroku的linux
```

