# Know Your Gemini ♊️

**Know Your Gemini** is a comprehensive developer resource dedicated to mastering the **Gemini CLI** and its agentic ecosystem. This repository serves as a blueprint for configuring, extending, and optimizing Gemini as a terminal-native AI agent.

In modern development, the CLI has evolved beyond simple chat. It is now an autonomous partner capable of multi-file reasoning, structured planning, and tool execution. This repo helps you harness that power to make your development workflow faster and more consistent.

---

## 🌟 Key Features

* **Skill Manifests:** Learn how to use `.md` files to define project-specific "Skills" that teach Gemini your coding standards, architectural patterns, and preferred libraries.
* **Workflow Automation:** Step-by-step guides on using **Plan Mode** for complex refactors and **Checkpointing** for long-running sessions.
* **Context Engineering:** Techniques for optimizing the 1M+ token context window to handle entire repositories without losing focus.
* **Tool Integration:** Documentation on connecting Gemini to local and cloud-based tools using the **Model Context Protocol (MCP)**.

---

## 🛠 Project Structure

- `/skills`: A collection of reusable markdown templates for different tech stacks (React, .NET, SQL).
- `/configs`: Sample configuration files for custom CLI aliases and environment setups.
- `/mcp-guides`: Tutorials on connecting external data sources like GitHub, Jira, and local databases.
- `/best-practices`: Deep dives into agentic prompting and structured output.

---

## 🚀 Quick Start

1.  **Clone the Repo:**
    ```bash
    git clone https://github.com/your-username/know-your-gemini.git
    ```
2.  **Explore Skills:** Browse the `/skills` folder to find a manifest that matches your current stack.
3.  **Apply to Your Project:** Drop a `GEMINI.md` or `SKILL.md` file into your project root to instantly upgrade the CLI's understanding of your codebase.

---

## 🤝 Contributing

We welcome contributions! Whether it's a new skill template, an MCP setup guide, or a workflow optimization, feel free to open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.
