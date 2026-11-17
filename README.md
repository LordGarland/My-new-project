# BugBuddy – The Socratic Coding Tutor for Middle School
Building AI course project

## Summary
BugBuddy is an AI coding assistant designed for middle school students (ages 11–14). Instead of giving away the right answer, it uses Socratic questioning and age-appropriate hints to help young beginners find and fix bugs on their own, fostering critical thinking.

## Background
Learning to code in middle school is exciting, yet beginners often hit a wall of frustration when facing their first syntax or logic errors. In a typical classroom of 20 to 25 students, a single teacher cannot assist everyone simultaneously when their programs fail to run. 

My personal motivation stems from seeing young students lose confidence and give up on programming simply because a missing bracket or a wrong loop condition feels like an insurmountable obstacle. This topic is crucial because early positive experiences with computational thinking build problem-solving skills that go far beyond computer science.

## Data and AI techniques
BugBuddy relies on two main data sources:
* **Educational datasets:** Curated collections of common beginner coding errors (in block-based environments like Scratch or introductory Python) paired with teacher-approved pedagogical hints.
* **User session data:** The student's current code snippet, error logs, and the ongoing chat history during the debugging session.

From a technical standpoint, the project uses **Large Language Models (LLMs)** and **Natural Language Processing (NLP)** techniques. Specifically, it relies on **Prompt Engineering** and **Few-Shot Learning** to enforce strict pedagogical guardrails, ensuring the AI acts as a patient tutor rather than a code generator.

## How is it used
BugBuddy is designed to be used directly inside the school computer lab or at home during coding homework. 
* **Students (ages 11–14)** paste their broken code or ask why their program isn't behaving as expected. BugBuddy responds with simple, encouraging questions (e.g., *"Look closely at line 4: what happens to your score variable when the loop repeats?"*).
* **Teachers** benefit from a reduced classroom bottleneck, allowing them to focus on students who need deeper conceptual help while BugBuddy handles routine syntax and logic debugging.
* **Affected stakeholders:** While students gain autonomy and teachers gain time, parents also benefit from having a safe, structured learning tool at home that prevents children from simply copying and pasting solutions from the internet.

## Challenges
As any technological solution, BugBuddy has clear limitations and does not solve everything:
* **Over-reliance and bypass attempts:** Clever students might try to trick the AI into writing the full code for them, requiring continuous refinement of the system's guardrails.
* **Emotional nuance:** An AI cannot replace the human empathy of a teacher who notices when a student is genuinely overwhelmed or needs a break.
* **Hallucinations:** LLMs can occasionally misinterpret very messy beginner code and give confusing hints.
* **Privacy:** Handling interactions with minors requires strict compliance with data protection regulations (such as GDPR), meaning no personal student data should be stored or used to train public models.

## What next
In the future, BugBuddy could grow in several directions:
* **Visual integration:** Supporting drag-and-drop block languages like Scratch by analyzing screenshots or project JSON files, not just text-based code.
* **Teacher Dashboard:** Adding an anonymized analytics panel that shows teachers the most common bugs encountered by the class during a lesson, helping them adjust their next lecture.
* **Gamification:** Introducing a badge system that rewards students for solving bugs with the fewest possible hints.

## Acknowledgments
* Inspiration for this project comes from the pedagogical principles of the Socratic method and modern educational AI initiatives like Khanmigo (Khan Academy).
* Project structure and documentation guidelines provided by the *Elements of AI / Building AI* course by Reaktor and the University of Helsinki.
