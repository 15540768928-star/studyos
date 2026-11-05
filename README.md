# StudyOS

个人 2027 高考学习工作台。当前为 **V1 第一轮静态交互原型**。

## 本地运行

需要 Node.js 20.19+ 或 22.12+。

```bash
npm install
npm run dev
```

构建检查：`npm run build`。

## 功能

- 首页总览（示例任务、倒计时）
- 六科学习地图（演示状态切换）
- 学习日志（仅当前页面会话）
- AI 诊断（规则演示，不调用 API）
- 深浅主题与响应式布局

**注意：当前所有用户输入只保留在页面内存中，刷新后会丢失。请勿将其当作正式学习记录工具。** IndexedDB、JSON 备份与真实诊断属于后续开发阶段。

## 部署

仓库名为 `studyos` 时，Vite `base` 为 `/studyos/`。可通过 GitHub Actions 构建 `dist` 并部署 GitHub Pages。部署前不要把私人学习数据、密钥或 `.env` 提交到仓库。
