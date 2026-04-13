# 🚀 Git 最实用基础流程（新手必背，一次学会）
我给你整理**最简单、最常用、工作中天天用**的 Git 完整流程，**直接复制就能用**！

---

# 一、第一次使用（配置身份）
**只需要配置 1 次**
```bash
git config --global user.name "qh-Z"
git config --global user.email "qh.zhao1999@outlook.com"
```

---

# 二、新建项目（本地 → GitHub）
## 1. 进入文件夹
```bash
cd 你的项目文件夹
```

## 2. 初始化 Git
```bash
git init
```

## 3. 添加文件
```bash
git add .
```

## 4. 提交版本
```bash
git commit -m "第一次提交"
```

## 5. 关联 GitHub
```bash
git remote add origin git@github.com:qh-Z/你的仓库名.git
```

## 6. 推送到 GitHub
```bash
git push -u origin main
```

---

# 三、日常开发流程（修改代码后）
**以后每次改代码，只需要这 4 行！**
```bash
git add .                # 保存所有修改
git commit -m "修改说明"  # 提交版本
git pull                 # 拉取远程最新代码
git push                 # 推送到 GitHub
```

---

# 四、最常用 8 条命令（必背）
```bash
git status        # 查看当前修改状态
git add .         # 添加所有修改
git commit -m ""  # 提交
git push          # 上传到 GitHub
git pull          # 下载最新代码
git log           # 查看提交历史
git branch        # 查看分支
git clone 地址    # 下载别人的项目
```

---

# 五、一句话记住 Git
**写代码 → 保存修改 → 提交版本 → 同步到 GitHub**

---
