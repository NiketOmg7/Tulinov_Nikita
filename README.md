# AccessEvent

Инклюзивная платформа мероприятий с акцентом на доступность для людей с нарушениями слуха.

## О проекте

AccessEvent — веб-платформа, позволяющая организаторам создавать мероприятия, а участникам — регистрироваться на них. Особое внимание уделено визуальным уведомлениям, цветовой индикации статусов и текстовому чату, чтобы люди с нарушениями слуха могли полноценно участвовать в мероприятиях без необходимости слышать.

## Структура репозитория

access-event/
├── README.md
├── .gitignore
├── docs/
│   ├── analysis.md
│   ├── requirements.md
│   ├── stakeholders.md
│   └── tz.md
├── .github/
│   └── workflows/
│       └── day1-check.yml
├── src/
└── tests/

## Документация

- [Анализ предметной области](docs/analysis.md)
- [Требования и User Stories](docs/requirements.md)
- [Стейкхолдеры](docs/stakeholders.md)
- [Техническое задание](docs/tz.md)

## Технологический стек

- Python 3.10+, Flask 2.3+
- PostgreSQL 14+, SQLAlchemy
- Jinja2, pytest
- GitHub Actions + GHCR, Docker

## Лицензия

MIT