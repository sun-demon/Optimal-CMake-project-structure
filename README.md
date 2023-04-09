# Оптимальная структура CMake проекта

```
Project_name
├── src
|   ├── Module1_name
|   |   ├── include
|   |   |   └──Project_name
|   |   |      └──Module1_name
|   |   |    
|   ├── Module2_name
|   └── CMakeLists.txt
├── libs
│   └── CMakeLists.txt
├── cmake
|   ├── FindLibrary1_name.cmake
│   └── FindLibrary2_name.cmake
└── CMakeLists.txt
```

Здесь:

*```Project_name``` - название проекта
*```Project_name/src``` - каталог модулей программы
*```Project_name

```Module1_name```,
```Module2_name``` - названия модулей №1, №2.



[Источник](https://palikar.github.io/posts/cmake_structure/)
