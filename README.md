## Описание
Heroes Battle Simulator — это проект, имитирующий сражения между героями с использованием различных алгоритмов и стратегий. 
Этот симулятор предназначен для анализа тактических решений и проверки эффективности различных стратегий боя.
## Установка и запуск
### Требования
- Java 11+
- Maven (если нужно собирать проект из исходников)
### Сборка проекта
mvn clean package
### Запуск симуляции боя
java -jar jars/MyHeroesBattle-1.0.0.jar

## Основные классы
### Main.java
Точка входа в программу. Запускает симуляцию боя и вызывает основные методы для анализа стратегии.

### SimulateBattleImpl.java
Реализует логику сражения между героями, учитывая их характеристики, способности и поведение.

### SuitableForAttackUnitsFinderImpl.java
Определяет, какие юниты подходят для атаки в зависимости от ситуации на поле боя.

### UnitTargetPathFinderImpl.java
Рассчитывает оптимальные пути перемещения юнитов к целям.

