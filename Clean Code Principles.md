---
tags:
  - CleanCode
  - Programming
---
## 🏷️ Naming
- Use meaningful names: `getUserById()` > `getData()`
- Avoid unclear abbreviations
- Consistent naming: functions = verbs, variables = nouns
- Boolean names: `isActive`, `hasAccess`

## 🧩 Functions
- Do one thing only
- Keep small (<20 lines)
- Minimize parameters (use objects if needed)
- Avoid unintended side effects

## 📂 Code Structure
- Keep files small
- Group related code logically
- Use consistent indentation/spacing
- Avoid deep nesting (refactor instead)

## 📝 Comments
- Explain *why*, not *what*
- Prefer self-explanatory code over excessive comments

## ⚠️ Error Handling
- Fail early and clearly
- Use meaningful error messages
- Handle or propagate errors properly

## 🔁 DRY (Don’t Repeat Yourself)
- Extract common logic into reusable functions
- Avoid duplicate code

## 🧱 SOLID Principles
1. **Single Responsibility** – one job per module
2. **Open/Closed** – extend, don’t modify
3. **Liskov Substitution** – interchangeable components should work
4. **Interface Segregation** – no unnecessary dependencies
5. **Dependency Inversion** – depend on abstractions

## 🧪 Testing & Maintainability
- Write unit tests for core logic
- Keep functions pure when possible
- Think about the next maintainer

## 🔄 Consistency
- Stick to one style across the project
- Consistency > perfection

## 🧠 YAGNI & KISS
- YAGNI: don’t code features until needed
- KISS: Keep It Simple, Stupid