# 🧱 SOLID Principles in Object-Oriented Design

**SOLID** is a set of five design principles intended to make software systems easier to understand, more flexible, and maintainable. These principles are foundational in object-oriented programming and are widely used in designing clean architecture.

---

## 1. 🔹 Single Responsibility Principle (SRP)

> A class should have one and only one reason to change.

### 🔍 Explanation

Each class should be focused on a single task or responsibility. Mixing multiple responsibilities into a single class makes code harder to modify, test, and understand.

### 🧠 Analogy

A **coffee machine** is designed only to make coffee — not to toast bread or wash dishes. Similarly, in software, each class should serve one distinct purpose.

### 📌 Key Point

- Reduces coupling
- Easier to test
- Easier to maintain

---

## 2. 🔸 Open/Closed Principle (OCP)

> Software entities should be open for extension but closed for modification.

### 🔍 Explanation

This means you should be able to add new functionality to a class without altering its existing code. Instead of changing code that already works, extend it.

### 🧠 Analogy

A **plugin system** (like adding extensions to a browser) lets you add features without rewriting the core browser code.

### 📌 Key Point

- Protects existing code from breaking
- Encourages modularity and reuse
- Promotes inheritance and polymorphism

---

## 3. 🔹 Liskov Substitution Principle (LSP)

> Subclasses should be substitutable for their base classes without altering the correctness of the program.

### 🔍 Explanation

If class B is a subclass of class A, you should be able to use B anywhere you use A without unexpected behavior or errors. The subclass must respect the behavior expected from the parent class.

### 🧠 Analogy

A **bird** is expected to fly. But if you replace a bird with a **penguin** (a subclass that can't fly), things break. So penguins shouldn't be subclasses of flying birds.

### 📌 Key Point

- Promotes correct use of inheritance
- Helps prevent unexpected behavior
- Encourages behavioral consistency

---

## 4. 🔸 Interface Segregation Principle (ISP)

> No client should be forced to depend on methods it does not use.

### 🔍 Explanation

Large, multipurpose interfaces should be split into smaller, more specific ones. This prevents implementing classes from being burdened with irrelevant methods.

### 🧠 Analogy

A **simple printer** shouldn't be forced to support fax or scanning functions just because it implements a large "MultiFunctionDevice" interface.

### 📌 Key Point

- Makes interfaces more focused
- Reduces implementation burden
- Encourages composition over fat interfaces

---

## 5. 🔹 Dependency Inversion Principle (DIP)

> High-level modules should not depend on low-level modules. Both should depend on abstractions.

### 🔍 Explanation

Instead of tightly coupling a high-level class to a specific low-level class, both should rely on abstract interfaces. This decouples components and makes the system more flexible and testable.

### 🧠 Analogy

A **universal power adapter** doesn't care if it’s connected to a wall socket, car charger, or power bank — it just uses the abstract standard of a plug.

### 📌 Key Point

- Reduces tight coupling
- Improves code flexibility
- Makes unit testing easier

---

## ✅ Summary Table

| Principle | Definition                                     | Benefit                     | Analogy                                  |
| --------- | ---------------------------------------------- | --------------------------- | ---------------------------------------- |
| **SRP**   | One class, one responsibility                  | Cleaner, more focused code  | A coffee machine shouldn't wash dishes   |
| **OCP**   | Open for extension, closed for modification    | Easy feature addition       | Browser extensions                       |
| **LSP**   | Subtypes should behave like their parent types | Predictable subclassing     | Penguins shouldn’t subclass flying birds |
| **ISP**   | Only implement what’s needed                   | No unnecessary dependencies | Printers shouldn’t be forced to scan     |
| **DIP**   | Depend on abstractions                         | Decoupled, testable code    | Universal charger works with any source  |

---

> Mastering SOLID is a big step toward writing clean, scalable, and professional-grade software. These principles help reduce bugs, speed up development, and keep code maintainable in the long run.
