# Geometric Lib

[![Python](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/)

Библиотека на **Python** для вычисления площади и периметра геометрических фигур.

## Возможности

- **Круг** — площадь и длина окружности
- **Квадрат** — площадь и периметр
- **Прямоугольник** — площадь и периметр
- **Треугольник** — площадь и периметр

## Установка

```bash
git clone https://github.com/YurKP/my_geometric_lib.git
cd my_geometric_lib
```

## Использование

Пример для круга:

```python
from circle import area, perimeter

print(area(5))        # 78.53981633974483
print(perimeter(5))   # 31.41592653589793
```

Пример для прямоугольника:

```python
from rectangle import area, perimeter

print(area(3, 4))         # 12
print(perimeter(3, 4))    # 14
```

## Структура проекта

| Файл | Описание |
|---|---|
| `circle.py` | Функции для круга |
| `square.py` | Функции для квадрата |
| `rectangle.py` | Функции для прямоугольника |
| `triangle.py` | Функции для треугольника |
| `docs/README.md` | Подробная документация |

## Документация

Подробное описание всех функций с примерами вызова — в [docs/README.md](docs/README.md).