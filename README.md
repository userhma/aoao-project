# 示例工作区

这是一个最小化的 VS Code 工作区脚手架，包含 Node 与 Python 示例入口文件、VS Code 配置与推荐扩展列表。

快速开始（PowerShell）：

- 运行 Node 示例：

```powershell
# 安装依赖（如果有）
npm install
# 运行示例
node src\index.js
```

- 运行 Python 示例（推荐使用虚拟环境）：

```powershell
# 可选：创建虚拟环境
python -m venv .venv; .\.venv\Scripts\Activate.ps1
# 安装依赖
pip install -r requirements.txt
# 运行示例
python src\main.py
```

打开工作区：在 VS Code 中打开 `workspace.code-workspace` 文件以加载设置与推荐扩展。
