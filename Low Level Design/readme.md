# Low Level Design (LLD)

Object-oriented design practice — class diagrams, design patterns, and SOLID principles applied to common interview LLD problems.

## 📂 Structure

```
LLD/
├── solid-principles/         # Notes + examples for each SOLID principle
├── design-patterns/
│   ├── creational/           # Factory, Builder, Singleton, Prototype
│   ├── structural/           # Adapter, Decorator, Facade, Proxy
│   └── behavioral/           # Observer, Strategy, State, Command
├── problems/
│   ├── parking-lot/
│   ├── elevator-system/
│   ├── library-management/
│   ├── tic-tac-toe/
│   ├── chess-game/
│   ├── rate-limiter/
│   ├── splitwise/
│   └── bookmyshow/
└── uml-diagrams/              # Class diagrams as images or PlantUML source
```

## 🎯 Standard Approach for Each Problem

1. **Requirements gathering** — clarify functional & non-functional requirements
2. **Identify core entities/classes** — nouns become classes, verbs become methods
3. **Define relationships** — inheritance, composition, aggregation
4. **Apply design patterns** — where they naturally fit (don't force it)
5. **Draw UML class diagram**
6. **Code the core classes** in Java
7. **Discuss extensibility** — how would this scale/change with new requirements?

## 📌 Problem Log

| Problem | Key Patterns Used | Status | Notes |
|---|---|---|---|
| Parking Lot | Strategy, Factory | ⬜ | |
| Elevator System | State, Observer | ⬜ | |
| Rate Limiter | Strategy | ⬜ | |
| Tic-Tac-Toe | — | ⬜ | |

## 🧠 SOLID Principles Quick Reference

- **S**ingle Responsibility
- **O**pen/Closed
- **L**iskov Substitution
- **I**nterface Segregation
- **D**ependency Inversion

## 🔗 Resources

- Refactoring.Guru (design patterns)
- Head First Design Patterns
- GeeksforGeeks LLD problem set

## 📝 Notes

For each problem, keep a short write-up of trade-offs considered (e.g., "why composition over inheritance here") — this is often what differentiates strong LLD interview answers.