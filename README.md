# 9 класс Кыргызстан - учебная карта

Статичный сайт для GitHub Pages: материалы 9 класса, мини-тесты и отдельная страница подготовки к госэкзамену по истории Кыргызстана. Экзаменационные билеты поддерживают русский и кыргызский язык.

## Файлы сайта

- `index.html` - главная страница с предметами, темами и тестами.
- `history-exam.html` - подготовка к госэкзамену по истории Кыргызстана с переключателем `RU / KG`.
- `ticket-answer.html` - отдельная страница полного ответа на выбранный билет.
- `assets/` - локальные изображения и иконки.
- `manifest.webmanifest` - поддержка установки сайта на телефон как приложение.
- `.nojekyll` - отключает обработку Jekyll на GitHub Pages.

## Публикация через GitHub

1. Создай новый репозиторий на GitHub.
2. Загрузи в него все файлы из этой папки.
3. Открой `Settings` -> `Pages`.
4. В `Build and deployment` выбери `Deploy from a branch`.
5. В `Branch` выбери `main` и папку `/(root)`, затем нажми `Save`.
6. Через 1-3 минуты сайт будет доступен по адресу:

```text
https://USERNAME.github.io/REPOSITORY/
```

## Публикация через команды Git

Замени `USERNAME` и `REPOSITORY` на свои данные:

```powershell
git init
git add .
git commit -m "Add grade 9 study site"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

После этого включи GitHub Pages в `Settings` -> `Pages` -> `Deploy from a branch` -> `main` -> `/(root)`.
