# --instagram
仿instagram微信小程序

# Avalon Frontend

## 项目简介

Avalon Frontend 是一个基于 Vue.js + UniApp 的微信小程序前端项目，主打自然笔记、内容分享、社交互动等功能。项目采用 FirstUI 组件库，支持海报生成、二维码分享、用户中心、内容浏览等多种场景。

## 页面图例
<img width="410" height="801" alt="3e9bef43adfbc8500399c200cecbdd00" src="https://github.com/user-attachments/assets/fb1a558a-0c02-4f0d-bbce-62fab7709dd5" />
<img width="409" height="799" alt="414858800084a1fcc96e67e6d022d2ac" src="https://github.com/user-attachments/assets/8abd07f0-2f8b-4543-b337-b91d7f3b67d9" />
<img width="411" height="799" alt="11c5630fe08bc330c235d74263d7d989" src="https://github.com/user-attachments/assets/39ed44cf-fd85-47d7-9d45-b92a5061fb93" />
<img width="417" height="801" alt="25413543c62a6589f1495a7169146a0c" src="https://github.com/user-attachments/assets/c2fc4597-9f94-4c04-9587-417c148bb4ad" />
<img width="413" height="802" alt="1a8a8e46a0eae7e8dc1b76d6d9dcd102" src="https://github.com/user-attachments/assets/4b1028b4-0cff-4126-b0b1-fda90e02332e" />
<img width="413" height="802" alt="1a8a8e46a0eae7e8dc1b76d6d9dcd102" src="https://github.com/user-attachments/assets/e362c59f-f628-4ceb-b139-59f3e4e5f235" />
<img width="413" height="802" alt="1a8a8e46a0eae7e8dc1b76d6d9dcd102" src="https://github.com/user-attachments/assets/c136e7ef-5726-47f2-bd07-c48c5ed95e41" />



## 技术栈
- Vue.js 3
- UniApp
- TypeScript
- FirstUI 组件库
- Vite 构建工具

## 主要功能
- 微信小程序适配
- 海报生成与分享（支持二维码、背景图、文本等元素）
- 用户中心与登录
- 内容浏览与发布
- 即梦AI海报设计集成
- 高性能优化（文件监控、语法检查、编辑器配置）

## 目录结构
```
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
├── src/
│   ├── App.vue
│   ├── main.ts
│   ├── pages/
│   │   ├── share/
│   │   │   ├── share.vue
│   │   │   ├── share.ts
│   │   ├── tabbar/
│   │   │   ├── home/
│   │   │   ├   ├── home.vue
│   │   │   │   ├── home.ts
│   │   │   ├── search/
│   │   │   │   ├── search.vue
│   │   │   │   ├── search.ts
│   │   │   ├── user/
│   │   │   │   ├── user.vue
│   │   │   │   ├── user.ts
......
│   ├── components/
│   │   ├── firstui/
│   │   │   ├── fui-poster/
│   │   │   ├── ...
│   ├── service/
│   │   ├── UserService.ts
│   │   ├── ...
│   ├── model/
│   │   ├── UserInfo.ts
│   │   ├── ...
│   ├── utils/
│   │   ├── LoggerUtil.ts
│   │   ├── ...
│   ├── constant/
│   │   ├── Constants.ts
│   │   ├── ...
```

## 快速开始
1. 安装依赖
   ```bash
   npm install
   ```
2. 启动开发环境
   ```bash
   npm run dev
   ```
3. 微信开发者工具导入 dist 目录进行真机调试

## 特色说明
- 海报生成：基于 FirstUI fui-poster 组件，支持自定义背景、二维码、文本等元素，适配 9:16 比例。
- 用户二维码：通过 UserService.getUser().qrcode 动态获取，支持个性化分享。
- 代码架构：业务逻辑采用 base-class TypeScript 类，Vue 页面通过 script src 引入，便于维护和扩展。
- 性能优化：.vscode/settings.json 已配置文件监控和语法检查优化，适合大项目开发。

## 贡献指南
欢迎提交 Issue 和 Pull Request，建议遵循 TypeScript + Vue3 组件化开发规范。

## License
本项目仅授权会员企业内部使用，禁止私自传播和商业化，违者追究法律责任。

