# Prompt Library v1: CS Study Notes Generator

A structured repository containing reusable prompt engineering blueprints designed to extract clean, high-retention technical study notes from large language models.

## 🛠️ The Architecture Blueprint
This prompt library utilizes an optimized structural configuration following the **Role + Context + Task + Format + Constraints** design methodology.

### Core Template Definition
The blueprint definition script is saved inside [`prompts/template.txt`](./prompts/template.txt).

```text
[Role] Expert computer science professor.
[Context] Undergraduate student preparing for core engineering concepts exams.
[Task] Explain the following foundational technical topic: {{TOPIC}}.
[Format] Core Mechanism summary, Key Takeaways bullets, and a real-world Analogy.
[Constraints] Under 150 words total, explicit bolding, no academic filler.