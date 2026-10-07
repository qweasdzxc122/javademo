# javaDemo

Java 学习与练习仓库，用于存放示例代码、练习项目和学习笔记。

## 目录规划

```
javademo/
├── README.md          # 项目说明
├── .gitignore         # 忽略规则
└── spring-petclinic/  # 参考项目（Spring 官方示例，Apache-2.0）
```

后续会按主题逐步补充：

- `java-basics/`：Java 语言基础（集合、并发、IO、泛型、反射等）
- `spring/`：Spring / Spring Boot 相关实践
- `persistence/`：数据库与持久层（JDBC、JPA、MyBatis）
- `web/`：Web 与接口开发
- `notes/`：学习笔记与踩坑记录

## 参考项目：spring-petclinic

`spring-petclinic/` 目录是从 GitHub 克隆的官方示例项目，原作者为 Spring 团队，采用 Apache-2.0 许可，此处仅作学习参考，未做任何修改。

- 上游仓库：https://github.com/spring-projects/spring-petclinic
- 许可证：见 `spring-petclinic/LICENSE.txt`
- 运行方式：进入该目录执行 `./mvnw spring-boot:run`，然后浏览器访问 http://localhost:8080
- 涵盖技术：Spring Boot WebMVC、Spring Data JPA、Thymeleaf、Bean Validation、Cache、Actuator，H2/MySQL/PostgreSQL，Caffeine，Testcontainers，Docker 与 Kubernetes 部署，GitHub Actions CI

## 环境

- JDK：17 及以上
- 构建工具：Maven 或 Gradle
- 版本控制：Git（远端托管在 GitHub）

## 使用方式

```bash
git clone git@github.com:qweasdzxc122/javaDemo.git
cd javaDemo
```

## 说明

本仓库中包含的学习资料若引用第三方开源项目，均会保留其原始许可证（LICENSE）与出处说明。
