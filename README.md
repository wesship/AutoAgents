> [!NOTE]
> This project is a fork of [Link-AGI/AutoAgents](https://github.com/Link-AGI/AutoAgents). The original project and its contributors can be found there.

# AutoAgents: A Framework for Automatic Agent Generation

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CI/CD Status](https://github.com/wesship/AutoAgents/actions/workflows/ci.yml/badge.svg)](https://github.com/wesship/AutoAgents/actions/workflows/ci.yml)

> [IJCAI 2024] Generate different roles for GPTs to form a collaborative entity for complex tasks. This program, driven by LLM, autonomously generates multi-agents to achieve whatever goal you set.

---

## ✨ Features

- **Automatic Agent Generation**: Autonomously generates multi-agents for complex tasks.
- **Planner**: Determines expert roles and execution plans.
- **Observers**: Reflects on the reasonableness of the planner and execution results.
- **AgentBank**: Allows you to add custom agents.

---

## 🚀 Getting Started

### Prerequisites

- An OpenAI API Key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wesship/AutoAgents.git
   cd AutoAgents
   ```
2. Install the package:
   ```bash
   python setup.py install
   ```
3. Configure your API key in `config/key.yaml`.

### Usage

```bash
python main.py --mode commandline --llm_api_key YOUR_OPENAI_API_KEY --serpapi_key YOUR_SERPAPI_KEY --idea "Is LK-99 really a room temperature superconducting material?"
```

---

## 🛠️ Built With

- [Python](https://www.python.org/)

---

## 🤝 Contributing

Contributions are welcome! Please see the [contributing guidelines](CONTRIBUTING.md) for more information.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
