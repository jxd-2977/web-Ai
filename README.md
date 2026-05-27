# Vue 2.6.14 项目

这是一个基于 Vue 2.6.14 的前端项目脚手架。

## 技术栈

- **Vue**: 2.6.14
- **Element UI**: 2.15.14 - UI组件库
- **Less**: 4.x - CSS预处理器
- **Axios**: 1.x - HTTP客户端
- **ESLint**: 代码检查工具
- **Prettier**: 代码格式化工具

## 项目设置

```bash
npm install
```

### 开发环境运行

```bash
npm run serve
```

### 生产环境构建

```bash
npm run build
```

### 代码检查和修复

```bash
npm run lint
```

## 项目结构

```
my-vue-app/
├── public/              # 静态资源
├── src/                 # 源代码
│   ├── assets/          # 资源文件
│   ├── components/      # 组件
│   ├── App.vue          # 根组件
│   └── main.js          # 入口文件
├── babel.config.js      # Babel配置
├── vue.config.js        # Vue CLI配置
└── package.json         # 项目配置

```

## 主要依赖说明

- **vue@2.6.14**: Vue核心库
- **element-ui@2.15.14**: Element UI组件库
- **axios@1.16.1**: HTTP请求库
- **less@4.6.4**: Less预处理器
- **less-loader@7.3.0**: Webpack的Less加载器

## 开发工具

- **eslint@10.4.0**: JavaScript代码检查
- **prettier@3.8.3**: 代码格式化
