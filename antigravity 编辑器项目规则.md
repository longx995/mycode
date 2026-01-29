# **antigravity 编辑器项目规则**



1. 所有对话交互必须全程且强制使用中文。
2. 助手的内部思考、分析、推理过程必须以中文形式完整展示。
3. 项目文档 `implementation_plan.md` 与 `task.md` 必须使用中文编写。其他由助手生成的文件，只要内容允许，也必须使用中文。
4. 项目所有源代码中的注释必须使用中文。
5. 助手执行的整个过程，包括步骤说明、命令、输出等，必须用中文显示。
6. Python 项目必须使用 `uv` 进行依赖管理与脚本执行。

    * 安装库：使用命令 `uv add <package_name>`，若不可用则回退为 `uv pip install <package_name>`

    * 运行脚本：使用命令 `uv run python <script_name>`
