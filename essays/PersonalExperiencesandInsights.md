---
layout: essay
type: essay
title: "Personal Experiences and Insights"
# All dates must be YYYY-MM-DD format!
date: 2025-05-07
published: true
labels:
  - Software Engineering
---

Reflections on the Use of AI in ICS 314: Personal Experiences and Insights

I. Introduction

Artificial Intelligence (AI) has quickly become an integral tool in education, particularly within fields that require rapid iteration, problem-solving, and code development such as Software Engineering. In ICS 314, the inclusion of AI tools has offered new ways to approach coding challenges, understand concepts, and speed up development cycles. I have used a variety of AI tools throughout the semester, with ChatGPT being my primary assistant. I’ve also experimented briefly with GitHub Copilot and Cursor. These tools were especially helpful in debugging, understanding syntax nuances, and generating code snippets.

II. Personal Experience with AI

Experience WODs e.g. E18: For the Functional Programming Experience WOD E18, I used ChatGPT to help me better understand how to use Underscore.js functions like _.pluck, _.reduce, and _.filter. I asked prompts like: “How do I use _.pluck to extract values from an array of objects?” and “What’s the difference between _.reduce and JavaScript’s native .reduce() method?” These helped clarify syntax and use cases. I also tested my final percentageHawaiian function using ChatGPT to verify the math logic behind filtering and summing up data based on object properties. AI was most useful for understanding the structure of Underscore methods and confirming that I was using them in idiomatic ways. However, I still had to write and debug the final function logic myself.

In-class Practice WODs: For the practice WOD based on recreating the Island Snow website, I used ChatGPT to help with Bootstrap layout and image handling. One of my prompts was: “How do I make a navbar that collapses with a toggle button using Bootstrap 5?” Another was: “How do I center an image in Bootstrap without it stretching?” These were useful because the official Bootstrap docs are large and sometimes overwhelming when under time pressure. AI helped me find the correct class combinations like container-fluid, d-flex, and justify-content-evenly quickly. However, sometimes ChatGPT suggested outdated syntax or misaligned HTML, so I still had to double-check my output in the browser.

In-class WODs: For the in-class WOD involving the wod-aloha-beer project, I used ChatGPT during coding to help debug HTML/CSS issues in real time. For example, I asked, “How do I space Bootstrap nav links evenly across a row?” and “Why is my image not aligning using float-start in Bootstrap 5?” ChatGPT’s responses were mostly accurate and gave me quick ideas to test. The benefit was speed I could keep up during the limited time without digging through the docs. The downside was that sometimes I got generic answers that didn’t fully match our required setup, so I still had to adapt the code manually.

Essays: For the essay reflecting on recreating the Salvage Public website, I used ChatGPT to help organize my thoughts and improve the flow of my writing. My original notes were fragmented, and I asked prompts like: “Help me structure a reflection essay on recreating a website using Bootstrap 5” and “How can I explain why I chose Bootstrap in a student friendly tone?” ChatGPT helped turn rough bullet points into readable sentences. It was especially helpful for phrasing conclusions and clarifying my points about challenges with customization and responsiveness. I still rewrote most of the content in my own words, but AI gave me a clearer starting structure.

Final Project: For our group’s UH Marketplace app, my main contributions were creating the schema using Prisma and building the profile page. I used ChatGPT to help with syntax and structuring the prisma.schema file. For example, I asked, “How do I define a one to many relationship in Prisma for users and items?” The AI’s responses helped clarify how to properly relate users to their posted items and favorites. For the profile page, I asked ChatGPT things like “How do I fetch and display related data in Next.js using Prisma?” and “How do I use Tailwind CSS to align sections cleanly on a dashboard layout?” These helped me quickly structure a clean and responsive layout. While I still had to manually debug logic for displaying user data, ChatGPT accelerated the setup process and helped me focus on styling and functionality.

Learning a concept / tutorial: One of the key design concepts I had to learn was how to use containers effectively for layout and spacing in web design. I asked ChatGPT, “What’s the difference between .container, .container-fluid, and custom width containers in Bootstrap 5?” and “When should I use containers versus rows and columns?” It helped clarify that .container provides fixed-width centered content while .container-fluid stretches across the full viewport. This was especially useful when I needed to wrap navigation bars or body sections in a consistent layout without breaking responsiveness. ChatGPT also explained how to nest containers inside grid rows to better control alignment and padding, which I applied directly in my projects. It made my page structure cleaner and easier to manage.

Answering a question in class or in Discord: I didn’t have the opportunity to answer questions in class or on Discord during ICS 314. Most of the time, I was focused on completing my own work and keeping up with the pace of the assignments and WODs. When I did have questions, I usually turned to ChatGPT first before posting anything publicly. This made me more independent in troubleshooting and understanding code, but it also meant I didn’t get involved in the class discussion as much. If I were to retake the course, I’d try to be more active in Discord by sharing what I learned from AI tools to help others too.

Asking or answering a smart-question: For the Smart Questions essay assignment, I analyzed two Stack Overflow posts one that asked clearly about using XNA and Silverlight for game development, and another that vaguely questioned private class properties. I didn’t use AI to write this essay because I wanted to evaluate the questions myself based on clarity, detail, and structure. Writing this helped me better understand what makes a question “smart” and how important it is to provide context and code examples. Although I didn’t ask or answer a smart question myself in Discord or class, this assignment made me more aware of how I phrase technical questions in general and how to be clearer when describing code problems in the future.

Coding example e.g. “give an example of using Underscore .pluck”: While working on the Experience WOD that involved functional programming with Underscore.js, I used ChatGPT to understand how _.pluck works. I asked, “Give an example of using Underscore’s _.pluck to get values from an array of objects.” ChatGPT provided a clear example using an array of student objects and extracting their grades. I adapted that to my dataset (uhdata) by plucking the "AWARDS" field from the first few objects. The AI’s example was helpful as a template — it showed me how _.pluck works under the hood and how to combine it with other functions like _.reduce for total counts.

Explaining code: While working on our final project, I needed to explain how the profile page pulled and displayed a user’s posted items using Prisma. I copied the code into ChatGPT and asked, “How can I explain this Prisma query and map function to someone new to Next.js?” The AI broke it down into simple steps, explaining how the query filters items based on the logged in user’s ID and then maps them into a list format. This helped me explain the code more clearly to one of my teammates, especially the difference between server side and client side rendering. It also gave me a better understanding of how to communicate technical concepts to others in a straightforward way.

Writing code: When building features for the profile page in our final project, I used ChatGPT to help speed up writing repetitive code. For example, I asked, “How do I write a React component that displays a user’s items in a card layout using Tailwind CSS?” ChatGPT gave me a basic layout with JSX and Tailwind classes, which I then customized to match our design. It was especially helpful for generating clean starting points so I didn’t have to build everything from scratch. That said, I always had to tweak the props, state, and event handlers to match our app’s structure, so the AI gave me momentum but not a full solution.

Documenting code: In the final project, I wrote a function that queried the database for all items posted by a specific user using Prisma. To make the code more readable for my teammates, I used ChatGPT to help generate a JSDoc comment. My prompt was: “Write a JSDoc comment for a Prisma function that returns all marketplace items where userId matches the logged-in user.” ChatGPT gave me a clear comment block that described the function purpose, parameters, and return value. I edited it slightly to include the exact model name and property. This saved time and ensured that our code had consistent, professional looking documentation across files.

Quality assurance: While working on the profile page for the final project, I used ChatGPT to help fix ESLint issues that kept showing up in my Next.js/TypeScript files. I asked, “Fix the ESLint warning for missing return types in a React functional component,” and pasted part of my ProfilePage.tsx. ChatGPT added the correct return type JSX.Element and reminded me to avoid using any when I could define an interface instead. I also asked, “How do I resolve the ‘react hooks/exhaustive deps’ warning in a useEffect?” which helped me clean up some unnecessary dependencies in my hook. The AI didn’t catch every ESLint config nuance, but it sped up my debugging and made the final code cleaner and compliant with our linting rules.

Other uses in ICS 314: One other way I used ChatGPT in ICS 314 was to help brainstorm feature ideas and file structure for our group project. I asked, “What’s a good folder structure for a full-stack Next.js app using Prisma and Tailwind?” and it gave me a breakdown with folders like /components, /lib, /pages, and /prisma. While we didn’t follow it exactly, it gave us a helpful starting point to organize our code more clearly. I also used it once to generate placeholder item data to test layouts before hooking up the real database. This saved time during prototyping and helped our team visualize the final layout earlier in development.

III. Impact on Learning and Understanding

AI didn’t replace the learning process it accelerated it. It allowed me to get over minor hurdles faster, freeing up time to focus on larger architectural decisions or concepts. At the same time, relying too much on it sometimes led to surface level understanding. I had to remind myself to stop and analyze what the AI produced rather than blindly copying it.

IV. Practical Applications

Outside ICS 314, I’ve used ChatGPT to troubleshoot code in other classes like ICS 212 and during hackathons like HACC. One example: I asked it to help parse command line arguments in C. It explained how to use argc and argv concisely. This shows that AI’s utility isn’t limited to one course it’s becoming a cross-functional tool for CS students.

V. Challenges and Opportunities

The main challenge is overreliance. There were times when I accepted an answer that didn’t fully align with the context of the assignment. It’s also easy to become passive in the learning process. However, AI offers opportunities for students to accelerate learning, get unstuck quickly, and explore alternative coding patterns they might not have considered.

VI. Comparative Analysis

Compared to traditional methods, AI assisted learning is faster and often more engaging. You get instant feedback and can explore multiple variations of a solution. However, traditional methods often promote deeper retention, especially when you struggle through a problem and solve it manually. A blended approach seems most effective learn it yourself, then use AI to reinforce or verify.

VII. Future Considerations

AI will likely become more deeply integrated into software engineering education perhaps even becoming a co pilot for every student by default. Future improvements should focus on making AI more context aware and aligned with specific course objectives. There’s also room for AI tools to detect and explain conceptual misunderstandings, not just fix syntax.

VIII. Conclusion

Using AI in ICS 314 has been a valuable experience. It has helped me learn faster, write cleaner code, and explore alternative solutions. However, its usefulness depends on how intentionally it’s used. AI is best seen as a partner, not a crutch. Moving forward, I believe the best learning will come from a balance between personal effort and intelligent assistance.

