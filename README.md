# lab9-playwright-ci

Лабораторная работа №9: запуск Playwright/pytest тестов в GitHub Actions.

Файлы ЛР №8 (`delivery.html`, `conftest.py`, `test_delivery_ui.py`) находятся в корне репозитория.

## CI

Workflow `.github/workflows/ui-tests.yml` запускается при push, pull request и вручную.
Он выполняет 12 UI-тестов и сохраняет артефакт `ui-test-results` (`report.xml`, `server.log`, `test-results/`).
