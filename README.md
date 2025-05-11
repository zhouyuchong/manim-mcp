# MCP Manim Server

A server-based tool that leverages Manim to generate mathematical animations from text prompts.

## Working Video:

[Working Video](https://github.com/user-attachments/assets/7130709f-b0bd-48d8-b27d-e01536807036)

## Description

MCP Manim Server provides an interface to:
- Execute Manim code snippets programmatically
- Generate Manim code from natural language prompts
- Manage animation media files

## Installation

1. Clone this repository
```bash
git clone https://github.com/Avik-creator/MCP.git
cd MCP
```

2. Install dependencies
```bash
uv pip install
```

3. Set up Manim
The server uses Manim to render animations. Ensure Manim is installed:
```bash
pip install manim
```

## Environment Variables

- `MANIM_EXECUTABLE`: Path to the Manim executable (defaults to "manim")

## Usage

Run the server:
```bash
uv run main.py
```

### Features

#### Execute Manim Code
The server can run Manim code and return the path to the generated animation file.

#### Generate Manim Code from Prompts
The server can generate Manim code based on natural language prompts.

#### Clean Media Directory
Clean up generated media files when no longer needed.

## Project Structure

- `main.py`: Primary server implementation
- `media/`: Directory where generated animations are stored

## License

[MIT License](LICENSE)
