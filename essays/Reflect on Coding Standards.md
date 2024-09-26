---
layout: essay
type: essay
title: "ESLint: The Useful but Painful Micromanager"
# All dates must be YYYY-MM-DD format!
date: 2024-09-26
published: true
labels:
  - Software Engineering
---

In my exploration of coding standards, particularly through the integration of ESLint into my VSCode environment, I've encountered a series of challenges. These challenges not only sharpened my coding skills but also deepened my appreciation for the discipline coding standards impose. Here's a breakdown of some specific issues that ESLint would likely flag in a typical JavaScript snippet, illustrating how such tools enforce coding standards and promote better coding practices.

**Sample JavaScript Code:**

```javascript
console.log('xxx.js file loaded');

const hasLove = (lyrics: string[]): boolean => {
  return lyrics.some(lyric => lyric.includes('love'));
};

const numLoves = (lyrics: string[]): number => {
  return lyrics.filter(lyric => lyric.includes('love')).length;
};

const helloLoveLyrics = [
  'I don\'t know where you were, I don\'t know what became of us',
  'And I don\'t know what went wrong, time had turned its back on us',
  'It\'s not that I gave up, I just stopped trying',
  'I have my mind made up on no-more-crying',
  'I thought tonight would be just me, myself and I\'ing',
  'I guess I\'m not the one that\'s deciding',
  'Hello, love, all dressed up',
  'Whatchu doin\' round here? I didn\'t expect to see ya',
  'Hello, love, I got both hands up',
  'Yeah, you got me, you got me, you got me',
  'And it feels so good to see ya',
  'Hello, love',
  'Hello, love',
  'Hello, hello, love',
];
console.log(hasLove(helloLoveLyrics));
console.log(hasLove(helloLoveLyrics.slice(0, 4)));
console.log(numLoves(helloLoveLyrics));
console.log(numLoves(helloLoveLyrics.slice(4, 6)));
```

**ESLint Issues Identified:**

1. **Mixed Quotes**: ESLint may flag the inconsistent use of single and escaped single quotes. To enhance readability and maintain consistency, one style should be chosen.
   
   **Correction:** Use only single quotes or double quotes consistently.
   ```typescript
   "I don't know where you were, I don't know what became of us",
   ```

2. **Arrow Function Parentheses**: Some ESLint configurations require parentheses around parameters in arrow functions for better readability.
   
   **Correction:** Add parentheses around the `lyric` parameter.
   ```typescript
   lyrics.some((lyric) => lyric.includes('love'));
   ```

3. **Semicolons**: Depending on the ESLint configuration, either the presence or absence of semicolons can be enforced. Consistency is key.
   
   **Correction:** Ensure semicolons are either consistently used or omitted based on the style guide.
   ```typescript
   console.log('xxx.js file loaded');
   ```

4. **Unused Expressions**: The initial console log might be flagged if ESLint is set to discourage or flag unused expressions or console statements in production code.

These insights demonstrate the dual nature of coding standards enforcement tools like ESLint. While initially, they may seem to complicate the development process with what appears to be tedious critiques, it's true value lies in clarity, precision, and consistency. Each ESLint error corrected is not just an act of compliance but a step towards deeper understanding and better software craftsmanship. Thus, embracing coding standards and tools that enforce them is about committing to continuous improvement and excellence in our coding practices.
