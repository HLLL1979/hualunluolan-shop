# B2C商城 - Vercel部署指南

## 项目简介
B2C独立商城模板，支持在线选购、购物车、订单管理等功能。

## 快速部署步骤

### 1. 准备工作
- 注册 [GitHub](https://github.com) 账号
- 注册 [Vercel](https://vercel.com) 账号（用GitHub登录）

### 2. 创建GitHub仓库
1. 登录 GitHub
2. 点击右上角 "+" → "New repository"
3. 仓库名：`hualunluolan-shop`
4. 选择 "Public"（公开）
5. 点击 "Create repository"

### 3. 上传代码到GitHub
```bash
# 在本地项目目录执行
cd vercel-shop
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/你的用户名/hualunluolan-shop.git
git push -u origin main
```

### 4. Vercel自动部署
1. 登录 [vercel.com](https://vercel.com)
2. 点击 "Add New Project"
3. 选择 `hualunluolan-shop` 仓库
4. 点击 "Import"
5. 保持默认设置，点击 "Deploy"
6. 等待1-2分钟，部署完成

### 5. 访问网站
- Vercel会自动分配域名：`https://hualunluolan-shop.vercel.app`
- 可以绑定自定义域名（在Vercel设置中）

## 更新网站
每次推送代码到GitHub，Vercel会自动重新部署：
```bash
git add .
git commit -m "更新内容"
git push
```

## 绑定自定义域名（可选）
1. Vercel控制台 → Project Settings → Domains
2. 输入你的域名，如 `hualunluolan.com`
3. 按提示在域名服务商添加DNS记录
4. 等待DNS生效（通常几分钟到几小时）

## 免费额度说明
- 每月 100GB 带宽
- 每月 1000 个构建小时
- 对于小型B2C商城完全够用

## 联系信息
- 店铺：（请填写店铺名称）
- 地址：（请填写地址）
- 联系人：（请填写联系人）
- 电话：（请填写电话）
