# 21-Day Learning Plan: TypeScript + UX by Building a Kanban Task Tracker

> **Outcome-focused plan**: Each day lists what you should be able to *do* by the end of the day, plus concrete learning resources and hands-on tasks.
>
> **Assumptions**:
>
> * You are starting almost from scratch in JavaScript
> * You learn best by building
> * Web-only MVP
> * Stack: **TypeScript + React + basic CSS** (no backend until later)

---

## Week 1 — JavaScript & TypeScript Foundations (Mental Models First)

### Day 1 — JavaScript Basics: Variables & Thinking in Code

**By the end of today, you should be able to:**

* Write simple JavaScript that uses variables and outputs values
* Understand how code runs top-to-bottom
* Feel comfortable using the browser console

**Learn:**

* Variables (`let`, `const`)
* Basic data types: string, number, boolean

**Resources:**

* MDN: JavaScript First Steps – Variables
* freeCodeCamp: JavaScript Basics (Variables section)
* YouTube: “JavaScript in 1 Hour” (watch first ~20 mins)

**Practice:**

* Open browser console
* Create variables for a task: title, completed, priority
* Log them using `console.log`

---

### Day 2 — JavaScript Logic: Conditions & Comparisons

**By the end of today, you should be able to:**

* Make decisions in code using `if / else`
* Compare values safely

**Learn:**

* `if`, `else`
* Comparison operators (`===`, `!==`, `<`, `>`)
* Truthy vs falsy

**Resources:**

* MDN: Making decisions in JavaScript
* freeCodeCamp: Conditionals

**Practice:**

* Write logic: if task is completed → print "Done"
* Try different conditions in console

---

### Day 3 — JavaScript Collections: Arrays & Objects

**By the end of today, you should be able to:**

* Store multiple tasks in arrays
* Represent a task as an object

**Learn:**

* Arrays (`[]`)
* Objects (`{}`)
* Accessing properties

**Resources:**

* MDN: Arrays
* MDN: Objects basics

**Practice:**

* Create an array of task objects
* Each task: `{ id, title, status }`

---

### Day 4 — Functions: Reusable Logic

**By the end of today, you should be able to:**

* Write functions that perform actions on tasks
* Understand inputs and outputs

**Learn:**

* Function declarations
* Parameters & return values

**Resources:**

* MDN: Functions
* freeCodeCamp: Functions

**Practice:**

* Function to add a task
* Function to mark task as complete

---

### Day 5 — Modern JavaScript Patterns

**By the end of today, you should be able to:**

* Use arrow functions
* Loop through tasks

**Learn:**

* Arrow functions
* `map`, `filter`, `find`

**Resources:**

* JavaScript Array Methods (MDN)
* YouTube: Array methods explained visually

**Practice:**

* Filter tasks by status
* Map tasks to titles only

---

### Day 6 — Introduction to TypeScript

**By the end of today, you should be able to:**

* Explain what TypeScript adds to JavaScript
* Add types to variables

**Learn:**

* TypeScript basics
* Type annotations

**Resources:**

* TypeScript Handbook: Basic Types
* YouTube: TypeScript for Beginners

**Practice:**

* Rewrite task object using TypeScript
* Add types to function parameters

---

### Day 7 — Tooling Setup (Calm & Simple)

**By the end of today, you should be able to:**

* Run a TypeScript project locally
* Understand what `tsconfig.json` does (at a high level)

**Learn:**

* Node.js basics
* `npm`, `tsc`

**Resources:**

* TypeScript Handbook: Setup
* Vite + React + TypeScript guide

**Practice:**

* Create a basic TS project
* Compile TS → JS

---

## Week 2 — React + TypeScript (Building the Kanban Core)

### Day 8 — React Fundamentals

**By the end of today, you should be able to:**

* Understand components
* Render text to the screen

**Resources:**

* React Official Docs: Main Concepts
* React + TypeScript intro

**Practice:**

* Create `App.tsx`
* Display "My Task Board"

---

### Day 9 — Props & Components

**By the end of today, you should be able to:**

* Pass typed props to components
* Split UI into pieces

**Practice:**

* Create `TaskCard` component
* Pass a typed task object

---

### Day 10 — State Management

**By the end of today, you should be able to:**

* Store tasks in state
* Update UI when state changes

**Learn:**

* `useState`

**Practice:**

* Add task dynamically

---

### Day 11 — Events & User Input

**By the end of today, you should be able to:**

* Handle clicks and form inputs

**Practice:**

* Add task form
* Button click adds task

---

### Day 12 — Kanban Columns

**By the end of today, you should be able to:**

* Render tasks in columns based on status

**Practice:**

* Columns: Todo / Doing / Done

---

### Day 13 — Drag & Drop (Basic)

**By the end of today, you should be able to:**

* Move tasks between columns

**Resources:**

* react-beautiful-dnd (or dnd-kit) docs

---

### Day 14 — UX Basics

**By the end of today, you should be able to:**

* Explain why good UX matters
* Identify friction points

**Learn:**

* Visual hierarchy
* Feedback

**Resources:**

* Refactoring UI (articles)
* UX Collective (Medium)

---

## Week 3 — Polishing, UX Thinking, & Confidence

### Day 15 — UX for Task Management

**By the end of today, you should be able to:**

* Design flows that feel natural

**Practice:**

* Limit clicks
* Auto-focus input

---

### Day 16 — Styling

**By the end of today, you should be able to:**

* Style components cleanly

**Resources:**

* CSS Flexbox Guide
* Tailwind (optional)

---

### Day 17 — Type Safety Deepening

**By the end of today, you should be able to:**

* Use interfaces and union types

---

### Day 18 — Error Handling

**By the end of today, you should be able to:**

* Prevent invalid task states

---

### Day 19 — Persistence

**By the end of today, you should be able to:**

* Save tasks to `localStorage`

---

### Day 20 — MVP Review

**By the end of today, you should be able to:**

* Explain your app architecture
* Explain your TypeScript decisions

---

### Day 21 — Reflection & Next Steps

**By the end of today, you should be able to:**

* Confidently say: "I can build apps in TypeScript"
* Know what to learn next (backend, auth, APIs)

---

## Final Outcome

By completing this plan, you will have:

* A working Kanban task tracker
* Solid JavaScript fundamentals
* Real TypeScript intuition
* Practical UX thinking
* A portfolio-ready project

If you want, next we can:

* Turn this into a **Notion checklist**
* Add **daily time estimates**
* Extend it into a **backend roadmap**
