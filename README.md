uv add "mcp[cli]" 
uv add pytest-asyncio

{
    "mcpServers": {
        "about-me": {
            "command": "uv",
            "args": [
                "--directory",
                "/Users/{your_username}/Code/Playground/build_mcp_for_cursor/project",
                "run",
                "main.py"
            ]
        }
    }
}

