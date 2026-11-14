# DeepTutor 使用说明

## 身份确认

用户所说的 GitHub “deepturo”按上下文判断是香港大学 HKUDS 的 DeepTutor。上游仓库为 https://github.com/HKUDS/DeepTutor，许可证为 Apache License 2.0。本次检查到的上游 main 提交为 60fb3bdfddb30b7740c7ce3bd9b28d908f2af6db；README 标注的最新发布为 v1.7.2（以实际发布页为准）。该项目支持知识库、检索增强问答、聊天、练习/测验、学习路径、阅读、研究、记忆和 CLI；它是学习工具，不会自动替代教师、导师或汽车工程安全审查。

## 建议的导入方式

1. 在本仓库下载或克隆 LEARNING-KB/ 与 CMU-AI-PLAN/。
2. 在 DeepTutor 中创建一个名称类似 kevein976-cs-learning-roadmap 的知识库。
3. 导入本目录全部 Markdown，再按需导入 CMU-AI-PLAN/。
4. 每次改动后重新索引，并在问答中要求返回来源文件。
5. 用固定问题验收：请给出本周任务、列出未知信息、指出证据不足的结论。

## CLI 方向

DeepTutor 当前提供 deeptutor kb create、deeptutor kb list、deeptutor kb info 等知识库命令；具体参数以安装版本的 deeptutor --help 为准。上游 README 说明，完整 Web/CLI 安装与核心 CLI 安装是不同配置，使用前先完成模型和嵌入配置。

## 版本与隐私

- 记录 DeepTutor 版本、知识库名称、索引时间和模型配置。
- 不把 API 密钥、车辆识别码、位置轨迹、原始私密对话或未脱敏数据上传到公开仓库。
- Apache-2.0 允许使用和修改，但再分发时要保留许可证和署名要求；第三方资料仍受各自许可约束。
