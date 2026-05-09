---
name: devcontainer-cli
description: Guidance for using the official @devcontainers/cli tool. Use this skill when you need to build, start, or run commands inside a development container defined by a devcontainer.json configuration.
---

# devcontainer-cli

This skill provides procedural guidance for managing development environments using the official Dev Container CLI (`devcontainer`).

## Core Commands

### 1. Build Image
Build the container image defined in `devcontainer.json`.
```bash
devcontainer build --workspace-folder <path>
```

### 2. Start Container
Create and start the dev container.
```bash
devcontainer up --workspace-folder <path>
```
*Note: Use `--remove-existing-container` if you need to recreate a stale container.*

### 3. Execute Command
Run a command inside a running dev container.
```bash
devcontainer exec --workspace-folder <path> <command>
```

### 4. Read Configuration
Parse and validate the `devcontainer.json` file.
```bash
devcontainer read-configuration --workspace-folder <path>
```

## Essential Flags

- `--workspace-folder <path>`: (Required) Path to the root of the project containing `.devcontainer/`.
- `--config <path>`: Path to a specific `devcontainer.json` if not in the default location.
- `--id-label <key>=<value>`: Add labels to the container for easier identification.
- `--remove-existing-container`: Force recreation of the container.

## Common Workflows

### Setup and Verify
1. Validate config: `devcontainer read-configuration --workspace-folder .`
2. Build image: `devcontainer build --workspace-folder .`
3. Start container: `devcontainer up --workspace-folder .`

### Run Tests in Container
```bash
devcontainer exec --workspace-folder . npm test
```

## Troubleshooting

- **Docker not running**: Ensure the Docker daemon is active and accessible. Check `docker info`.
- **Config errors**: Use `read-configuration` to identify syntax or schema issues in `devcontainer.json`.
- **Container failure**: Check logs using `docker logs <container_id>`. Use `--remove-existing-container` to reset.
- **Permission issues**: Ensure the current user has permission to interact with the Docker socket.
