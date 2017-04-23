# My_Sublime_User

## SublimeText 配置备份（User 文件夹)

### 使用git同步subl配置和插件

```bash
cd [package folder]/User
git init
```

### 以下文件不需要同步，添加至.gitignore文件：

```bash
Package Control.last-run
Package Control.ca-list
Package Control.ca-bundle
Package Control.system-ca-bundle
Package Control.cache/
Package Control.ca-certs/
encoding_cache.json
.DS_Store
```
### 提交到远程仓库（如：github）

```bash
git add --all
git commit -m "your commit content"
git remote add origin [your git repository]
git push origin master
```

