# Password-Generator-Project

## Опис проекту
**Password-Generator-Project** — це Maven-проєкт, який забезпечує генерацію випадкових паролів із заданою довжиною.

### Основні класи
Цей проект складається з двох частин:

1. Генератор паролів – клас PasswordGenerator, який генерує випадкові паролі заданої довжини.

2. Демонстрація використання – другий Maven-проект, який підключає артефакт генератора паролів та використовує його для створення паролів.

### Як працює програма
1. Клас `PasswordGenerator` реалізує метод `generatePassword(int length)`, який генерує випадковий пароль із символів: великих і малих літер, цифр та спеціальних символів.
2. Основний клас `Main` створює об'єкт класу `PasswordGenerator` та викликає метод `generatePassword`, виводячи результат у консоль.

### Вимоги до системи
- Java 8 або вище
- Apache Maven 3.6.0 або вище
- Будь-яке середовище розробки для Java (VSCode, IntelliJ IDEA, Eclipse)
