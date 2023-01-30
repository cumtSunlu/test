## git 使用方法

### 配置
```bash
git config --global user.name name
git config --global user.email email
```

### 生成ssh秘钥
```bash
ssh-keygen
```
```bash
cat \c\user\user\.ssh\
```
在git网页端输入秘钥

### 使用
- 拉取最新分支
```bash
git pull git@github.com:cumtSunlu/test.git
```
- 新建个人分支
```bash
PS E:\code\GIT\test> git checkout -b sl/test
Switched to a new branch 'sl/test'
```
- 代码更改后提交
```bash
git add .  //提交代码到暂存区
```
```bash
git commit  //将暂存区代码合并到本地分支
```
```bash
git push  //将本地分支合并到远程分支
```

