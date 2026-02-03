# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
Select Input Text

Choose a 500-word technical article titled “The Basics of Blockchain Technology”.

Identify AI Platforms

ChatGPT

Google Gemini

Claude

Microsoft Copilot

Apply Prompting Techniques
For each platform, apply the following prompting methods:

Zero-Shot Prompting:

Provide only the article and ask for a summary without examples.

Few-Shot Prompting:

Provide 1–2 sample summaries along with the article.

Chain-of-Thought Prompting:

Ask the model to reason step-by-step before generating the summary.

Role-Based Prompting:

Assign a role (e.g., “You are an educational content writer for undergraduate students”).

Generate Summaries

Collect summaries from each platform for all prompting techniques.

Evaluate Output

Compare the summaries based on:

Accuracy

Coherence

Simplicity

Speed

User Experience

Analyze Results

Identify the most effective combination of platform and prompting technique
## Result
The experiment revealed clear differences in summarization quality across platforms and prompting techniques:

Role-based prompting consistently produced the most simple and student-friendly summaries, especially on ChatGPT and Claude.

Zero-shot prompting was the fastest, but summaries were often less structured and sometimes missed key technical details.

Few-shot prompting improved coherence but required more effort in prompt design.

Chain-of-thought prompting produced highly accurate summaries, but response time was slightly slower and sometimes included unnecessary reasoning.

Best Overall Combination:

Platform: ChatGPT

Prompting Technique: Role-Based Prompting

This combination delivered the best balance of accuracy, clarity, simplicity, and user experience, making it most suitable for summarizing technical content for undergraduate students.


