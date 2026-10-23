# MCP client

Add `OPENAI_API_KEY` as a **Codespaces** secret for this repository. Replace the
placeholder `MCP_SERVER_URL` in `app.py` with the server's public HTTPS URL
ending `/mcp`, or set that environment variable. Create a Codespace and open
port 7860, keeping it private. Startup is automatic.

Ask `Microsoft on 2025-09-19`. OpenAI discovers and calls the remote MCP tools;
Gradio displays the response and an expandable tool trace. The server must be
running with public port 8000. No service registry is used.

