# Prompt Engineering for Developers - DeepLearning.AI

This repository contains my learning materials and practical implementations from the **Prompt Engineering for Developers** course by DeepLearning.AI. The course focuses on two fundamental principles for effective prompt engineering with Large Language Models (LLMs).

## Course Overview

This course teaches essential techniques for writing effective prompts to get the best results from LLMs like GPT-4. The materials cover systematic approaches to prompt design and optimization.

## Repository Contents

### Files

- **`1-prompt-guideline.ipynb`** - My personal implementation and practice notebook with custom examples
- **`1-prompt-guideline-v1.0`** - Original course material from DeepLearning.AI

## Key Learning Concepts

### Principle 1: Write Clear and Specific Instructions

**Tactics Covered:**
- **Delimiter Usage**: Using clear delimiters (```, """, <>, etc.) to separate different parts of input
- **Structured Output**: Requesting responses in specific formats like JSON or HTML
- **Condition Checking**: Having the model verify if certain conditions are met before proceeding
- **Few-Shot Prompting**: Providing examples to guide the model's response style

### Principle 2: Give the Model Time to "Think"

**Tactics Covered:**
- **Step-by-Step Instructions**: Breaking down complex tasks into sequential steps
- **Structured Reasoning**: Instructing the model to work out its own solution before making judgments
- **Format Specification**: Defining exact output formats for consistent results

## Practical Examples Implemented

### Text Summarization
- Basic summarization with delimiter usage
- Handling prompt injection attempts
- Multi-step text processing (summarize → translate → extract names → JSON output)

### Structured Data Generation
- Creating JSON formatted data (Bollywood movie listings)
- Custom data structures with specific fields

### Instruction Processing
- Conditional instruction rewriting
- Tea-making instructions formatted as numbered steps
- Handling non-instructional text appropriately

### Few-Shot Learning
- Grandparent-child dialogue examples
- Consistent style maintenance across responses

### Problem Solving & Verification
- Solar panel cost calculations
- Student solution verification
- Multi-step reasoning processes

### Model Limitations
- Understanding and handling hallucinations
- Verifying factual accuracy

## Technical Implementation

- **API Used**: OpenAI GPT-4 Turbo and GPT-3.5 Turbo
- **Programming Language**: Python
- **Key Libraries**: OpenAI Python SDK
- **Temperature Setting**: 0 (for consistent, deterministic outputs)

## Learning Outcomes

Through this course, I've gained practical experience in:
- Writing clear and specific prompts that reduce ambiguity
- Structuring prompts for complex multi-step tasks
- Understanding model limitations and hallucination risks
- Implementing systematic approaches to prompt optimization
- Using delimiters effectively to prevent prompt injection
- Designing prompts that encourage step-by-step reasoning

## Usage Notes

The notebooks demonstrate real-world applications of prompt engineering principles, showing both successful implementations and common pitfalls to avoid. Each example builds upon previous concepts, creating a comprehensive learning progression.

---

*This repository serves as a practical reference for prompt engineering techniques learned through the DeepLearning.AI course.*