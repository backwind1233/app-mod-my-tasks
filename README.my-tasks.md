# 🚀 Custom App Modernization Tasks

A collection of expert-level tasks for Java application modernization, migration, and optimization.

## 📋 Overview

These custom tasks help you modernize and migrate Java applications using AI-powered assistance. Each task provides structured guidance for common modernization scenarios.

### How to Use Custom Tasks

**To Install:**
- Click the **Install** button for the task you want to use
- The task will be automatically imported into your workspace
- Access tasks through the App Modernization extension panel

**To Use:**
- Open the task from "My Tasks" in the extension panel
- Review the structured prompt and guidance
- Let the AI assistant help you execute the task
- Follow the step-by-step instructions provided

---

## 📚 Available Tasks

| Task | Description |
| ---- | ----------- |
| [Spring Boot 2.x to 3.x Migration](./spring-boot-migration.md)<br />[Install](vscode://vscjava.migrate-java-to-azure/installTask?url=https%3A%2F%2Fraw.githubusercontent.com%2Fbackwind1233%2Fapp-mod-my-tasks%2Fmain%2Fspring-boot-migration.md%26category%3Dmy-tasks) | Comprehensive guide to migrate Spring Boot 2.x applications to Spring Boot 3.x with Java 17+, Jakarta EE namespace changes, and Spring Security 6 updates. |
| [Migrate Java Application to Azure](./azure-migration.md)<br />[Install](vscode://vscjava.migrate-java-to-azure/installTask?url=https%3A%2F%2Fraw.githubusercontent.com%2Fbackwind1233%2Fapp-mod-my-tasks%2Fmain%2Fazure-migration.md%26category%3Dmy-tasks) | End-to-end Azure migration planning including architecture design, service selection, cost optimization, and deployment strategies. |
| [Security Vulnerability Analysis and Remediation](./security-vulnerability-fix.md)<br />[Install](vscode://vscjava.migrate-java-to-azure/installTask?url=https%3A%2F%2Fraw.githubusercontent.com%2Fbackwind1233%2Fapp-mod-my-tasks%2Fmain%2Fsecurity-vulnerability-fix.md%26category%3Dmy-tasks) | Identify and fix security vulnerabilities (CVEs) by analyzing dependencies, assessing impact, and applying recommended patches. |
| [Monolith to Microservices Refactoring](./microservices-refactoring.md)<br />[Install](vscode://vscjava.migrate-java-to-azure/installTask?url=https%3A%2F%2Fraw.githubusercontent.com%2Fbackwind1233%2Fapp-mod-my-tasks%2Fmain%2Fmicroservices-refactoring.md%26category%3Dmy-tasks) | Transform monolithic applications into microservices using domain-driven design, API gateways, and event-driven architecture. |
| [Java Application Performance Optimization](./performance-optimization.md)<br />[Install](vscode://vscjava.migrate-java-to-azure/installTask?url=https%3A%2F%2Fraw.githubusercontent.com%2Fbackwind1233%2Fapp-mod-my-tasks%2Fmain%2Fperformance-optimization.md%26category%3Dmy-tasks) | Analyze and optimize Java application performance through profiling, code optimization, database tuning, and JVM configuration. |

---

## 🎯 Task Categories

### Migration & Upgrade
- Spring Boot version upgrades
- Java version migrations (8 → 11 → 17 → 21)
- Azure cloud migration
- Framework modernization

### Security & Compliance
- CVE remediation
- Dependency updates
- Security best practices
- Vulnerability scanning

### Architecture & Design
- Microservices decomposition
- Cloud-native architecture
- API design and implementation
- Event-driven systems

### Performance & Optimization
- Application profiling
- Database optimization
- JVM tuning
- Caching strategies

---

## 💡 Creating Custom Tasks

Want to create your own tasks? Follow our [task creation guide](../doc/task-uri-handler.md) to:

1. Create task files with YAML frontmatter
2. Structure prompts with clear sections
3. Include examples and best practices
4. Share tasks via GitHub or local files

### Task Template

```markdown
---
id: your-task-id
name: Your Task Name
type: task
---

**Prompt:**

Your task description and instructions here.

## Analysis Phase
[Analysis steps]

## Implementation Steps
[Implementation guidance]

## Key Considerations
[Important points to remember]

## Output Format
[Expected deliverables]
```

---

## 🔧 Installation Methods

### One-Click Installation
Click the **Install** button next to any task in the table above.

### Manual Installation
1. Download the task markdown file
2. Open VS Code Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
3. Run: `Java Migration: Install Custom Task`
4. Select the downloaded file

### From GitHub
Use the URI format:
```
vscode://vscjava.migrate-java-to-azure/installTask?url=<file-url>&category=<category>
```

---

## 📖 Documentation

- [Task Creation Guide](../doc/task-uri-handler.md)
- [URI Handler Documentation](../doc/debug-uri-handler.md)
- [Sample Task Examples](../doc/sample-task.md)

---

## 🤝 Contributing

Have a great modernization task to share? We'd love to include it!

1. Create your task following the template
2. Test it thoroughly
3. Submit a pull request

---

## 📝 License

These tasks are provided under the same license as the Azure Java Migration Copilot extension.

---

## 🆘 Support

Need help? 
- Check the [documentation](../doc/)
- Review [example tasks](../doc/sample-task.md)
- File an issue on GitHub

---

**Happy Modernizing! 🚀**
