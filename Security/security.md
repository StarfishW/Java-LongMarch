# 安全
> 当前篇幅所讲述的并非宽泛的网络安全而是Java层面的
>
> 举个栗子🌰
>
> 学生系统管理后台 ， 学生是不能修改成绩的（正常情况），但是教师是可以修改的，那么相同的后台是如何区分用户并授予权限的呢
## Spring Security
> [!TIP]
>  如果你的项目是基于 Spring Boot 构建的话，强烈建议使用 Spring Security  [官方网址](https://spring.io/projects/spring-security#learn)

### Spring Security的核心

**`认证`**
你谁呀？

**`授权`**
你干啥？（或者说成 你能干啥？）
