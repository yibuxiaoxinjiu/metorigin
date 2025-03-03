# metorigin

`NextChat`（原 `ChatGPT Next Web`）是一个轻量级且快速的 AI 助手项目，支持 Claude、DeepSeek、GPT4 及 Gemini Pro 等。以下是关于这个仓库的详细介绍：

### 项目基本信息
- **项目名称**：NextChat (ChatGPT Next Web)

- **部署方式**：
    - 可一键免费部署在 Vercel 上，1 分钟内即可完成。
    - 提供 Zeabur、Gitpod 等多种部署选项。

### 项目亮点
1. **客户端小巧**：在 Linux/Windows/MacOS 上的客户端体积约为 5MB，可通过[此链接](https://github.com/Yidadaa/ChatGPT-Next-Web/releases)下载。
2. **兼容性强**：完全兼容自部署的大语言模型（LLMs），推荐与 [RWKV-Runner](https://github.com/josStorer/RWKV-Runner) 或 [LocalAI](https://github.com/go-skynet/LocalAI) 搭配使用。
3. **注重隐私**：所有数据都本地存储在浏览器中。
4. **支持 Markdown**：支持 LaTex、mermaid、代码高亮等 Markdown 特性。

### 企业版功能
满足公司私有化和定制化部署需求，包括：
- **品牌定制**：定制 VI/UI 以与公司品牌形象无缝对接。
- **资源整合**：公司管理员可统一配置和管理数十种 AI 资源，供团队成员使用。
- **权限控制**：明确的成员权限、资源权限和知识库权限，通过企业级管理面板进行控制。
- **知识集成**：将内部知识库与 AI 能力相结合，更贴合公司特定业务需求。
- **安全审计**：自动拦截敏感查询，追溯所有历史对话记录，确保 AI 符合公司信息安全标准。
- **私有部署**：支持各种主流私有云解决方案的企业级私有部署，保障数据安全和隐私保护。
- **持续更新**：在多模态 AI 等前沿能力上持续更新和升级。

### 项目结构
项目根目录下包含各种配置文件（如 `.babelrc`、`.eslintrc.json` 等）、文档（如 `README.md` 等）以及多个子文件夹，如：
- `docs`：存放项目相关文档，包含不同语言版本的部署指南等。
- `.github`：可能包含 GitHub 相关的配置和工作流文件。
- `scripts`：存放脚本文件。
- `public`：存放公共资源文件。
- `src-tauri`：可能与桌面应用开发相关。
- `.husky`：用于配置 Git hooks。
- `test`：存放测试相关文件。
- `app`：存放应用的主要代码。
