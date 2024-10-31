---
layout: post
title: "The Underlying Differences Between AI and Human Coding"
subtitle: "Conducted at Washington University in St. Louis"
tags: ["AI", "statistics"]
author: "Aiden Qian"
---

## The Underlying Differences Between AI and Human Coding

The rapid development of artificial intelligence (AI) has led to its widespread adoption in software development. Tools like OpenAI's Codex, ChatGPT, and GitHub Copilot have demonstrated impressive abilities to generate code from natural language descriptions. This paper addresses the debate surrounding AI-generated code versus human-created solutions by analyzing competitive programming problems.

### Key Differences Between Human and AI Solutions

- **Cyclomatic Complexity**: Human solutions tend to use modular functions, enhancing reusability, while AI often handles everything in `main()`.
  
- **Lines of Code (LOC)**: Both solutions can have similar LOC, but humans reuse code more effectively.
  
- **Commenting**: Human solutions use both single-line and multiline comments, while AI typically does not comment code.

- **Variable Names**: Humans use more descriptive variable names, while AI solutions tend to use generic ones.

- **Modularity**: Human solutions favor separating logic into functions for maintainability, while AI-generated code is more monolithic.

### Methodology Overview: Comparative Analysis

This experiment analyzed 200 competitive coding problems from platforms like USACO, CSES, and Codeforces. Human solutions were obtained from USACO Guide, while AI-generated solutions used prompts like "Give me a solution to this competitive coding problem in C++."

Metrics analyzed include cyclomatic complexity, LOC, number of functions, comments, and variables.

#### LOC/SLOC Percentage
Human solutions tend to have more blank lines and comments, which results in a lower SLOC/LOC ratio compared to AI-generated solutions.

#### Consistency in AI Solutions
AI solutions display lower standard deviation in metrics like LOC and functions, suggesting a more uniform structure compared to human solutions, which vary more widely.

### Key Observations

1. **Human Solutions Have More Commenting**: Human solutions include more comments and multiline documentation.
  
2. **Greater Variable Diversity in Human Solutions**: Humans use a greater diversity of data types, while AI tends to default to simpler types.

3. **Compile Rates**: AI solutions occasionally fail to compile, while human solutions compiled successfully in all cases.

### Conclusion

Human solutions demonstrate more flexibility and readability due to better use of modularity, comments, and variable types. AI-generated code, while consistent and concise, may lack adaptability. Future research could further investigate these differences, particularly across various programming languages.

[Read the full article here](https://drive.google.com/file/d/1sWvj2PBj9P7CnXeNLwEYAvdDrZBYg6Wl/view?usp=sharing)
