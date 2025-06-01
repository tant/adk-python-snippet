# Google ADK Agent Snippet

A Visual Studio Code extension providing a comprehensive Python boilerplate for ADK AI Agents.  
Quickly scaffold agent code with best practices, multi-agent setup, tool definitions, callbacks, and state management using the `adkagent` snippet.

## Features

- Insert a full-featured ADK agent Python template with the `adkagent` snippet.
- Includes imports, LLM configuration, tool definitions (stateless/stateful), callbacks (guardrails), multi-agent setup (sub-agents & root agent), and state management.
- Designed for rapid prototyping and production-ready agent code.

## Requirements

- [VS Code](https://code.visualstudio.com/)
- [google-adk](https://pypi.org/project/google-adk/) Python package:  
  ```
  pip install google-adk
  ```
- (Optional) [litellm](https://pypi.org/project/litellm/) for multi-model support:  
  ```
  pip install litellm
  ```

## Usage

1. Open a Python file in VS Code.
2. Type `adkagent` and press `Tab` or `Enter` to insert the agent template.
3. Customize the generated code as needed for your project.

## Known Issues

- No known issues at this time.  
  Please [open an issue](https://github.com/your-repo/issues) if you encounter any problems.

## Release Notes

### 1.0.0

- Initial release: ADK agent boilerplate snippet for Python.

## License

This project is licensed under the [MIT License](LICENSE).

**Enjoy building with ADK!**
