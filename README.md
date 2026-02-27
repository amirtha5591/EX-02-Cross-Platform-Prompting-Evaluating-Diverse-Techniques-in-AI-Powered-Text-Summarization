EX-02: Cross-Platform Prompting – Evaluating Diverse Techniques in AI-Powered Text Summarization
# AIM

To evaluate and compare the effectiveness of different prompting techniques (Zero-shot, Few-shot, Chain-of-Thought, Role-based prompting) across various AI platforms such as ChatGPT, Gemini, Claude, and Copilot for summarizing a 500-word technical article on “The Basics of Blockchain Technology.”

# SCENARIO

We are part of a content curation team for an educational platform that provides short and simple summaries of research papers to undergraduate students.

The task is to summarize a 500-word technical article on Blockchain Technology using multiple AI platforms and prompting strategies.

The comparison is based on:

Accuracy

Coherence

Simplicity

Speed

User Experience

# PROMPTING TECHNIQUES USED
# 1. Zero-Shot Prompting

The AI is directly asked to summarize without giving examples.

Example Prompt:
“Summarize the following article on Blockchain Technology in simple language for undergraduate students.”

# 2. Few-Shot Prompting

The AI is given 1–2 examples before asking it to summarize.

Example Prompt:
“Here is an example of how to summarize a technical topic.
Example: (sample summary given)
Now summarize the following Blockchain article in a similar way.”

# 3. Chain-of-Thought Prompting

The AI is asked to think step-by-step before summarizing.

Example Prompt:
“First identify the key concepts in the article. Then explain each concept briefly. Finally, combine them into a clear summary.”

# 4. Role-Based Prompting

The AI is assigned a role before summarizing.

Example Prompt:
“You are a professor explaining Blockchain Technology to first-year undergraduate students. Provide a clear and simple summary.”

# ALGORITHM

Step 1: Select a 500-word technical article on “The Basics of Blockchain Technology.”

Step 2: Choose AI platforms:

ChatGPT

Gemini

Claude

Copilot

Step 3: Apply Zero-shot prompting on each platform and generate summary.

Step 4: Apply Few-shot prompting on each platform and generate summary.

Step 5: Apply Chain-of-Thought prompting on each platform and generate summary.

Step 6: Apply Role-based prompting on each platform and generate summary.

Step 7: Evaluate each output based on:

Accuracy (Correct technical information)

Coherence (Logical flow)

Simplicity (Easy for students)

Speed (Response time)

User Experience (Ease of interaction)

Step 8: Compare results and identify the best combination.

# OBSERVATION (General Comparison)
<img width="910" height="263" alt="image" src="https://github.com/user-attachments/assets/bb8dbc68-8736-41f2-9b62-a4294e702376" />

# ANALYSIS

Zero-shot is fastest but may miss important depth.

Few-shot improves structure and clarity.

Chain-of-Thought gives deeper explanation but is slightly slower.

Role-based prompting produces the most student-friendly summaries.

ChatGPT and Claude generally provide better coherence.

Gemini is fast and simple.

Copilot works well but may be shorter in explanation.

# RESULT

From the evaluation, Role-Based Prompting with ChatGPT (or Claude) produced the best overall summary for undergraduate students.
