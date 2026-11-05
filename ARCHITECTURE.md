# StudyOS 技术架构

- React + TypeScript + Vite
- GitHub 仓库管理代码；GitHub Pages 部署静态前端
- V1 后续使用 IndexedDB 保存数据，JSON 导出导入备份
- AI 分析通过手动复制材料到 ChatGPT、再导入结构化结果，不内置 API 密钥

数据对象（后续实现）：Subject、Topic、MasteryHistory、Task、Log、Evidence、Diagnosis、Settings。每条记录含稳定 ID、创建时间和修改时间。

当前迭代使用 React 内存状态演示交互；刷新页面将丢失演示数据。
