# Алгоритми пошуку (ДЗ)

Готові до тренування? 🤩

Сьогодні ви зможете використати знання алгоритмів пошуку, їхніх переваг і недоліків для розв’язання практичних завдань.

У цьому практичному завданні ви закріпите такі навички:

- досліджувати ефективність алгоритмів шляхом вимірювання їх часу виконання,
- порівнювати різні алгоритми пошуку та використовувати той, який найкраще підходить для вашої задачі, враховуючи їх ефективність,
- вміти програмно реалізувати алгоритм у вигляді окремої програми.

Домашнє завдання буде складатися з трьох незалежних завдань.

## Опис домашнього завдання

### Завдання 1

Додати метод `delete` для видалення пар ключ-значення таблиці `HashTable`, яка реалізована в конспекті.

### Завдання 2

Реалізувати двійковий пошук для відсортованого масиву з дробовими числами. Написана функція для двійкового пошуку повинна повертати кортеж, де першим елементом є кількість ітерацій, потрібних для знаходження елемента. Другим елементом має бути "верхня межа" — це найменший елемент, який є більшим або рівним заданому значенню.

### Завдання 3

Порівняти ефективність алгоритмів пошуку підрядка: Боєра-Мура, Кнута-Морріса-Пратта та Рабіна-Карпа на основі двох текстових файлів (стаття 1, стаття 2). Використовуючи `timeit`, треба виміряти час виконання кожного алгоритму для двох видів підрядків: одного, що дійсно існує в тексті, та іншого — вигаданого (вибір підрядків за вашим бажанням). На основі отриманих даних визначити найшвидший алгоритм для кожного тексту окремо та в цілому.

## Підготовка та завантаження домашнього завдання

1. Створіть публічний репозиторій `goit-algo-hw-05`.
2. Виконайте завдання та відправте його у свій репозиторій.
3. Завантажте робочі файли на свій комп’ютер та прикріпіть їх у `LMS` у форматі `zip`. Назва архіву повинна бути у форматі `ДЗ5_ПІБ`.
4. Прикріпіть посилання на репозиторій `goit-algo-hw-05` та відправте на перевірку.

> [!IMPORTANT]
> ВАЖЛИВО
> Перегляньте Інструкцію щодо завантаження робочого файлу з репозиторію на Github

## Файли для роботи

Текстові файли для виконання завдання 3:

- стаття 1,
- стаття 2.

## Формат здачі

- Прикріплені файли репозиторію у форматі `zip` з назвою `ДЗ5_ПІБ`.
- Посилання на репозиторій.

## Критерії прийняття ДЗ

Прикріплені посилання на репозиторій `goit-algo-hw-05` та безпосередньо самі файли репозиторію у форматі `zip`.

**Завдання 1:**

Код виконується, і метод `delete` видаляє задану пару ключ-значення в таблиці `HashTable`.

**Завдання 2:**

Виконання коду повертає кортеж, де першим елементом є кількість ітерацій, потрібних для знаходження елемента. Другим елементом є "верхня межа" (найменший елемент, який є більшим або рівним заданому значенню).

**Завдання 3:**

Програмно реалізовано алгоритми пошуку підрядка: Боєра-Мура, Кнута-Морріса-Пратта та Рабіна-Карпа.

На основі виконання кожного з трьох алгоритмів визначено найшвидший алгоритм для кожного з двох текстів.

Зроблено висновки щодо швидкостей алгоритмів для кожного тексту окремо та в цілому. Висновки оформлено у вигляді документа формату markdown.

# Висновки

Обидва алгоритми показали різні результати в залежності від типу підрядка.

Для існуючого підрядка, тобто того, що вже міститься в тексті, алгоритм Боєра-Мура виявився більш швидким в обох статтях.

Для вигаданого підрядка, якого немає в тексті, алгоритм Кнута-Морріса-Пратта виявився більш ефективним.

В цілому, для аналізу обох текстів, алгоритм Боєра-Мура виявився кращим. Можливо, це пов'язано зі специфічними особливостями текстів та підрядків, які використовувалися для порівняння.
