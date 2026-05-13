# 基于python实现的批量删除文本
项目启动：
```
# 设置全局默认版本（推荐 3.11.9）
pyenv global 3.11.9

# 1. 创建虚拟环境
python -m venv venv

# 2. 激活环境 (Windows)
source venv/bin/activate

# 3. 安装 PyMuPDF
pip install PyMuPDF

# 执行代码
python ./src/main.py
```


**工作流程：**

1.  **创建虚拟环境**：在项目目录下执行 `python -m venv .venv`。
2.  **激活虚拟环境**：
    -   **Linux/macOS**：`source .venv/bin/activate`
    -   **Windows**：`.venv\Scripts\activate`
3.  **安装依赖**：激活环境后，使用 `pip install <package_name>` 安装包。
4.  **导出依赖列表**：使用 `pip freeze > requirements.txt` 将当前环境中所有包及其精确版本导出到 `requirements.txt` 文件。