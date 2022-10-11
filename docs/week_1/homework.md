# домашнее задание

!!! info "Автор(ы)"

    - [Никита Соболев](https://github.com/sobolevn)

## Задачи по ДЗ на первую неделю

- Сгенерировать `.pyi` stabs для проекта [boltons](https://github.com/mahmoud/boltons)
    - [x] так как там много всего, следует сконцентрироваться на одном [файле](https://github.com/mahmoud/boltons/blob/master/boltons/dictutils.py)
- Можно воспользоваться `stubgen` для создания изначального скелета, можно полностью ручками
  - Для проверки корректности, запускаем:
    - [x] mypy
    - [x] stubtest
    - [x] flake8 + flake8-pyi
    - [x] isort и black
- При оформлении пакета смотрите [PEP-561](https://peps.python.org/pep-0561/)
