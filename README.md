# qa-portfolio

Практическое QA-портфолио: ручное тестирование, API, SQL и базовая автоматизация (Java + Python).
Цель — показать навыки через артефакты, приближенные к реальной работе.

## Структура
- `manual/` — чек-листы, тест-кейсы, баг-репорты
- `api/` — Postman collections + environments
- `sql/` — SQL задачи и решения (скрипты)
- `automation-java/` — Maven проект (JUnit 5)
- `automation-python/` — pytest проект

## Как запускать

### automation-python
```bash
cd automation-python
python -m venv .venv
# Windows:
.\.venv\Scripts\activate
pip install -r requirements.txt
pytest -q
