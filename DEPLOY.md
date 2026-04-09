# G359红色文化旅游攻略 - 部署指南

## 步骤1：创建GitHub仓库

1. 登录GitHub账号
2. 点击右上角的「+」号，选择「New repository」
3. 仓库名称：`g359-red-culture-tour`
4. 选择「Public」
5. 点击「Create repository」

## 步骤2：将本地仓库推送到GitHub

在本地终端中运行以下命令：

```bash
# 添加远程仓库
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/g359-red-culture-tour.git

# 推送到GitHub
git push -u origin master
```

## 步骤3：启用GitHub Pages

1. 进入GitHub仓库页面
2. 点击「Settings」选项卡
3. 选择「Pages」选项
4. 在「Source」部分，选择「main」分支，然后点击「Save」
5. 等待几分钟，GitHub会生成一个公开访问的URL

## 步骤4：生成二维码

1. 复制GitHub Pages生成的URL（格式：https://YOUR_GITHUB_USERNAME.github.io/g359-red-culture-tour/）
2. 使用二维码生成工具（如https://www.qr-code-generator.com/）生成二维码
3. 下载生成的二维码图片

## 步骤5：使用二维码

将生成的二维码打印出来，放置在高铁车厢内，乘客扫码后即可跳转到G359红色文化旅游攻略网页。

## 注意事项

- 确保GitHub Pages已成功启用，URL可以正常访问
- 二维码生成后，建议测试一下扫码是否能正常跳转到网页
- 网页使用了CDN加载资源，确保在高铁上的网络环境下也能正常加载
