[![HTML Check](https://github.com/FomenkoAndrey/git-testing/actions/workflows/HTML5Validator.yml/badge.svg)](https://github.com/FomenkoAndrey/git-testing/actions/workflows/HTML5Validator.yml)
[![EditorConfig](https://github.com/FomenkoAndrey/git-testing/actions/workflows/editorconfig.yml/badge.svg)](https://github.com/FomenkoAndrey/git-testing/actions/workflows/editorconfig.yml)

# GitHub Actions

## HTML CSS validation

Action выполняет HTML + CSS валидацию

## EditorConfig

Тестирование базового кодстайла

Файл **package-lock.json** обязательно должен быть в репозитории для теста EditorConfig

Выполнить тест локально и проверить репозиторий перед отправкой на github можно командой:

`editorconfig-checker -exclude libs`

## GitHub Pages Deploy

Данный action добавляется автоматически GitHub при активации страницы.
