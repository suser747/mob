# GLXT 项目

前后端分离项目，包含 Vue 3 前端和 Spring Boot 后端。

## 项目结构

```
glxt/
├── demo/          # Spring Boot 后端
└── web/           # Vue 3 前端
```

## 技术栈

### 后端 (demo/)
- Spring Boot 3.5.15
- Java 17
- Spring Data JPA
- MySQL
- Lombok

### 前端 (web/)
- Vue 3.5.34
- Vite 8.0.12
- @vitejs/plugin-vue

## 运行

### 后端
```bash
cd demo
./mvnw spring-boot:run
```

### 前端
```bash
cd web
npm install
npm run dev
```
