---
layout: essay
type: essay
title: "The AI Power Tool"
date: 2025-05-07
published: true
labels:
  - Software Engineering
---

# Reflections on the Use of AI in ICS 314: Personal Experiences and Insights

## Introduction

Artificial Intelligence (AI) has rapidly become an essential tool in education—especially in software engineering, where fast iteration, problem-solving, and code development are crucial. In ICS 314, AI tools provided new ways to approach coding challenges, learn concepts, and accelerate development. Throughout this semester, I mainly used ChatGPT as my AI assistant, while occasionally trying GitHub Copilot and Cursor. These tools were particularly helpful for debugging, clarifying syntax, and generating code snippets.

## Personal Experience with AI Tools

### Coding & Debugging Support

For the Functional Programming WOD (E18), ChatGPT helped me understand how to use Underscore.js methods like `_.pluck`, `_.reduce`, and `_.filter`. I’d ask:
```text
How do I use _.pluck to extract values from an array of objects?
What’s the difference between _.reduce and JavaScript’s native .reduce() method?
```
AI clarified syntax and use cases, but I still needed to write and debug the core logic myself.

### Layout and Design Help

During WODs for recreating websites (like Island Snow), I asked ChatGPT questions such as:
```text
How do I make a navbar that collapses with a toggle button using Bootstrap 5?
How do I center an image in Bootstrap without it stretching?
```
This saved me time compared to searching through the full Bootstrap docs, especially under time pressure. However, I always checked results in the browser and adapted code as needed.

### Real-time Coding Assistance

For the “wod-aloha-beer” project, ChatGPT helped debug HTML/CSS in real time:
```text
How do I space Bootstrap nav links evenly across a row?
Why is my image not aligning using float-start in Bootstrap 5?
```
AI sped up my workflow, but sometimes gave generic answers that required manual adjustment.

### Writing and Organizing Essays

When writing essays (like the Salvage Public reflection), I prompted ChatGPT to:
```text
Help me structure a reflection essay on recreating a website using Bootstrap 5.
How can I explain my Bootstrap design choices in a student-friendly tone?
```
ChatGPT helped organize my scattered notes into readable sentences and conclusions, which I then personalized further.

### Building the Final Project

For our group’s UH Marketplace app, I contributed to the Prisma schema and profile page. ChatGPT assisted with:
```text
How do I define a one-to-many relationship in Prisma for users and items?
How do I fetch and display related data in Next.js using Prisma?
How do I use Tailwind CSS to align sections on a dashboard layout?
```
AI made it easier to get started, letting me focus on styling and feature logic.

### Learning Concepts & Tutorials

To understand layout containers in Bootstrap, I asked:
```text
What’s the difference between .container and .container-fluid in Bootstrap 5?
When should I use containers vs. rows and columns?
```
This led to better use of layout patterns in my projects.

### Documentation & Quality Assurance

For documenting code, I had ChatGPT generate JSDoc comments:
```js
/**
 * Returns all marketplace items for the logged-in user.
 * @param {string} userId - The user ID to query.
 * @returns {Promise<Array>} - List of user items.
 */
```
For ESLint and TypeScript issues, ChatGPT offered suggestions on missing return types, prop interfaces, and React hook dependencies, making my code cleaner and more compliant.

### Other Use Cases

ChatGPT also helped brainstorm file structure and feature ideas, for example:
```text
What’s a good folder structure for a full-stack Next.js app using Prisma and Tailwind?
```
It even generated placeholder item data for early UI prototyping.

## Impact on Learning

AI didn’t replace the learning process—it accelerated it. I could overcome minor obstacles faster and focus on deeper concepts and architecture. However, I realized it was easy to become passive if I relied too much on AI suggestions, so I made sure to review and understand all generated code.

## Practical Applications

Outside of ICS 314, I’ve used ChatGPT in other classes (like ICS 212) and hackathons (HACC). For example, it helped me parse command-line arguments in C by explaining `argc` and `argv` clearly. This demonstrates how AI tools are becoming cross-functional helpers for CS students.

## Challenges and Opportunities

**Challenges:**
- Overreliance can lead to shallow understanding.
- AI sometimes gives generic or context-insensitive answers.
- It’s tempting to accept an answer without critical thinking.

**Opportunities:**
- Accelerates learning and problem-solving.
- Provides instant feedback and new coding perspectives.
- Enables students to focus more on big-picture design and less on syntax trivia.

## Comparative Analysis

Compared to traditional learning, AI-assisted learning is faster and sometimes more engaging—you get feedback instantly and can explore many solution paths. Traditional methods, however, often foster deeper retention and understanding. The best approach is blended: learn independently, then use AI to check, reinforce, and explore alternatives.

## Future Considerations

AI will likely become even more integrated in software engineering education, perhaps as a default "co-pilot" for students. The next step is making AI more context-aware and able to detect conceptual misunderstandings, not just syntax errors.

## Conclusion

Using AI in ICS 314 has been a genuinely valuable experience. It helped me learn faster, write cleaner code, and find alternative solutions. But its value depends on how intentionally it’s used—AI is best seen as a partner, not a crutch. The most
