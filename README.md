# Spring Security Demo Project

这是一个使用 Spring Security 的示例项目，展示了基本的 Web 安全认证功能。

## 技术栈

- Java 17
- Spring Boot 3.2.1
- Spring Security 6.2.1
- Thymeleaf
- Maven

## 功能特性

- 基本的登录/登出功能
- 安全认证和授权
- 使用 Thymeleaf 模板引擎
- 响应式页面设计

## 快速开始

### 前置条件

- JDK 17 或更高版本
- Maven 3.8+ (或使用项目内置的 Maven Wrapper)

### 运行项目

1. 克隆项目
```bash
git clone https://github.com/niaomingjian/cursor-http-security.git
cd cursor-http-security
```

2. 构建并运行
```bash
mvn spring-boot:run
```

3. 访问应用
- 打开浏览器访问: http://localhost:8080
- 使用以下凭证登录:
  - 用户名: user
  - 密码: 在应用启动时会在控制台打印，格式如下：
    ```
    Using generated security password: xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
    ```

## 项目结构

```
src/
├── main/
│   ├── java/
│   │   └── example/
│   │       ├── HelloSecurityApplication.java    # 应用入口
│   │       └── IndexController.java             # 主页控制器
│   └── resources/
│       └── templates/
│           └── index.html                       # 主页模板
└── test/
    └── java/
        └── example/
            └── HelloSecurityApplicationTests.java
```

## 开发指南

1. 本项目使用 Maven 进行依赖管理和构建
2. 主要配置文件：
   - `pom.xml`: Maven 项目配置
   - `application.properties`: Spring Boot 配置（如需添加）

## 注意事项

- 这是一个演示项目，使用了默认的安全配置
- 在生产环境中，请确保：
  - 修改默认的安全配置
  - 使用适当的密码加密方式
  - 添加必要的安全控制

## 贡献指南

欢迎提交 Issue 和 Pull Request 来改进这个项目。

## 许可证

本项目采用 MIT 许可证。 