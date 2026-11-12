# demoqa-practice-form

## Что проверяет тест

Тест `PracticeFormTests` заполняет все поля формы [Practice Form](https://demoqa.com/automation-practice-form) и проверяет данные в окне после отправки:

| Поле | Как заполняется |
|------|-----------------|
| Имя, фамилия, email, телефон | текстовые поля |
| Пол | радиокнопка |
| Дата рождения | календарь (месяц, год, день) |
| Предметы | автодополнение |
| Хобби | чекбокс |
| Картинка | загрузка файла из `src/test/resources` |
| Адрес | текстовое поле |
| Штат и город | выпадающие списки |

## Технологии

- Java 17
- Gradle
- JUnit 5
- Selenide

## Требования

- JDK 17
- Браузер Chrome

## Как запустить

```bash
git clone git@github.com:savelij-mihalev/demoqa-practice-form.git
cd demoqa-practice-form
./gradlew test
```

## Автор

[savelij-mihalev](https://github.com/savelij-mihalev)