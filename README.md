# Nova Solve by Nova OS

[![PyPI](https://img.shields.io/pypi/v/novasolve.svg)](https://pypi.org/project/novasolve/)
[![Python](https://img.shields.io/pypi/pyversions/novasolve.svg)](https://pypi.org/project/novasolve/)
[![License](https://img.shields.io/badge/license-Proprietary-red.svg)](NOTICE.md)

AI-powered test fixing for Python projects. Fix failing PyTest tests automatically with a single command.

![Nova Solve Demo](https://user-images.githubusercontent.com/demo.gif)

## 🚀 Quick Start

```bash
# Install Nova Solve
pip install novasolve

# Fix failing tests in your project
nova solve .

# Watch as your tests turn green! ✅
```

## 🎯 Features

- **Automatic Test Fixing**: Analyzes failing tests and generates patches
- **Smart Context Gathering**: Understands your codebase to make accurate fixes
- **Git Integration**: Creates clean branches for each fix
- **Safety First**: Never modifies your main branch directly
- **Fast**: Fixes most tests in under 15 minutes

## 📦 Installation

### Requirements
- Python 3.10 or higher
- Git
- OpenAI API key

### Install from PyPI
```bash
pip install novasolve
```

### Set up your API key
```bash
# On first run, Nova will prompt for your OpenAI API key
nova solve .

# Or set it via environment variable
export OPENAI_API_KEY="your-api-key"
```

## 🔧 Usage

### Basic Usage
```bash
# Fix all failing tests in current directory
nova solve .

# Fix tests in a specific directory
nova solve path/to/project

# Use a different AI model
nova solve . --model gpt-4

# Dry run (see what would be fixed without applying changes)
nova solve . --dry-run
```

### Example Output
```
🔍 Discovering failing tests...
Found 3 failing tests

📝 Fixing test_calculator.py::test_addition
✅ Fixed! Created branch: nova/fix-a1b2c3d

📝 Fixing test_string_utils.py::test_parse
✅ Fixed! Created branch: nova/fix-e4f5g6h

📝 Fixing test_processor.py::test_validation
✅ Fixed! Created branch: nova/fix-i7j8k9l

🎉 All tests fixed! Review the branches and merge when ready.
```

## 💰 Pricing

Nova Solve is available under a commercial license.

### Founding-50 Plan
- **$399/month** (Limited time offer)
- Unlimited test fixes
- Priority support
- Early access to new features

[**Get Access →**](https://novasolve.ai/pricing)

## 📚 Documentation

- [Getting Started Guide](https://docs.novasolve.ai/getting-started)
- [Configuration Options](https://docs.novasolve.ai/configuration)
- [API Reference](https://docs.novasolve.ai/api)
- [Troubleshooting](https://docs.novasolve.ai/troubleshooting)

## 🔐 Source Code Access

Nova Solve is source-available to licensed customers. 

**To access the source code:**
1. [Purchase a license](https://novasolve.ai/pricing)
2. You'll receive an invitation to the private repository
3. Clone and customize as needed

See [NOTICE.md](NOTICE.md) for more details.

## 🤝 Support

- **Email**: support@novasolve.ai
- **GitHub Issues**: For licensed customers with source access
- **Documentation**: https://docs.novasolve.ai

## 🏢 About Nova OS

Nova Solve is built by [Nova OS](https://novaos.ai), a company focused on AI-powered developer tools. We're on a mission to make software development faster and more reliable.

## 📄 License

Nova Solve is proprietary software. See [NOTICE.md](NOTICE.md) for licensing details.

---

*Made with ❤️ by Nova OS in San Francisco* 