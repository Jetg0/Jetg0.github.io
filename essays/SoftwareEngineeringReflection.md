---
layout: essay
type: essay
title: "What I Learned About Software Engineering"
date: 2025-05-12
published: true
---

# What I Learned About Software Engineering

After working on the UH Marketplace project, I realized that this class was about much more than just web development. The most valuable skills I learned were fundamental software engineering practices that apply to any kind of software, not just websites.

In this reflection, I’ll talk about three core concepts **Configuration Management**, **Agile Project Management**, and **Design Patterns** and how they show up beyond web apps. Every section has real examples from our project.

---

## 1. Configuration Management

**What is it?**  
Configuration management is the process of tracking and controlling changes in your software. This includes your source code, dependencies, configuration files, and environment settings. It ensures everyone works on the same version of a project and that changes are safe, reversible, and reproducible.

**How we used it:**  
For UH Marketplace, we used Git for version control and managed dependencies in `package.json`. This let our team:
- Work on new features in separate branches without breaking main code.
- Roll back to earlier versions if bugs appeared.
- Let new team members set up the project easily with `git clone` and `npm install`.

**Example: `package.json`**
```json
{
  "name": "uh-marketplace-app",
  "version": "1.0.0",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "lint": "next lint"
  },
  "dependencies": {
    "next": "^14.2.4",
    "react": "^18.2.0",
    "prisma": "^5.16.1"
  }
}
```

**Example: Common Git Workflow**
```sh
# Make a new feature branch
git checkout -b feature/favorites

# Add and commit changes
git add .
git commit -m "Add favorites feature"

# Push branch for review
git push origin feature/favorites

# Open a Pull Request on GitHub to merge
```

**Why it matters everywhere:**  
These practices are essential for any software project—mobile apps, desktop apps, libraries, or even hardware firmware—because teamwork and change are universal.

---

## 2. Agile Project Management

**What is it?**  
Agile project management is an iterative approach where you work in small increments, get feedback often, and can quickly adapt. One Agile technique we used is **Issue Driven Project Management (IDPM)**, where every task (feature, bug, improvement) is an “issue” tracked in a tool like GitHub Projects.

**How we used it:**  
We organized our work with GitHub issues and a project board. Each teammate claimed issues, worked on them, and moved them through columns (“To Do”, “In Progress”, “Done”). This made our workflow clear and kept us moving forward, even if priorities shifted.

**Example: GitHub Issue**
```yaml
title: Add Search Bar Functionality
assignees: [jetg0]
labels: [feature, frontend]
status: In Progress
description: |
  Implement a search bar on the Explore page to filter listings by keyword.
```

**Example: Project Board**
```txt
| To Do           | In Progress           | Done            |
|-----------------|----------------------|-----------------|
| Add user roles  | Add search bar       | Set up CI/CD    |
| Improve login   | Fix page layout bug   | Implement login |
```

**Why it matters everywhere:**  
You can use Agile and IDPM for any group project—not just coding. It works for game dev, research, robotics, or planning events. Breaking work into clear issues and short cycles keeps teams focused and adaptable.

---

## 3. Design Patterns

**What is it?**  
Design patterns are reusable solutions to common software design problems. They’re not code you copy, but ideas you apply to organize your system in a proven way.

**How we used it:**  
In UH Marketplace, we used the **Controller pattern** to separate business logic from our user interface. Our API routes in Next.js are like controllers: they handle requests, manage data, and return responses, keeping logic out of the frontend.

**Example: API Route Controller**
```typescript
// pages/api/items.ts
import { NextApiRequest, NextApiResponse } from 'next';
import prisma from '../../lib/prisma';

export default async function handler(
  req: NextApiRequest,
  res: NextApiResponse
) {
  if (req.method === 'GET') {
    const items = await prisma.item.findMany();
    res.status(200).json(items);
  } else if (req.method === 'POST') {
    const { name, price } = req.body;
    const newItem = await prisma.item.create({ data: { name, price } });
    res.status(201).json(newItem);
  } else {
    res.status(405).json({ error: "Method not allowed" });
  }
}
```

**Why it matters everywhere:**  
Patterns like MVC, Singleton, Observer, or Factory show up in all software fields. Knowing and applying them makes code easier to maintain and grow—even in games, desktop apps, or APIs.

---

## Final Thoughts

This class taught me to think like a software engineer, not just a web developer.  
- **Configuration management** helps me keep projects organized and maintainable.
- **Agile project management** keeps teams on track and lets us adapt.
- **Design patterns** help me write code that other engineers can quickly understand and extend.

These lessons are useful in any project, no matter the tech stack or domain.

---
