# Android Interview Questions

Welcome to the **android-interview-questions** repository! This collection of categorized questions will help you prepare for interviews as an Android Developer.

## Table of Contents

* [Object-Oriented Programming](#object-oriented-programming)
* [Kotlin Language](#kotlin-language)
* [Android Framework & SDK](#android-framework--sdk)
* [Coroutines & Concurrency](#coroutines--concurrency)
* [Architectures & Design Patterns](#architectures--design-patterns)
* [Data & Storage](#data--storage)
* [Build, Dependencies & Tools](#build-dependencies--tools)
* [Testing & Code Quality](#testing--code-quality)
* [Security](#security)
* [Accessibility & Miscellaneous](#accessibility--miscellaneous)

---

## Object-Oriented Programming

* What is the difference between **method overloading** and **method overriding**?
* How do **abstract classes** differ from **interfaces**?
* What happens when multiple interfaces declare the same method signature?
* If several interfaces provide default implementations, what issues can arise when implementing them together?
* How can you achieve multiple inheritance in Java/Kotlin?
* Explain **polymorphism** and **inheritance** with examples.

## Kotlin Language

* What does the `reified` keyword do in generics?
* Compare `let`, `run`, `with`, `also`, and `apply`—when would you use each?
* How do you implement a **singleton** in Kotlin? Is your solution thread-safe?
* What is the difference between `const val` and `val`?
* Describe Kotlin’s **visibility modifiers** and explain `lateinit` vs `lazy`.
* What are `inline` and `crossinline` functions?
* How do you call a `suspend` function? What characteristics do `suspend` functions have?

## Android Framework & SDK

* What is a `Context`, and what types of `Context` exist?
* Differentiate between `Activity`, `Fragment`, and `Service`.
* Can a fragment exist without a parent activity? In what scenario?
* What is an **ANR**, and after how many seconds does the system trigger it?
* How does Android protect an app’s data from unauthorized access by other apps?
* What is **Doze Mode**, and how does it affect background tasks and services?
* How does Android handle configuration changes (e.g., screen rotation), and how do you preserve UI state?
* Is it possible for an activity’s `onDestroy()` to run without `onPause()` or `onStop()` first? Explain.

## Coroutines & Concurrency

* Define a **coroutine** and explain how it works.
* What is a **CoroutineContext**, and what contexts are commonly used?
* How do you start a coroutine? Compare error handling in `launch` vs. `async`.
* If a child coroutine fails inside a `launch` block, what happens to its siblings?
* How do you cancel a coroutine, and what must you do to ensure long-running tasks respect cancellation?
* Why is `synchronized` not recommended in coroutines? Can you use a **Mutex** instead?
* What is a **race condition**, and how can you prevent it?
* What concurrency utilities are available on Android?

## Architectures & Design Patterns

* Compare **MVVM** and **MVP**. What other architectural patterns do you know?
* How would you integrate **Jetpack Compose** into an existing XML-based application?
* What responsibilities does the **ViewModel** have in MVVM?
* What is **ViewModelScope**, and why is it useful when working with coroutines?
* How do you implement **dependency injection**? Compare Koin and Hilt.
* What is **Clean Architecture**, and how does it structure application layers?
* How do you configure **build variants** vs. **product flavors** in Gradle?

## Data & Storage

* Compare **Room**, **DataStore**, and **SharedPreferences**.
* What is a **database migration**, and how would you change a column’s type (e.g., `String` → `Int`) in a released app?
* How do you serialize data between screens? Compare `Serializable` and `Parcelable`.
* Why does `Serializable` work even though it has no methods?
* How would you store **sensitive data** locally to ensure security?
* Explain the differences between **hot** and **cold** streams. Compare `Flow`, `StateFlow`, and `SharedFlow`.
* What is **back pressure** in RxJava, and how do you handle it?

## Build, Dependencies & Tools

* How can you verify a library doesn’t depend on outdated versions of other artifacts if you don’t have source access?
* Why can’t a Kotlin library module depend on an Android Library module?
* Compare **R8** and **ProGuard**. Why are they necessary?
* What is **linting**, and which lint tools have you used?
* How do you configure **build variants** and **flavors** in Gradle?

## Testing & Code Quality

* How do you write **unit tests** for ViewModels and coroutines? What should you cover?
* What makes a test reliable and maintainable?
* How do you detect and fix a **memory leak**? Provide an example.
* How do you ensure a **Composable** is stable and doesn’t cause unnecessary recompositions?
* Which tools do you use for performance monitoring and leak detection (e.g., LeakCanary)?

## Security

* How do you protect an Android app from **decompilation** and unauthorized code access?
* How do you encrypt and securely store sensitive data on the device?
* How do ProGuard/R8 optimizations contribute to app security?

## Accessibility & Miscellaneous

* How do you add accessibility content descriptions (TalkBack) for a `Button` in Compose?
* What constitutes a **side effect** in Compose, and how do you manage them?
* What benefits do **data classes** provide in Kotlin? Which methods are automatically generated?
* Can two apps with the same package name be installed on the same device?
* What is your favorite Kotlin feature, and why?
* How do you ensure your code can’t be improved further? What does that mean during code reviews?

---

*Good luck with your interview preparation!*
