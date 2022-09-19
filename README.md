# Azure CosmosDB Emulator

Template repository of devcontainer using [Azure Cosmos DB Emulator](https://learn.microsoft.com/en-us/azure/cosmos-db/linux-emulator).

## Summary

| Metadata | Value |  
|----------|-------|
| *Contributors* | [Yuta Matsumura](https://github.com/tsubakimoto) |
| *Categories* | Services, Azure |
| *Definition type* | Docker Compose |
| *Published image architecture(s)* | x86-64 |
| *Available image variants* | 3.1-focal, 6.0-focal |
| *Works in Codespaces* | Yes |
| *Container host OS support* | Linux, macOS |
| *Container OS* | Ubuntu (`-focal`) |
| *Languages, platforms* | .NET, .NET Core, C#, Microsoft Azure |

## Using this definition

**[Optional] Include any special setup requirements here. For example:**

While the definition itself works unmodified, you can select the version of **YOUR RUNTIME HERE** the container uses by updating the `VARIANT` arg in the included `.devcontainer/devcontainer.json` file.

```json
"args": { "VARIANT": "buster" }
```

### Adding the definition to a project or codespace

1. If this is your first time using a development container, please see getting started information on [setting up](https://aka.ms/vscode-remote/containers/getting-started) Remote-Containers or [creating a codespace](https://aka.ms/ghcs-open-codespace) using GitHub Codespaces.

2. Start VS Code and open your project folder or connect to a codespace.

3. Press <kbd>F1</kbd> select and **Add Development Container Configuration Files...** command for **Remote-Containers** or **Codespaces**.

   > **Note:** If needed, you can drag-and-drop the `.devcontainer` folder from this sub-folder in a locally cloned copy of this repository into the VS Code file explorer instead of using the command.

4. Select this definition. You may also need to select **Show All Definitions...** for it to appear.

5. Finally, press <kbd>F1</kbd> and run **Remote-Containers: Reopen Folder in Container** or **Codespaces: Rebuild Container** to start using the definition.
