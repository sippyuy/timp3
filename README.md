# Лабораторная работа №3
  Представьте, что вы стажер в компании "Formatter Inc.".
## Задание №1
Вам поручили перейти на систему автоматизированной сборки CMake. Исходные файлы находятся в директории formatter_lib. В этой директории находятся файлы для статической библиотеки formatter. Создайте CMakeList.txt в директории formatter_lib, с помощью которого можно будет собирать статическую библиотеку formatter.
- Клонируем репозиторий и открываем терминал в директории **formatter_lib**

![](https://github.com/sippyuy/timp3/blob/main/screens/1.png)

- Редактируем файл **CMakeLists.txt** в *nano*

![](https://github.com/sippyuy/timp3/blob/main/screens/2.png)

- Собираем проект и проверяем корректность сборки
      - cmake -B build - подготовка и обработка файлов сборки в библиотеку *build*
      - cmake --build build сборка библиотеки в исполняемый файл
    
![](https://github.com/sippyuy/timp3/blob/main/screens/3.png)

## Задание №2
У компании "Formatter Inc." есть перспективная библиотека, которая является расширением предыдущей библиотеки. Т.к. вы уже овладели навыком созданием CMakeList.txt для статической библиотеки formatter, ваш руководитель поручает заняться созданием CMakeList.txt для библиотеки formatter_ex, которая в свою очередь использует библиотеку formatter.

- Открываем терминал в библиотеке **formatter_ex_lib**

![](https://github.com/sippyuy/timp3/blob/main/screens/5.png)

- Редактируем файл **CMakeLists.txt** в *nano*

![](https://github.com/sippyuy/timp3/blob/main/screens/4.png)

- Команды для сборки проекта

![](https://github.com/sippyuy/timp3/blob/main/screens/6.png)

## Задание №3
Конечно же ваша компания предоставляет примеры использования своих библиотек. Чтобы продемонстрировать как работать с библиотекой formatter_ex, вам необходимо создать два CMakeList.txt для двух простых приложений:

  - hello_world, которое использует библиотеку formatter_ex;
  
  - Перемещаемся в директорию **hello_world_application** и редактируем CMakeLists.txt в nano
  
  ![](https://github.com/sippyuy/timp3/blob/main/screens/8.png)
  ![](https://github.com/sippyuy/timp3/blob/main/screens/7.png)
  
  - Сборка проекта
  
    ![](https://github.com/sippyuy/timp3/blob/main/screens/9.png)
    
  - Запускаем приложение и проверяем работоспособность
  
    ![](https://github.com/sippyuy/timp3/blob/main/screens/10.png)
    
  - solver, приложение которое испольует статические библиотеки formatter_ex и solver_lib.
  
  - Перемещаемся в директорию **solver_lib**  и редактируем файл CMake

    ![](https://github.com/sippyuy/timp3/blob/main/screens/12.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/11.png)
    
  - Перемещаемся в директорию **solver_application** и редактируем CMake
  
    ![](https://github.com/sippyuy/timp3/blob/main/screens/14.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/13.png)
    
  - Сборка приложения
  
    ![](https://github.com/sippyuy/timp3/blob/main/screens/15.png)
    
  - Запускаем приложение, вычисляющее решения квадратного уравнения, проверяем работоспособность
  
    ![](https://github.com/sippyuy/timp3/blob/main/screens/16.png)

Удачной стажировки!
