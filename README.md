# Оптимальная структура CMake проекта


Структура папки проекта
```
PROJECT_NAME
├── cmake
│   ├── FindGit.cmake
│   ├── git_revision.cmake
│   └── safeguards.cmake
├── doc
│   └── Doxyfile.in
├── libs
│   └── CMakeLists.txt
├── src
│   ├── MODULE_1_NAME
│   ├── MODULE_2_NAME
│   └── CMakeLists.txt
├── templates
│   ├── template_app_module
│   └── template_lib_module
├── CMakeLists.txt
├── conanfile.txt
├── create_new_app_module.sh
├── create_new_lib_module.sh
├── Doxyfile.in
├── LICENSE
├── Makefile
└── README.md
```


Структура папки каждого модуля
```
MODULE_NAME
├── CMakeLists.txt
├── data
├── include
│   └── PROJECT_NAME
│       └── MODULE_NAME
│           └── main.hpp
├── src
│   └── main.cpp
└── tests
    ├── CMakeLists.txt
    └── test_main.cpp
```

Здесь:

*```Project_name``` - название проекта
*```Project_name/src``` - каталог модулей программы
*```Project_name

```Module1_name```,
```Module2_name``` - названия модулей №1, №2.



[Источник](https://palikar.github.io/posts/cmake_structure/)
