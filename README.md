# 你好 —— 我的第一个网页

一个只有两个字的网页:"你好"。用于演示**纯静态网页从零部署到公网**的完整流程。

## 🌐 在线访问

**https://qingjing-ding.github.io/hello-page/**

任何设备、任何地区的浏览器打开即可看到(手机/电脑均可)。

## 它是怎么上线的

网页是一个 `index.html` 文件,托管在 **GitHub Pages**(GitHub 免费的静态网站托管服务):
每次向 `main` 分支推送代码,GitHub 自动把文件发布到上面的网址,**没有打包、没有编译环节**。

## 目录结构

```
hello-page/
├── index.html          # 网页本体(首页约定名必须是 index.html)
├── 网页部署教程.md      # ⭐ 从注册账号到买服务器/域名/备案的完整部署教程
└── README.md
```

## 想改内容?

**方式一(零门槛)**:GitHub 网页上点开 `index.html` → 铅笔图标编辑 → Commit changes,约 1 分钟自动生效。

**方式二(命令行)**:

```powershell
cd D:\Study\hello-page
notepad index.html
git add . ; git commit -m "更新内容"; git push
```

改完没变化?浏览器 **Ctrl+F5** 强制刷新。

## 详细教程

⭐ **[网页部署教程.md](./网页部署教程.md)** —— 给完全没接触过的人写的:

- 路线 A:GitHub Pages 免费部署(纯网页点击版 + 命令行版)
- 路线 B:国内云服务器 + 买域名 + ICP 备案 + 宝塔面板部署(含购买链接、价格、流程)
