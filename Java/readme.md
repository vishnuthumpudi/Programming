# Java

Core Java concepts, OOP fundamentals, and Spring Boot practice as part of ongoing certification prep and interview readiness.

## 📂 Structure

```
Java/
├── core-java/          # Syntax, collections, exceptions, streams, generics
├── oop-concepts/       # Classes, inheritance, polymorphism, abstraction, encapsulation
├── multithreading/     # Concurrency, executors, synchronization
├── spring-boot/        # REST APIs, GraphQL, JPA/Hibernate, dependency injection
│   ├── projects/
│   └── notes/
├── design-patterns/    # Creational, structural, behavioral patterns in Java
└── certifications/     # TCS Wings 1, Oracle, or other cert prep notes
```

## 🎯 Current Focus

- [ ] TCS Wings 1 Spring Boot certification
- [ ] Spring Boot + GraphQL projects
- [ ] JPA/Hibernate entity mapping deep dive

## 📌 Topics Log

| Topic | Status | Notes |
|---|---|---|
| OOP fundamentals | ✅ Done | Classes, inheritance, overriding, polymorphism |
| Abstraction | ✅ Done | |
| GraphQL mutations (Spring Boot) | ✅ Done | Debugged `createBook` — missing `@GeneratedValue` |
| Multithreading | ⬜ Not started | |
| Spring Security | ⬜ Not started | |

## 🐛 Bugs & Gotchas

Running list of tricky issues encountered and their root causes — useful for interview "debugging" style questions.

- **Missing `@GeneratedValue` on `@Id` field** → caused ID not to auto-increment in `createBook` mutation.

## 🔗 Resources

- Official Docs: https://spring.io/projects/spring-boot
- Baeldung: https://www.baeldung.com/
- Certification track: TCS Wings 1

## 📝 Notes

Keep code samples runnable where possible. Add a `README.md` inside each subfolder for project-specific setup instructions.