# Quadratic Equations Solver

Библиотека для решения квадратных уравнений.

# Использование

Пример использования в интерпретаторе Python 3.5: 
```
$ python3
Python 3.5.3 (default, Jan 19 2017, 14:11:04) 
[GCC 6.3.0 20170118] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import quadratic_equation
>>> quadratic_equation.get_roots(1, -2, 3)
(-3.0, 1.0)
```

# Выполнение тестов

Для автоматизации тестов перед коммитом используется механизм хуков. Хук ```pre-commit``` вызывается командой ```git commit```. Завершение скрипта с ненулевым статусом прервет выполнение ```git commit```. Запуск теста делегируется скрипту tests.py.  Файл ```pre-commit``` нужно поместить в директорию ```/.git/hooks``` и установить права на исполнение:
```
$ chmod +x pre-commit
$ ls -al .git/hooks/
...
-rwxr-xr-x 1 user user  28 янв  5 19:31 pre-commit
...
```

# Цели проекта

Код написан для образовательных целей. Учебный курс для веб-разработчиков - [DEVMAN.org](https://devman.org)
