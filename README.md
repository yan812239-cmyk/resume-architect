🎓 资深校招技术简历架构师 (Professional Resume Architect Agent)
这是一个专为在校生设计的单文件、零后端 AI 简历优化工具。它不仅是一个对话框，更是一个集成了行业关键词检索与 ATS 模拟打分的 L3 智能体。

🚀 核心亮点
多模型无缝切换：支持阿里通义千问 (Qwen2.5-Max)、DeepSeek、OpenAI 及 Google Gemini 官方 API 协议。

工业级 STAR 重构：内置深度 Prompt 逻辑，能够自动识别技术细节（如 MATLAB 仿真、18-bit ADC 建模、A 股 ETF 量化策略等），并将其转化为量化指标。

隐私安全：纯前端实现，API Key 与简历数据仅保存在本地浏览器内存，不经过任何第三方服务器。

智能工作流：

search_industry_keywords: 自动检索岗位最新硬核技能要求。

simulate_ats_scoring: 模拟大厂 ATS 筛选系统进行客观评分。

🛠️ 使用指南
部署：本仓库已配置 GitHub Pages，直接访问即可使用。

配置 API：

输入对应平台的 API Key。

若遇到跨域 (CORS) 限制，请点击 ⚙️ 设置 按钮，填入支持跨域的 API 代理地址。

上传简历：点击 📎 上传 PDF 或直接粘贴文本。

架构重写：点击 ✦ 启动架构师分析，Agent 将执行从诊断到 STAR 重写的完整流程。

💡 优化示例 (以通信工程为例)
原始描述：参加了 ADC 课设，负责写代码，最后通过了测试。

Agent 重写后：【基于 MATLAB 的 18-bit SAR ADC 性能计算系统】。自主研发信号类型智能识别算法，实现 DNL/INL 曲线自动拟合，将计算精度偏差控制在 0.01LSB 以内。

⚖️ 开源协议
本项目采用 MIT License，欢迎自由修改与分发。
