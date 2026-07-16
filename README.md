# Build Your First Reusable Prompt Library

## Week 1 – Generative AI & Prompt Engineering

### NeuroFive Solutions Internship

---

## Overview

This project is part of my **Generative AI & Prompt Engineering Internship** at **NeuroFive Solutions**.

The objective of this assignment is to design a **reusable prompt library** using a structured template approach. Instead of writing prompts from scratch for every task, this project demonstrates how prompt engineers can create **parameterized templates** that generate consistent, high-quality outputs by changing only a few variables.

The selected use case is **LinkedIn / Social Media Caption Generation** for AI and technology-related content.

---

## Objectives

* Build a reusable prompt template using a consistent structure.
* Apply the **Role + Context + Task + Format + Constraints** framework.
* Generate multiple prompts by swapping variables only.
* Test the prompts in a Large Language Model (LLM).
* Document the template and outputs as **Prompt Library v1**.

---

## Use Case

### Professional LinkedIn Caption Generator

The prompt library is designed for creating professional LinkedIn posts related to:

* Artificial Intelligence
* Machine Learning
* Prompt Engineering
* Software Development
* AI Ethics
* Career Growth in Technology

---

## Template Structure

The reusable prompt follows five clearly defined sections:

| Section         | Purpose                                 |
| --------------- | --------------------------------------- |
| **Role**        | Defines the AI's expertise and behavior |
| **Context**     | Provides background information         |
| **Task**        | Specifies what the AI should do         |
| **Format**      | Defines the structure of the output     |
| **Constraints** | Applies quality and style limitations   |

---

## Prompt Template

```text
ROLE
You are an experienced LinkedIn content strategist and AI copywriter.

CONTEXT
I regularly post educational and professional content related to artificial intelligence, machine learning, prompt engineering, software development, and technology careers.

TASK
Write a LinkedIn caption about: {TOPIC}
Target audience: {AUDIENCE}
Purpose: {PURPOSE}

FORMAT
- Start with a strong hook
- 150–250 words
- Short paragraphs
- End with a discussion question
- Include 5 relevant hashtags

CONSTRAINTS
- Professional but conversational tone
- No clickbait
- Avoid unnecessary emojis
- Keep information accurate and practical
```

---

## Prompt Variations

Five prompts were created from the same template by changing only the variables:

| Prompt | Topic                    | Audience                 | Purpose                                            |
| ------ | ------------------------ | ------------------------ | -------------------------------------------------- |
| 1      | Agentic AI               | Students learning AI     | Explain how Agentic AI differs from traditional AI |
| 2      | Prompt Engineering       | Beginners                | Teach why prompting matters                        |
| 3      | AI Ethics                | Software Engineers       | Raise awareness about responsible AI               |
| 4      | Multimodal AI            | Technology Professionals | Explain real-world applications                    |
| 5      | Building an AI Portfolio | University Students      | Motivate students to create practical AI projects  |

---

## Testing Environment

The prompts were tested using **ChatGPT (GPT-5.5)**.

Each prompt was executed without modifying the template structure, demonstrating the reusability of the design.

---

## Project Structure

```text
Build-Your-First-Reusable-Prompt-Library/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.md
│
├── templates/
│   └── linkedin_caption_template.md
│
├── prompts/
│   ├── prompt_01_agentic_ai.md
│   ├── prompt_02_prompt_engineering.md
│   ├── prompt_03_ai_ethics.md
│   ├── prompt_04_multimodal_ai.md
│   └── prompt_05_ai_portfolio.md
│
├── outputs/
    ├── output_01.md
    ├── output_02.md
    ├── output_03.md
    ├── output_04.md
    └── output_05.md

```

---

## Key Learning Outcomes

Through this assignment, I learned that:

* Reusable prompt templates save time and reduce repetition.
* Structured prompts improve output consistency across tasks.
* Separating instructions from variables makes prompts easier to maintain.
* Prompt libraries can be versioned and documented similarly to software components.
* The **Role + Context + Task + Format + Constraints** framework is an effective standard for professional prompt design.

---

## Why Reusable Prompt Libraries Matter

Reusable prompt libraries function similarly to **functions in programming**. Instead of copying and editing large prompts repeatedly, engineers can maintain a single template and generate many task-specific prompts by replacing variables such as topic, audience, or purpose. This approach improves scalability, maintainability, and quality control in AI-assisted workflows.

---

## Future Improvements (Prompt Library v2)

Planned enhancements include:

* Adding tone presets (formal, educational, persuasive, technical).
* Supporting multiple social platforms (LinkedIn, X/Twitter, Instagram).
* Adding automatic hashtag generation rules.
* Creating evaluation criteria for caption quality.
* Building a small Python script to fill template variables automatically.

---

## Conclusion

This project demonstrates how structured prompt engineering can transform ad-hoc prompting into a **repeatable and reusable workflow**. By designing a well-documented template and generating multiple prompts from it, I created a maintainable **Prompt Library v1** that can be extended for future AI content generation tasks.

The assignment highlights an important principle of professional prompt engineering: **build reusable systems, not one-time prompts**.

---

## Author

**Shah Mubarak Zaib**

BS Computer Science Student
AI & Prompt Engineering Enthusiast
AI/ML Intern | Prompt Engineer | Python Developer

---

## Acknowledgements

This project was completed as part of the **Week 1 – Generative AI & Prompt Engineering Internship Program** at **NeuroFive Solutions**.

Special thanks to the mentors and the NeuroFive Solutions team for designing hands-on assignments that encourage practical prompt engineering and reusable AI workflow design.
