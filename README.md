# static-code-analyzer

> Roslyn-based Static Code Analyzer for C#

![Language](https://img.shields.io/github/languages/top/J1u2a3n8/static-code-analyzer)
![License](https://img.shields.io/github/license/J1u2a3n8/static-code-analyzer)
![Last Commit](https://img.shields.io/github/last-commit/J1u2a3n8/static-code-analyzer)
![Stars](https://img.shields.io/github/stars/J1u2a3n8/static-code-analyzer?style=social)
![Issues](https://img.shields.io/github/issues/J1u2a3n8/static-code-analyzer)

## Description

A static analysis tool built on the Roslyn compiler platform that detects code smells, calculates complexity metrics, and enforces coding standards. Extensible rule engine with custom analyzers.

## Architecture

Modular: Parser → Syntax Tree Visitor → Rules Engine → Reporter (JSON/HTML/SARIF)

## Quick Start

### Prerequisites

.NET 8 SDK, Visual Studio 2022 / VS Code with C# Dev Kit

### Installation

```bash
# Clone
git clone https://github.com/J1u2a3n8/static-code-analyzer.git
cd static-code-analyzer

dotnet restore
# dotnet build
```

### Usage

```bash
dotnet run --project src/StaticAnalyzer -- --path ./target-project --output report.json
```

## Testing

```bash
dotnet test
```

## Project Structure

```
static-code-analyzer/
├── src/              # Main source code
├── tests/            # Unit/integration tests
├── docs/             # Documentation
├── .github/          # CI/CD workflows
└── README.md
```

## Tech Stack

C#, .NET 8, Roslyn (Microsoft.CodeAnalysis), Newtonsoft.Json

## License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

## Author

**J1u2a3n8** - [GitHub](https://github.com/J1u2a3n8) - [LinkedIn](https://www.linkedin.com/in/juan-luis-canedo-villarroel-189783227/)

---

⭐ If you found this project useful, give it a star!
