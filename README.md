[TOC]

![Snipaste_2023-09-30_14-41-09](.\image\Snipaste_2023-09-30_14-41-09.png)

#### 1、新建远程代码仓库

![Snipaste_2023-09-29_13-43-25](.\image\Snipaste_2023-09-29_13-43-25.png)

![Snipaste_2023-09-29_13-43-48](.\image\Snipaste_2023-09-29_13-43-48.png)

![Snipaste_2023-09-29_13-45-15](.\image\Snipaste_2023-09-29_13-45-15.png)![Snipaste_2023-09-29_13-47-01](.\image\Snipaste_2023-09-29_13-47-01.png)![Snipaste_2023-09-29_13-50-06](.\image\Snipaste_2023-09-29_13-50-06.png)![Snipaste_2023-09-29_13-53-58](.\image\Snipaste_2023-09-29_13-53-58.png)

#### 2、创建 develop 分支

![Snipaste_2023-09-30_10-54-04](.\image\Snipaste_2023-09-30_10-54-04.png)

![Snipaste_2023-09-30_14-42-46](.\image\Snipaste_2023-09-30_14-42-46.png)

![Snipaste_2023-09-30_11-18-11](.\image\Snipaste_2023-09-30_11-18-11.png)

![Snipaste_2023-09-30_11-22-31](.\image\Snipaste_2023-09-30_11-22-31.png)

![Snipaste_2023-09-30_11-23-59](.\image\Snipaste_2023-09-30_11-23-59.png)![Snipaste_2023-09-30_11-25-25](.\image\Snipaste_2023-09-30_11-25-25.png)

![Snipaste_2023-09-30_11-26-23](.\image\Snipaste_2023-09-30_11-26-23.png)![Snipaste_2023-09-30_11-27-05](.\image\Snipaste_2023-09-30_11-27-05.png)

#### 3、团队成员加入项目

![Snipaste_2023-09-30_10-45-47](.\image\Snipaste_2023-09-30_10-45-47.png)![Snipaste_2023-09-30_10-48-20](.\image\Snipaste_2023-09-30_10-48-20.png)![Snipaste_2023-09-30_10-48-56](.\image\Snipaste_2023-09-30_10-48-56.png)

#### 4、克隆远程代码仓库到本地

![Snipaste_2023-09-30_11-32-58](.\image\Snipaste_2023-09-30_11-32-58.png)

![Snipaste_2023-09-30_11-32-58](.\image\Snipaste_2023-09-30_11-32-58.png)

```bash
git clone <远程仓库地址>
```

![Snipaste_2023-09-30_11-36-00](.\image\Snipaste_2023-09-30_11-36-00.png)

**在本地新建develop分支，并切换到该分支**

```bash
git checkout -b develop
```

![Snipaste_2023-09-30_11-49-04](.\image\Snipaste_2023-09-30_11-49-04.png)

**拉取远程代码仓库develop分支的代码**

```bash
git pull origin develop
```

![Snipaste_2023-09-30_11-49-23](.\image\Snipaste_2023-09-30_11-49-23.png)

![Snipaste_2023-09-30_14-41-39](.\image\Snipaste_2023-09-30_14-41-39.png)

#### 5、添加个人特性分支（特性分支命名规范：feature_xxx）

![Snipaste_2023-09-30_16-34-44](.\image\Snipaste_2023-09-30_16-34-44.png)

```bash
# 新建 feature_view_login 分支
git branch feature_view_login
```

```bash
# 切换到 feature_view_login 分支
git checkout feature_view_login
```

![Snipaste_2023-09-30_11-54-56](.\image\Snipaste_2023-09-30_11-54-56.png)

#### 6、推送个人特性分支

**完成自己负责的模块之后，将个人特性分支上传到远程代码仓库**

![Snipaste_2023-09-30_12-41-27](.\image\Snipaste_2023-09-30_12-41-27.png)

#### 7、发起分支合并请求

![Snipaste_2023-09-30_13-21-50](.\image\Snipaste_2023-09-30_13-21-50.png)

![Snipaste_2023-09-30_13-24-36](.\image\Snipaste_2023-09-30_13-24-36.png)

![Snipaste_2023-09-30_13-29-41](.\image\Snipaste_2023-09-30_13-29-41.png)

#### 8、分支管理员在本地拉取合并请求的代码，检查代码规范，安全性等问题

![Snipaste_2023-09-30_13-51-12](.\image\Snipaste_2023-09-30_13-51-12.png)

![Snipaste_2023-09-30_14-01-47](.\image\Snipaste_2023-09-30_14-01-47.png)

![Snipaste_2023-09-30_14-42-05](.\image\Snipaste_2023-09-30_14-42-05.png)

#### 9、合并master分支

![Snipaste_2023-09-30_14-05-55](.\image\Snipaste_2023-09-30_14-05-55.png)

#### 10、效能洞察

![Snipaste_2023-09-30_14-43-19](.\image\Snipaste_2023-09-30_14-43-19.png)



![Snipaste_2023-09-30_14-07-57](.\image\Snipaste_2023-09-30_14-07-57.png)

![Snipaste_2023-09-30_14-08-23](.\image\Snipaste_2023-09-30_14-08-23.png)

![Snipaste_2023-09-30_14-09-09](.\image\Snipaste_2023-09-30_14-09-09.png)

![Snipaste_2023-09-30_14-39-01](.\image\Snipaste_2023-09-30_14-39-01.png)