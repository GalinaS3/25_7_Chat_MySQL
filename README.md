# 25_7_Chat_MySQL
Организуйте хранение данных чата в базе данных.
Реализована архитектура клиент-сервер. Протокол TCP.
Файл Chat_Console_MySQL_S - сервер. Запускается первой. Файл Chat_Console_MySQL_C - клиент. Запускается второй.
Работа пользователя только в программе клиента.
Подключение к базе MySQL прописано на сервере в файле Data.cpp, функция void Data::openData(): host - "localhost", user - "root", password - "111", db - "testdb".
