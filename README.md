# WindSurf Configuration

WindSurf is a powerful agentic AI coding assistant designed by the Windsurf engineering team. This repository contains configuration rules and settings that customize the behavior of the WindSurf AI assistant.

## 🚀 Features

- Custom rules and configurations for WindSurf AI
- Multi-language support (Go, Python)
- Django project templates and best practices
- Modern UI/UX guidelines with dark theme
- HTMX integration patterns

## 📦 Prerequisites

- A working installation of WindSurf AI
- Basic understanding of YAML configuration files
- For Python/Django projects:
  - Python 3.10+
  - Django
  - pip (Python package manager)
- For Go projects:
  - Go 1.18+

## 🛠️ Installation

1. Place the `.windsurfrc` file in your home directory:
   ```bash
   # Create the config directory if it doesn't exist
   mkdir -p ~/.config/windsurf/
   
   # Copy the configuration file
   cp rules/go/.windsurfrc ~/.config/windsurf/config.yaml
   ```

2. Reload WindSurf to apply the new rules:
   - If using the IDE integration, restart your IDE
   - If using the CLI, restart your terminal session
   - Some configurations may require a full system restart to take effect

## 🏃‍♂️ Usage

After installation, WindSurf will automatically use the configuration from `~/.config/windsurf/config.yaml`. You can modify this file to customize WindSurf's behavior according to your preferences.

To verify your configuration is being loaded, you can check the WindSurf logs for any configuration-related messages.

## 🔧 Configuration

### Python/Django Configuration
For Python and Django development, we provide comprehensive rules and best practices in [rules/python/.windsurfrules](rules/python/.windsurfrules) that include:

- **Project Setup**:
  - Python 3.10+ with virtual environment support
  - Django project structure and best practices
  - Security middleware and CSRF protection

- **Development Tools**:
  - Code formatting with Black (88 char line length)
  - Linting with Flake8
  - HTMX integration (preferred over JavaScript)

- **UI/UX Standards**:
  - Dark theme with gradient backgrounds
  - Modern CSS with rounded corners
  - Minimal JavaScript usage

### Go Configuration
For Go development rules and configuration, refer to [rules/go/.windsurfrc](rules/go/.windsurfrc).

### Global Configuration
The main configuration file is located at `~/.config/windsurf/config.yaml` and controls WindSurf's behavior including:
- Code style preferences
- Language-specific rules
- Custom commands and shortcuts
- Integration settings

## 🤝 Contributing

Contributions to improve WindSurf's configuration are welcome! To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request with a clear description of your changes

Please ensure your changes follow the existing code style and include appropriate documentation.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📫 Contact

Anthony Hopkins - anthony.b.hopkins@gmail.com

Project Link: [https://github.com/anthony-hopkins/](https://github.com/anthony-hopkins/windsurf_rules)
