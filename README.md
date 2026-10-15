# Лабораторная работа №2 — Git

Простой учебный сайт для выполнения заданий по созданию репозитория, коммитов и тегов.

## Как открыть
1. Распакуйте ZIP-архив.
2. Откройте папку `lab2_git_project` в Visual Studio Code.
3. Откройте `index.html` в браузере. При загрузке появится приветственное окно.

## Git: настройка имени и почты
В терминале VS Code выполните команды, заменив значения на свои:

```bash
git config --global user.name "Ваше имя"
git config --global user.email "ваш-email@example.com"
git config --global core.editor "code --wait"
```

Репозиторий в архиве уже инициализирован, содержит историю коммитов и аннотированные теги `v1.0` и `v2.0`.

## Полезные команды
```bash
git status
git log --oneline --decorate
git tag -n
```
