# Lddom
Raw Project, need more changes, free to creative, have modding system in JavaScript, welcome to try. >_&lt;

# lddom_ttribute (dDOM Visual Code & Addon Engine)

Интерактивный браузерный визуализатор графа кода (`ddom_graph.js`) и модульный движок аддонов без серверных зависимостей.

## Что внутри
* `ddom_viewer_etl.html` — лёгкий эталонный каркас (~500 LoC) для быстрого старта и изучения архитектуры.
* `ddom_viewer_now.html` — расширенная рабочая среда с поддержкой кастомных фонов, иконок и модулей.
* `plugin/` — директория аддонов (включая двухколоночный менеджер приоритетов слоёв `ApplyHowMinecraft`).
* `OLauncher/` — инструменты запуска и связки с локальным сервером.

## Быстрый старт
1. Откройте `ddom_viewer_now.html` в любом современном браузере.
2. Нажмите `[A]` («Аддоны & Списки»), чтобы управлять слоями и подключать `.js` / `.zip` модули.
