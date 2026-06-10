# 赛事预测中心

## 部署到 GitHub Pages（免费）

```bash
# 1. 在 GitHub 新建仓库 sports-predict

# 2. 推送
cd sports-site
git init
git add .
git commit -m "init"
git remote add origin https://github.com/你的用户名/sports-predict.git
git push -u origin main

# 3. 打开仓库 Settings → Pages → 选 main 分支 → Save
# 网址就是 https://你的用户名.github.io/sports-predict
```

## 绑定域名（可选）
Pages 设置里填域名，DNS 加一条 CNAME 指向 `你的用户名.github.io`

## 更新内容
改 html 文件 → git add . → git commit → git push，一分钟生效

## 广告接入
1. Google AdSense：审批通过后把广告代码替换 `ad-placeholder`
2. 百度联盟：同理，需要备案域名

## SEO 优化
- 每个页面都有独立的 title / description / keywords
- robots.txt 和 sitemap 已配好
- 赛事期间每天更新一次内容，搜索排名会逐步上升
