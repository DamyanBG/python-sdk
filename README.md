# Modular MCP (Model Context Protocol SDK)

This is a **fork** of the [Model Context Protocol Python SDK](https://github.com/modelcontextprotocol/python-sdk), maintained by **Damyan Dimitrov** ([GitHub](https://github.com/DamyanBG)).

## ✨ Purpose

The goal of this fork is to provide a **more modular design** for the MCP Python SDK. It introduces a `Bundler` class, which serves a similar purpose to FastAPI’s `APIRouter`, allowing for:

- Cleaner and more scalable code organization
- Easier composition of multiple MCP endpoints
- Better separation of concerns across modules

## 📦 Installation

This package will be published on PyPI as:

```bash
pip install modular-mcp
```

## 🚀 Running the Server

This SDK is designed to be run using [`uv`](https://github.com/astral-sh/uv):

```bash
uv venv
uv pip install -e .[cli]
uv run mcp
```

## 📚 More Information

For details on the original design, ideas, and broader MCP ecosystem, refer to the original project:

👉 [Original Model Context Protocol Python SDK](https://github.com/modelcontextprotocol/python-sdk)

## 📝 License

MIT – same as the original project.