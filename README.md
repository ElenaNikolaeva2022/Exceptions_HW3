# Исключения в программировании и их обработка

## Урок 3. Продвинутая работа с исключениями в Java

### Практическое задание

1. Создать статический метод который принимает на вход три параметра: login, password и confirmPassword.
2. Login должен содержать только латинские буквы, цифры и знак подчеркивания.
3. Длина login должна быть меньше 20 символов. Если login не соответствует этим требованиям, необходимо выбросить WrongLoginException.
4. Password должен содержать только латинские буквы, цифры и знак подчеркивания. Длина password должна быть меньше 20 символов. Также password и confirmPassword должны быть равны.
5. Если password не соответствует этим требованиям, необходимо выбросить WrongPasswordException.
6. WrongPasswordException и WrongLoginException - пользовательские классы исключения с двумя конструкторами – один по умолчанию, второй принимает сообщение исключения и передает его в конструктор класса Exception.
7. Обработка исключений проводится внутри метода.
8. Метод возвращает true, если значения верны или false в другом случае.
