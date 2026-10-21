# Cafe Documentation Project
Учебный проект документации для системы заказов университетского кафе, собранный через Sphinx.

## Состав проекта
| Файл | Ответственный |
|---|---|
| `docs/user-guide.md` | Студент А |
| `docs/admin-guide.md` | Студент Б |
| `docs/conf.py` | Конфигурация сборки Sphinx |
| `docs/index.md` | Навигационная страница |

## Сборка сайта
```bash
pip install sphinx myst-parser
sphinx-build -b html docs/ site/ -W
```
После сборки статический сайт открывается из `site/index.html`.

## Требования
- Python 3.11+
- Все секреты в документации заменены безопасными заглушками
- Относительные пути к изображениям в `docs/images/` сохранены
