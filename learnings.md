# Getting Started (Ubuntu)

## From Scratch (Installing Node)

1. Follow the [instructions](https://nodejs.org/en/download) from Node.js to install Node on Ubuntu
   - I installed `pnpm` instead of `npm`
2. Visit the [TypeScript website](https://www.typescriptlang.org/download/) to install TypeScript on a per-project basis

---

## 15 Feb 2026: Exploring TypeScript

I'm following the tutorial: [TypeScript Tooling in 5 minutes](https://www.typescriptlang.org/docs/handbook/typescript-tooling-in-5-minutes.html)

### Project Structure

My TypeScript structure is very barebone. Truncated folder structure:

```
personal-task-tracker-typescript/
├── node_modules/
├── greeter.ts
├── greeter.js
├── greeter_interface.ts
├── greeter_interface.js
├── greeter_class.ts
├── greeter_class.js
├── package.json
└── pnpm-lock.yaml
```

### Compiling TypeScript Files

Use this command to compile TypeScript to JavaScript:

```bash
npx tsc greeter.ts
```

### Running the JavaScript File

Use this command to execute the compiled JavaScript:

```bash
node greeter.js
```

---

### Key Learnings

**Basic TypeScript Concepts:**
- `greeter.ts` and `greeter_interface.ts` are fairly easy to follow and demonstrate fundamental TypeScript features
- `greeter_class.ts` is where the JavaScript vibe kicks in and things get interesting

**Structural Typing (Duck Typing):**
- TypeScript uses structural typing rather than nominal typing
- I made no explicit connection between the `Student` class and `Person` interface, but TypeScript automatically recognizes that `Student` has similar properties as `Person`
- This is called "duck typing" - if it walks like a duck and quacks like a duck, TypeScript treats it as a duck
- Everything works seamlessly because the structure matches, not because of explicit inheritance or implementation

---

### Error Encountered

Compiling the TypeScript file creates an error in `greeter.ts`:

**Error:** `Duplicate function implementation`

**Cause:** TypeScript detects both the source file (`greeter.ts`) and its compiled output (`greeter.js`) in the same directory. Without a `tsconfig.json` to exclude JavaScript files, TypeScript treats both files as part of the project, resulting in duplicate function definitions.

### Solution

#### Short-term Solution
Remove the compiled `greeter.js` file:

```bash
rm greeter.js
```

This resolves the immediate error, and the file can be regenerated when needed.

#### Long-term Solution
Create a `tsconfig.json` file to properly configure TypeScript and exclude JavaScript files from compilation.