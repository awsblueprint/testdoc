---
title: page main 2
deprecated: false
hidden: false
metadata:
  robots: index
---
# 🎯 React JSX & Components — 50 Interview Questions (With Answers & Explanations)

***

# 🔹 SECTION 1: Core Concepts (Q1–Q10)

***

### 1. What is JSX and why is it used?

**Answer:**
JSX is a syntax extension that allows writing HTML-like code in JavaScript.

**Explanation:**
It improves readability and makes UI code declarative. Internally, it compiles to `React.createElement()`.

***

### 2. Is JSX mandatory in React?

**Answer:**
No.

**Explanation:**
You can use `React.createElement()`, but JSX is preferred for simplicity.

***

### 3. What happens when JSX is compiled?

**Answer:**
It converts into JavaScript objects.

**Explanation:**
These objects represent elements in the Virtual DOM.

***

### 4. Why must JSX return a single parent element?

**Answer:**
Because JSX compiles into a single JavaScript object.

***

### 5. Difference between JSX and HTML?

**Answer:**
JSX has:

- `className` instead of `class`
- JavaScript expressions
- camelCase attributes

***

### 6. What are React components?

**Answer:**
Reusable UI building blocks.

***

### 7. Difference between functional and class components?

**Answer:**
Functional → hooks, simpler
Class → lifecycle methods, legacy

***

### 8. Why are components important?

**Answer:**
They enable modular, reusable, maintainable code.

***

### 9. What is props in React?

**Answer:**
Inputs passed to components.

***

### 10. Can components return null?

**Answer:**
Yes.

**Explanation:**
Useful for conditional rendering.

***

# 🔹 SECTION 2: Internal Working (Q11–Q20)

***

### 11. How does JSX work internally?

**Answer:**
JSX → Babel → JS → Virtual DOM → Real DOM

***

### 12. What is Virtual DOM?

**Answer:**
A lightweight copy of the real DOM.

***

### 13. What is reconciliation?

**Answer:**
Process of updating only changed parts of DOM.

***

### 14. When does a component re-render?

**Answer:**
On state or props change.

***

### 15. Does parent re-render affect child?

**Answer:**
Yes, by default.

***

### 16. What is React.memo?

**Answer:**
Prevents unnecessary re-renders.

***

### 17. What is key in React?

**Answer:**
Unique identifier for list items.

***

### 18. Why avoid index as key?

**Answer:**
Causes bugs when list order changes.

***

### 19. What is component lifecycle in functional components?

**Answer:**
Handled using hooks like `useEffect`.

***

### 20. Why is React declarative?

**Answer:**
You describe UI, React updates DOM.

***

# 🔹 SECTION 3: JSX Tricky Questions (Q21–Q30)

***

### 21. What will this render?

```jsx
<h1>{true}</h1>
```

**Answer:** Nothing

**Explanation:** Booleans are ignored.

***

### 22. Output?

```jsx
<h1>{0 && "Hello"}</h1>
```

**Answer:** 0

***

### 23. Why can't we use `if` inside JSX?

**Answer:**
Because JSX only supports expressions.

***

### 24. Difference between `{}` and `()` in JSX?

**Answer:**
`{}` → JS expressions
`() `→ grouping JSX

***

### 25. What is `props.children`?

**Answer:**
Content inside component tags.

***

### 26. Can JSX return arrays?

**Answer:**
Yes.

***

### 27. What is Fragment?

**Answer:**
Wrapper without extra DOM node.

***

### 28. What happens if JSX is malformed?

**Answer:**
Compilation error.

***

### 29. Can we write loops in JSX?

**Answer:**
No, use `.map()`.

***

### 30. Why use `dangerouslySetInnerHTML` carefully?

**Answer:**
It can cause XSS attacks.

***

# 🔹 SECTION 4: Real-World Scenarios (Q31–Q40)

***

### 31. How would you design reusable components?

**Answer:**
Use props and composition.

***

### 32. How do you handle empty data in UI?

**Answer:**
Render fallback like "No data".

***

### 33. How to avoid prop drilling?

**Answer:**
Use Context API.

***

### 34. How to optimize large lists?

**Answer:**
Use keys, memoization, virtualization.

***

### 35. How to conditionally render components?

**Answer:**
Ternary or logical operators.

***

### 36. How to pass dynamic content?

**Answer:**
Using props or children.

***

### 37. How to structure large apps?

**Answer:**
Break into small components.

***

### 38. How to handle missing props?

**Answer:**
Default props or fallback values.

***

### 39. When to use fragments vs div?

**Answer:**
Use fragments to avoid extra DOM.

***

### 40. How to handle user input UI?

**Answer:**
Controlled components with state.

***

# 🔹 SECTION 5: Advanced & Edge Case Questions (Q41–Q50)

***

### 41. Why shouldn't you mutate props?

**Answer:**
Props are read-only.

***

### 42. What is lifting state up?

**Answer:**
Sharing state via parent.

***

### 43. What is controlled vs uncontrolled components?

**Answer:**
Controlled → React state
Uncontrolled → DOM

***

### 44. What is memoization in React?

**Answer:**
Caching results to avoid re-renders.

***

### 45. What is component composition?

**Answer:**
Combining components instead of inheritance.

***

### 46. What causes infinite re-render?

**Answer:**
Updating state inside render.

***

### 47. Why avoid inline functions in lists?

**Answer:**
Performance overhead.

***

### 48. What is shallow comparison?

**Answer:**
Comparing references instead of deep values.

***

### 49. How does React handle events?

**Answer:**
Using synthetic events.

***

### 50. What is the biggest advantage of JSX + components?

**Answer:**
Building scalable, maintainable UI.

***

# ✅ Final Summary

These 50 interview questions cover:

- Core React concepts
- JSX deep understanding
- Tricky edge cases
- Real-world problem solving
- Performance and optimization

***

If you want next:
👉 Mock interview (live simulation)
👉 System design frontend questions
👉 React coding interview tasks
👉 Company-specific questions (Google, Amazon, etc.)

Just tell me 👍
