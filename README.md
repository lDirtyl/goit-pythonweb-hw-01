# goit-pythonweb-hw-01

## Завдання 1. Патерн фабрика
- Створити абстрактний базовий клас Vehicle з методом start_engine().
- Змінити класи Car та Motorcycle, щоб вони успадковувались від Vehicle.
- Створити абстрактний клас VehicleFactory з методами create_car() та create_motorcycle().
- Реалізувати два класи фабрики: USVehicleFactory та EUVehicleFactory. Ці фабрики повинні створювати автомобілі та мотоцикли з позначкою регіону наприклад, Ford Mustang (US Spec) відповідно для США.
- Змініть початковий код так, щоб він використовував фабрики для створення транспортних засобів.

## Завдання 2. SOLID
- Щоб виконати принцип єдиної відповідальності (SRP), створіть клас Book, який відповідатиме за зберігання інформації про книгу.
- Щоб забезпечити принцип відкритості/закритості (OCP), зробіть так, щоб клас Library міг бути розширений для нової функціональності без зміни його коду.
- Щоб виконати принцип підстанови Лісков (LSP), переконайтеся, що будь-який клас, який наслідує інтерфейс LibraryInterface, може замінити клас Library без порушення роботи програми.
- Щоб виконати принцип розділення інтерфейсів (ISP), використовуйте інтерфейс LibraryInterface для чіткої специфікації методів, які необхідні для роботи з бібліотекою library.
- Щоб виконати принцип інверсії залежностей (DIP), зробіть так, щоб класи вищого рівня, такі як LibraryManager, залежали від абстракцій (інтерфейсів), а не від конкретних реалізацій класів.