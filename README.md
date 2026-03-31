# Island project

- `main/java/island` — основной код
- `test/island` — тесты


## Как запустить


```bash
mvn test
```
## Структура проекта

```
island_project/
├── pom.xml
├── README.md
├── main/
│   └── java/
│       └── island/
│           ├── App.java
│           ├── Command.java
│           ├── CommandParser.java
│           ├── Direction.java
│           ├── Island.java
│           ├── Main.java
│           ├── Navigator.java
│           └── Position.java
└── test/
    └── island/
        ├── CommandParserTest.java - тесты на разбор команд.
        ├── IslandFunctionalTest.java - общий тест всей программы
        ├── IslandTest.java - тесты самого острова
        ├── NavigatorTest.java - тесты на перемещение по острову
        ├── PositionTest.java - тесты для координат
```

