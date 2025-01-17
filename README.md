# 🤖 PyGUI LLM Prompts Manager

A modern, desktop GUI application for managing and optimizing your LLM prompts across different AI models and providers.

![Python Version](https://img.shields.io/badge/python-3.11%2B-blue)
![PyQt Version](https://img.shields.io/badge/PyQt-6.4.0%2B-green)
![License](https://img.shields.io/badge/license-MIT-orange)

## 🌟 Features

- 📝 Create, edit, and manage prompts for different LLM models
- 🔍 Smart search and organization with tags
- ⚡ Automatic prompt optimization based on model best practices
- 📊 Track prompt history and versions
- 🎯 Quick copy-paste functionality for easy use
- 🌈 Modern, intuitive user interface

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/tblakex01/pygui-llm-prompts.git

# Navigate to directory
cd pygui-llm-prompts

# Install dependencies
pip install -r requirements.txt

# Run the application
python src/main.py
```

## 💻 System Requirements

- Windows 10 or later
- Python 3.11+
- 4GB RAM
- 100MB disk space

## 📋 Project Implementation Checklist

### 🎯 Core Features

#### Database & Data Model
- [ ] Implement base SQLite database setup
- [ ] Create Provider data model and CRUD operations
- [ ] Create Model data model and CRUD operations
- [ ] Create Prompt data model and CRUD operations
- [ ] Implement database indexing
- [ ] Add database migration system

#### User Interface
- [ ] Design and implement main window layout
- [ ] Create Provider/Model tree view
- [ ] Develop prompt list view with sorting/filtering
- [ ] Build prompt editor component
- [ ] Add tag management interface
- [ ] Implement favorites system
- [ ] Create search functionality

#### Prompt Optimization System
- [ ] Implement base PromptOptimizer class
- [ ] Create Anthropic-specific optimizer
- [ ] Create OpenAI-specific optimizer
- [ ] Build optimization review dialog
- [ ] Implement best practices fetching system
- [ ] Add optimization history tracking
- [ ] Create optimization suggestions system

### 🔄 Future Enhancements

- [ ] Rich text formatting in prompt editor
- [ ] Prompt templates with variables
- [ ] Import/Export functionality
- [ ] Cloud sync capabilities
- [ ] Version history system
- [ ] Advanced tag management
- [ ] Prompt testing integration
- [ ] Multi-language support
- [ ] Dark mode support

## 🏗️ Project Structure

```
llm_prompt_manager/
├── src/
│   ├── database/
│   ├── ui/
│   ├── optimization/
│   └── utils/
├── tests/
├── docs/
└── resources/
```

## 🛠️ Technology Stack

- **GUI Framework**: PyQt6
- **Database**: SQLite3
- **Python Version**: 3.11+
- **Additional Libraries**:
  - `dataclasses`
  - `typing`
  - `pytest`
  - `black`
  - `requests`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to Anthropic and OpenAI for their comprehensive documentation
- PyQt community for the excellent GUI framework
- All contributors who help improve this project

---
⭐ Found this project helpful? Please consider giving it a star!