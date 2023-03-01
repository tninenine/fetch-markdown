提交代码 frontend

```
git add .
git commit -m "feat:[XY-21]"
```

1. 提交格式: codetype:#taskId eg: `git commit -m 'feat:[XY-21]'`
2. 不可同时提交 client 、server 中修改的文件
3. 每次代码提交必须提 PR ,不可直接在 master 上提交代码
4. codetype 说明：

- feat: (new feature for the user, not a new feature for build script)
- fix: (bug fix for the user, not a fix to a build script)
- docs: (changes to the documentation)
- style: (formatting, missing semi colons, etc; no production code change)
- refactor: (refactoring production code, eg. renaming a variable)
- test: (adding missing tests, refactoring tests; no production code change)
- chore: (updating grunt tasks etc; no production code change)

5. 分支命名格式: name + task id eg:xxx.xx/CCNU-LAB-1
