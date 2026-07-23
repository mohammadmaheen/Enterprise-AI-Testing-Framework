# Enterprise AI Testing Framework

## Overview

This project demonstrates AI application testing using Promptfoo and Llama 3.2 running locally with Ollama.

The framework validates an enterprise AI assistant through multiple testing categories including functional, conversational, workflow, and LLM security testing.

---

## Features

- Functional Testing
- Conversational AI Testing
- Workflow Testing
- LLM Security Testing
- Prompt Injection Testing
- Automated Evaluation Reports

---

## Technology Stack

- Promptfoo
- Ollama
- Llama 3.2
- YAML
- VS Code

---

## Project Structure

```
Enterprise-AI-Testing-Framework
│
├── prompts/
├── reports/
├── screenshots/
├── test-data/
├── tests/
│   ├── functional/
│   ├── conversational/
│   ├── workflow/
│   └── llm/
│
├── promptfooconfig.yaml
└── README.md
```

---

## Test Modules

### Functional Testing

- Password Reset
- Leave Policy
- VPN Support
- Employee Benefits
- Working Hours
- HR Contact

### Conversational AI Testing

- Multi-turn conversations
- Context awareness
- Follow-up questions

### Workflow Testing

- Employee onboarding guidance
- Password reset workflow
- Leave application workflow
- VPN setup workflow

### LLM Security Testing

- Prompt Injection
- System Prompt Protection
- Confidential Information Requests
- Harmful Request Handling

---

## Execution

Run:

```bash
promptfoo eval
```

View report:

```bash
promptfoo view
```

---

## Sample Results

- Functional Tests
- Conversational Tests
- Workflow Tests
- LLM Security Tests

Promptfoo Evaluation Report screenshots are available inside the **screenshots** folder.

---

## Future Improvements

- Semantic assertions
- API integration
- CI/CD execution
- Expanded security test coverage