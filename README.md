# 🚀 Setup Instructions for Leave Management Server

## 📦 Prerequisites
- Ensure **Claude Desktop** is installed.
- Python and `pip` should be available in your system environment.

## 🧪 Installation & Project Setup

1. **Install `uv` package manager:**
```
pip install uv
```
Initialize a new MCP project:

```
uv init my-first-mcp-server
```
2. Add mcp CLI to your project:

```
uv add "mcp[cli]"
```

3.  upgrade the typer library:


```
pip install --upgrade typer
```

4. Write your leave management server logic:

    Implement your logic in the main.py file inside your project directory.

5. Install the server into Claude Desktop:


```
uv run mcp install main.py
```

6. 🔄 Restart Claude Desktop
Kill any existing Claude instance using Task Manager.

7. Restart Claude Desktop to apply the changes.