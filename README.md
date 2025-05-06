# Kotlin/Android Studio Statistics Calculator

This project is a **Statistics Calculator** developed using **Kotlin** in **Android Studio**. It demonstrates key concepts in mobile development, offering a user-friendly interface for performing various statistical computations.

Developed as part of the **Mobile Development** course in the **Computer Science** program at the **University of Wisconsin–Eau Claire**, this project gave students hands-on experience with:

- Kotlin programming
- Android app development
- Mobile UI design
- Functionality integration
- Kotlin’s advanced language features

---

## ❗ Invalid Input Rules

| Input Pattern | Example     | Description                                                                 |
|---------------|-------------|-----------------------------------------------------------------------------|
| `#√#`         | `2√16`      | Square roots must be applied separately from other operations.              |
| `#Xtr(%)`     | `√Xtr(%)`, `4Xtr(%)` | The `Xtr(%)` button must be used in isolation, not with other operators.  |
| `#^#^#`       | `2^3^2`     | Nested exponents are not supported.                                        |
| `√√#`         | `√√16`      | Nested square roots are not supported.                                     |
| `{√, #^}`     | `{√4, 2^5}` | Exponents and square roots are not allowed in dataset input for statistics.|

---

## 🧮 Calculator Functions

| Button   | Input | Function                                                                 |
|----------|-------|--------------------------------------------------------------------------|
| `Stat`   |       | Calculates **mean**, **max**, **min**, **median**, **trimmed mean**, and **sum** of dataset values. |
| `^`      | `#`   | Raises the previous number to the power of the following number.         |
| `√`      | `#`   | Computes the square root of the following number.                        |
| `Xtr(%)` | `#`   | Calculates a **trimmed mean** using the given percentage.                |
| `-`      | `#`   | Supports negative number input and operations.                           |

---

This project showcases a robust example of mobile-first, statistics-focused application development with Kotlin and Android Studio.
