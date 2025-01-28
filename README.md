# Global .gitignore

A comprehensive global .gitignore configuration for Python/Django development environments. For more details about .gitignore patterns, visit the [official documentation](https://git-scm.com/docs/gitignore).

## Quick Setup

1. Create config directory and copy the file:

```bash
mkdir -p ~/.config
cp .gitignore ~/.config/
```

2. Configure git to use this global ignore file:

```bash
git config --global core.excludesfile ~/.config/.gitignore
```

## What's Included

Ignores common files and directories for:

- 🐍 Python (bytecode, packages, build files)
- 🎯 Django specific files
- 🧪 Testing and coverage reports
- 💻 IDEs and editors (VSCode, JetBrains)
- 🔧 Development environments
- 🌐 Virtual environments
- 🔒 Environment variables
- 💾 System files (macOS, etc.)

## Usage

Once configured, this will work as your global .gitignore across all your repositories. You can still maintain project-specific `.gitignore` files in individual repositories for additional patterns.

## License

MIT

