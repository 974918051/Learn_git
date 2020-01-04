### 一、创建新项目
用鼠标在[网页](https://github.com/)上操作，获得项目SSH链接。
### 二、克隆新建项目到本地
```bash
    git clone git@github.com:974918051/Learn_git.git
```
### 三、添加文件到新项目
```bash
touch README.md
vi README.md #自己写点什么
```

```bash
git add READMD.md #添加到盘子里（我是这样理解的，杰哥也是）
```

```bash
git status
```

### 四、commit（存盘）
```bash
git commit -m "添加一个README.md"
```

### 五、push到云端
```bash
git push -u origin master #master是主分支
```