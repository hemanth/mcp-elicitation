# MCP Elicitation Demo

A simple demo of FastMCP's elicitation feature for interactive user input during tool execution.

## Quick Start

1. **Install dependencies**:
   ```bash
   pip install fastmcp
   ```

2. **Run the server**:
   ```bash
   python server.py
   ```

3. **Run the client** (in another terminal):
   ```bash
   python client.py
   ```

## What it does

- **Server**: Provides a `book_doctor_appointment` tool that collects user info step-by-step
- **Client**: Interactive appointment booking with smart input validation and retry logic

The client handles input validation on the client side and only re-prompts for invalid inputs, not the entire flow.