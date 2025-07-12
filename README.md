💼 MCP-Powered Financial Agent<br>
This project is a Multi-Agent Financial Analyst system built using CrewAI, powered by GPT-4.1 and integrated via MCP (Model Context Protocol). The agent performs financial analysis, assists with investment insights, and runs locally with MCP integration in the Cursor environment.

🚀 Features<br>
🔗 Multi-Agent Structure: Built using CrewAI to manage complex task delegation.
🤖 GPT-4.1: Utilizes powerful reasoning and analysis from OpenAI’s GPT-4.1 model.
🧠 MCP Integration: Easily connect your agent to other tools and models via the Model Context Protocol.
💻 Cursor Compatible: Ready to run inside Cursor with custom mcp.json configuration.

mcp.json Configuration in cursor :

{<br>
  "mcpServers": {<br>
    "financial-analyst": {<br>
      "command": "uv",<br>
      "args":[<br>
        "--directory",<br>
        "/Users/pulkitrajput/Desktop/MCP_Financial_Analyst",<br>
        "run",<br>
        "server.py" <br>
&nbsp;&nbsp;&nbsp;      ]
&nbsp;&nbsp;    }
&nbsp;  }
}
