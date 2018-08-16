1. `git`修改远程仓库

  a. 修改地址

  ```git
    git remote set-url origin <url>
  ```

  b. 先删除后添加

  ```git
    git remote rm origin
    git remote add origin <url>
  ```
