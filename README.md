# 📌 TypeScript Assignment: Core Concepts

## 🚀 Objective

This assignment covers essential TypeScript topics such as **async/await, callbacks, promises, objects, classes, access modifiers, enums, inheritance, interfaces, and types**.

## 📁 File Structure

```bash
typescript-homework/
│── src/
│   │── asyncAwait.ts
│   │── callback.ts
│   │── promise.ts
│   │── objects.ts
│   │── class.ts
│   │── accessModifiers.ts
│   │── enum.ts
│   │── inheritancePolymorphism.ts
│   │── interface.ts
│   │── type.ts
│── README.md
│── package.json
│── tsconfig.json
```

## 📜 Assignment Tasks

### 1️⃣ `asyncAwait.ts` - Async/Await, Callback, and Promise

**Task:**
Create a function that fetches data from an API using `async/await`, processes it with a callback function, and returns a promise.

**Instructions:**

- Use `fetch` API to get data from `https://jsonplaceholder.typicode.com/posts/1`
- Utilize `async/await` syntax for the asynchronous operation
- Implement a callback function that processes the fetched data
- Return a promise that resolves once processing is complete
- Handle errors properly

---

### 2️⃣ `objects.ts` - Objects and Access Modifiers

**Task:**
Define a `User` object with appropriate access modifiers and print its properties securely.

**Instructions:**

- Create a class `User` with `public name`, `private password`, and `protected role`
- Implement a method `getUserInfo()` that returns only safe information
- Instantiate the class and attempt to access its properties

---

### 3️⃣ `class.ts` - Class, Inheritance & Polymorphism

**Task:**
Create a base `Vehicle` class and extend it with `Car` and `Bike` classes.

**Instructions:**

- Define a class `Vehicle` with properties: `make`, `model`, and `year`
- Extend it with `Car` and `Bike`, adding unique properties/methods
- Implement polymorphic behavior with a method `move()`

---

### 4️⃣ `enum.ts` - Enum

**Task:**
Define an enum for different user roles and implement a function using it.

**Instructions:**

- Create an enum `UserRole` with values: `Admin`, `Editor`, `Viewer`
- Implement a function `getPermissions(role: UserRole): string[]` to return role-based permissions

---

### 5️⃣ `interface.ts` & `type.ts` - Interface and Type

**Task:**
Define an interface for `Person` and a type alias for `Point`, and use them in functions.

**Instructions:**

- Create an interface `Person` with properties: `name`, `age`, `email`
- Implement a function `greet(person: Person): string`
- Define a type `Point` with properties: `x` and `y`
- Implement a function `distance(p1: Point, p2: Point): number`

---

## 📤 Assignment Submission

1. **GitHub Repository:**

   - Upload your assignment to the **GitHub Classroom** repository.
   - Use `git add .`, `git commit -m "Core Concepts Assignment"`, and `git push origin main`.

2. **Submission Deadline:**

   - 10.03.2025 12.00

3. **Evaluation Criteria:**
   - **Is type safety ensured?**
   - **Are function names properly structured?**
   - **Do all scripts execute correctly?**

By completing this assignment, you will strengthen your understanding of TypeScript’s core concepts. Good luck! 🚀
