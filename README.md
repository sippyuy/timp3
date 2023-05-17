# Лабораторная работа №3
  Представьте, что вы стажер в компании "Formatter Inc.".
## Задание №1
Вам поручили перейти на систему автоматизированной сборки CMake. Исходные файлы находятся в директории formatter_lib. В этой директории находятся файлы для статической библиотеки formatter. Создайте CMakeList.txt в директории formatter_lib, с помощью которого можно будет собирать статическую библиотеку formatter.

![](https://github.com/sippyuy/timp3/blob/main/screens/1.png)
![](https://github.com/sippyuy/timp3/blob/main/screens/2.png)
![](https://github.com/sippyuy/timp3/blob/main/screens/3.png)

## Задание №2
У компании "Formatter Inc." есть перспективная библиотека, которая является расширением предыдущей библиотеки. Т.к. вы уже овладели навыком созданием CMakeList.txt для статической библиотеки formatter, ваш руководитель поручает заняться созданием CMakeList.txt для библиотеки formatter_ex, которая в свою очередь использует библиотеку formatter.

![](https://github.com/sippyuy/timp3/blob/main/screens/5.png)
![](https://github.com/sippyuy/timp3/blob/main/screens/4.png)
![](https://github.com/sippyuy/timp3/blob/main/screens/6.png)

## Задание №3
Конечно же ваша компания предоставляет примеры использования своих библиотек. Чтобы продемонстрировать как работать с библиотекой formatter_ex, вам необходимо создать два CMakeList.txt для двух простых приложений:

  - hello_world, которое использует библиотеку formatter_ex;
    
    ![](https://github.com/sippyuy/timp3/blob/main/screens/8.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/7.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/9.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/10.png)
    
  - solver, приложение которое испольует статические библиотеки formatter_ex и solver_lib.
  
    ![](https://github.com/sippyuy/timp3/blob/main/screens/12.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/11.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/14.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/13.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/15.png)
    ![](https://github.com/sippyuy/timp3/blob/main/screens/16.png)

Удачной стажировки!
