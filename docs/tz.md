# Техническое задание: AccessEvent

## 1. Назначение и цели
AccessEvent — веб-платформа мероприятий для людей с нарушениями слуха.

## 2. Описание предметной области
Сущности: Event, Participant, Organizer, Registration, Notification, Review, Category.

## 3. Требования к функциям
FR-01 ... FR-18 (см. requirements.md)

## 4. Требования к качеству
NFR-01 ... NFR-10 (см. requirements.md)

## 5. Требования к интерфейсу
- Адаптивный дизайн (mobile-first)
- WCAG 2.1 AA
- Цветовая индикация
- Шрифт 16px+

## 6. Требования к данным
- PostgreSQL 14+
- SQLAlchemy
- 7+ таблиц
- bcrypt

## 7. Технологический стек
Python 3.10+, Flask 2.3+, PostgreSQL 14+, Jinja2, pytest, Docker, GHCR.

## 8. Ограничения и допущения
- Только веб
- Без платежей
- Без видеоконференций
- Срок: 6 дней
