# Лабораторная работа №3
<p align="center">Министерство образования Республики Беларусь</p>
<p align="center">Учреждение образования</p>
<p align="center">«Брестский государственный технический университет»</p>
<p align="center">Кафедра ИИТ</p>
<br><br><br><br>
<p align="center">Лабораторная работа №3</p>
<p align="center">По дисциплине: «ТИМАУ»</p>
<br><br><br>
<p align="right">Выполнила</p>
<p align="right">Студентка 3-го курса</p>
<p align="right">Группы АС-64</p>
<p align="right">Будник А.А.</p>
<p align="right">Проверил</p>
<p align="right">Иванюк Д.С.</p>
<br><br><br>
<p align="center">Брест 2024</p>

---

## Ход работы

### Ход работы:

1. Был клонирован репозиторий "savushkin-r-d/PLCnext-howto" на компьютер, и в Visual Code был собран исполняемый файл "hello_PLCnext" с использованием CMake.

![](./imgs/1.png)

2. Контроллер был подключен через LAN-кабель после настройки IPV-4 соединения. В свойствах подключения был установлен IP-адрес "192.168.1.1" и маска сети "255.255.255.0".

![](./imgs/2.png)

3. Для проверки соединения использовалась команда "ping 192.168.1.10" в командной строке, где "192.168.1.10" — это IP-адрес контроллера. Пакеты не терялись, что подтверждало правильность настройки соединения.

![](./imgs/3.png)

4. На компьютер были установлены две программы: PuTTY и WinSCP.
5. С помощью PuTTY было установлено соединение с контроллером, указав его IP-адрес, логин "admin" и пароль.

![](./imgs/4.png)
![](./imgs/5.png)

6. Через WinSCP исполняемый файл был передан в корневую директорию контроллера, после чего были введены IP-адрес, логин и пароль для подключения.

![](./imgs/6.png)

7. Были изменены права доступа, чтобы исполняемый файл можно было запустить.

![](./imgs/7.png)

8. Исполняемый файл был запущен и проверена корректность работы проекта.

![](./imgs/8.png)
![](./imgs/9.png)

В процессе выполнения лабораторной работы был разработан тестовый проект "Hello PLCnext from AS0xxyy!" и приобретены практические навыки взаимодействия с контроллером AXC F 2152.