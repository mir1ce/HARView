# HAR Viewer

一个基于Vue.js和Wails框架的HTTP Archive (HAR) 文件查看器。

<img width="1546" height="893" alt="image" src="https://github.com/user-attachments/assets/ddf4f04e-fa07-4ef9-ae28-881bfa731bf2" />


## 功能

- 显示HAR文件中的所有HTTP请求
- 查看请求和响应的详细信息
- 显示请求头、响应头、请求体和响应体
- 显示请求时间信息
- 支持查看文本和图片内容
- 直观的状态码显示

## 技术栈

- 前端: Vue.js 3 + Element Plus
- 后端: Go (Wails框架)
- 构建工具: Vite


## 使用说明

1. 应用启动后会自动加载xhr.txt文件中的HAR数据
2. 左侧显示所有HTTP请求列表
3. 点击任一请求可在右侧查看详细信息
4. 使用顶部标签页切换查看不同部分的信息:
   - Request Headers: 请求头信息
   - Response Headers: 响应头信息
   - Request Body: 请求体内容
   - Response Body: 响应体内容
   - Timing: 请求时间信息

## 特性

- 自动识别并格式化显示文本内容 (HTML, CSS, JS, JSON等)
- 根据HTTP状态码显示不同颜色标识
- 响应时间信息的详细展示
- 现代化的UI界面，基于Element Plus组件库
- 响应式设计，支持不同屏幕尺寸
- 搜索功能，快速过滤请求
- 支持加载自定义HAR文件
