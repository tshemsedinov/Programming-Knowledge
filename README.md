# Essential Knowledge for Programmers

Here's what I suggest learning and practicing. These principles can become cargo cults if not properly rethought. Understanding these concepts can't just be extracted from a box (or book) and placed into your maind. It varies greatly for different languages and platforms. Blindly transferring knowledge and practices from C++ or Java to JavaScript and C# results in dead ceremonies. However, they can be revived through practice, tied to realities, and rethought to avoid becoming monstrous and horrors.

- 📂 Module Systems, Dependency Injection (DI), and Inversion of Control (IoC): skills in building application structure, including legendary folder architecture, layered and onion architecture, hexagonal and pipeline – you can't take them all, they are contradictory techniques; you need to choose and comprehend.
- 📦 Decomposition of Abstractions and GRASP Principles: Information Expert, SOLID: Single Responsibility Principle (SRP) and Interface Segregation Principle (ISP), Law of Demeter (LoD).
- 🧩 Contract Programming and Modeling with Schemas: Databases, data structures, API contracts, module contracts, forms, reports, subsystems, layers – a uniform approach is needed for contracts.
- 🔮 Principles of Isolation and SoC (Separation of Concerns): Isolate everything that needs to change independently, using interfaces and contracts, patterns (like facade and adapter), processes and threads, isolated execution contexts.
- 🔗 Coupling and Cohesion: Managing complexity, hiding complexity behind abstractions and facades; semantic complexity is much more important than cyclomatic.
- 🙈 All-agnostic approaches: Platform-agnostic, Framework-agnostic, Protocol-agnostic, etc. – code should not change when moving to new framework, for example, endpoint handlers should not change when moving between frameworks or even protocols (of course, this shouldn't be done blindly).
- 🏛️ Clean Architecture and Layered Architecture: there can be one layer, two or three; don't copy project templates, you should design abstraction layers.
- ✍ Creating Domain-Specific Languages (DSL): domain code complexity often leads us to the need to simplify syntax drastically; programming language, whatever it is, stops fitting the domain – we need to make a leap in expressiveness, another syntax, and semantics. Languages like LISP and JS can be their own DSLs, but not always.
- 👷🏻‍♂️ Separation of Applied and System Code: these are different specialties with minimal knowledge overlap. For example, in JavaScript, an applied programmer can think of variables as scalar values and references, while a system programmer must think about identifiers, heap, stack, register variables, object forms, optimization features, and garbage collection – this could be a 10-hour lecture with some things forgotten or inaccuracies creeping in.
- 🌟 Multi-Paradigm Programming: don't get stuck on one paradigm, whether functional, object-oriented, actor model, state machine programming, reactive, or prototype-based – choose from a wide spectrum of ideas; procedural programming often gives surprisingly good results, try it.

### Follow Me

- YouTube Channel: https://youtube.com/@TimurShemsedinov
- GitHub Repository: https://github.com/tshemsedinov
- Telegram Channel: https://t.me/HowProgrammingWorks
