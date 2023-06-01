**Лабораторная работа №5**

**Цель - изучение фреймворков для тестирования на примере GoogleTest**

Создам *fork* репозитория Lab05 (https://github.com/tp-labs/lab05)

Создам workflow:
```
$ mkdir .github
$ cd .github
$ mkdir workflows 
$ cd workflows
$ nano cmake.yml
```
Отредактирую его в редакторе nano:

<img width="682" alt="Снимок экрана 2023-06-01 в 21 15 27" src="https://github.com/FUR1OUSS/TIMP_lab5/assets/82472327/dc639d52-d6f6-4a85-b713-d352541d6fc5">

Подключим submodule гуглтест

```git submodule add https://github.com/google/googletest```

В корневой папке репозиотрия создам CMakeLists.txt:

Отредактирую его:

<img width="682" alt="Снимок экрана 2023-06-01 в 22 20 12" src="https://github.com/FUR1OUSS/TIMP_lab5/assets/82472327/db24225b-9f0c-4232-aaca-6a94ea88a10d">

Создам директорию tests и тест в ней:
```
$ mkdir tests
$ cd tests 
$ nano test.cpp
```
Отредактирую его:

<img width="682" alt="Снимок экрана 2023-06-01 в 22 23 05" src="https://github.com/FUR1OUSS/TIMP_lab5/assets/82472327/eb00f40f-c14a-4ac8-b34b-79d948d22117">

Пушим изменения в удаленный репозиторий:
```
$ git add
$ git commit -m "add_gtest"
$ git push origin main
```
