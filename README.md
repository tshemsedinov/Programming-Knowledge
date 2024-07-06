# Найважливіші знання для програміста

Ось що я пропоную вчити... навіть швидше практикуватися, тому що всі ці знання мають тенденцію ставати карго культом. Проблема в тому, що розуміння цих принципів і підходів не може бути вийнято з коробки (або книги) і просто вкладено вам у мозок. Для різних мов та платформ воно дуже відрізняється. Якщо бездумно перенести знання та практики з C++ або Java у JavaScript та C#, то це будуть просто мертві церемонії. Але їх можна оживити практикою, прив'язати до реалій, переосмислити, щоб вони не перетворювалися на монстрів та застиглий жах.

- 📂 Системи модульності, впровадження залежностей (DI - dependency injection) та інверсія управління (IoC - Inversion of Control), навички побудови структури додатків: легендарна архітектура папочок, багатошарова і цибульна архітектури, гексагональна та pipeline - не можна всі їх взяти, це будуть суперечливі прийоми, потрібно вибрати та осмислити.
- 📦 Декомпозиція абстракцій та принципи GRASP: Information Expert, SOLID: принцип єдиної відповідальності (SRP) та поділу інтерфейсів (ISP), закон Деметри (LoD).
- 🧩 Контрактне програмування та моделювання всього через схеми (schemas): бази даних, структури даних, контракти API, контракти модулів, форми, звіти, підсистеми, потрібен однорідний підхід.
- 🔮 Принципи ізоляції та SoC (Separation of concerns) - ізолювати потрібно все, що має змінюватися незалежно, а спосіб ізоляції - інтерфейси та контракти, патерни (як фасад та адаптер), процеси та потоки, ізольовані контексти виконання.
- 🔗 Coupling (зачеплення) та Cohesion (зв'язування) - управління складністю, приховування складності за абстракціями та фасадами, семантична складність набагато важливіша, ніж цикломатична.
- 🙈 Agnostic підходи: Platform-agnostic, Framework-agnostic, Protocol-agnostic і т.і.: код не повинен змінюватися при перенесенні між фреймворками, наприклад, обробники ендпоінтів не повинні змінюватися при перенесенні між фреймворками і навіть протоколами. Звісно, ​​не треба цим зловживати.
- 🏛️ Чиста архітектура (Clean) та цибулева архітектура (Onion та Layered) – шарі може бути і один, не потрібно завжди робити їх два чи три, не потрібно бездомно копіювати шаблон проекту, шари абстракцій потрібно проектувати.
- ✍ Створення доменних мов domain-specific language (DSL) - складність доменної зони коду, при розвитку проекту зазвичай призводить нас до необхідності різко спростити синтаксис і ось наша мова, якою б не була, перестає підходити, потрібно зробити стрибок у виразності, інший синтаксис та семантика. Ну зрозуміло, що такі мови, як LISP та JS можуть самі собі бути DSL, але не завжди.
- 👷🏻‍♂️ Поділ прикладного та системного коду (це різні спеціальності) - перетин знань мінімальний. Наприклад, у JavaScript, прикладному програмісту можна думати про змінні, як про скалярне значення або посилання, а системний програміст вже повинен думати про ідентифікатор та його зв'язування, кучу, стек, регістрові змінні, форму об'єктів, особливості оптимізації та збирання сміття, тут можна на 10 годин лекцію затіяти і ще щось забудеш чи неточність вкрадеться.
- 🌟 Мультипарадигменне програмування: зациклюватися не можна ні на чому, ні на функціональному чи об'єктно-орієнтованому програмуванні, ні на моделі акторів та автоматному програмуванні, реактивному та прототипному, потрібно вибирати з широкого спектру ідей, до речі, дуже часто звичайне процедурне дає несподівано гарний результат, спробуйте.

### Посилання

- 👉 Ютюб, де я роблю лекції: https://youtube.com/@TimurShemsedinov
- 👉 Мій гітхаб: https://github.com/tshemsedinov
- 👉 Один з каналів в тг: https://t.me/HowProgrammingWorks
