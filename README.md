# Responsibilities
* check - Иван
* controller - Егор
* user_interface - Денис
* block_diagram - Давид
* logs - Иван
* function (импорт, экспорт, запись) - Давид
* README - Иван
* main - Иван

* тестирование - 

# Задача:
Создать телефонный справочник с возможностью импорта и экспорта данных в нескольких форматах.
В рамках этого обсуждения вам надо нарисовать “архитектуру” (например, в виде блок-схемы) для работы данного приложения. Блок-схема архитектуры проекта обязательна.

- *под форматами понимаем структуру файлов, например:в файле на одной строке хранится одна часть записи, пустая строка - разделитель*
    
Фамилия_1
Имя_1
Телефон_1
Описание_1
    
Фамилия_2
Имя_2
Телефон_2
Описание_2
    
Фамилия_3
Имя_3*
Телефон_3
Описание_3
    
*и т.д.в файле на одной строке хранится все записи, символ разделитель - **;**
    
*Фамилия_1,Имя_1,Телефон_1,Описание_1*
*Фамилия_2,Имя_2,Телефон_2,Описание_2*
*и т.д.*


# Предварительный план работы :
1. Обсуждение в команде
2. Создание файловой архитектуры приложения и репозитория
3. Репозиторий форкается, участники его клонируют, СОЗДАЮТ ВЕТКУ со своим именем и производят индивидуальную работу над своей частью.
4. Далее push в свой репозиторий с доп веткой, после чего запрос на pull request в общий репозиторий.

# Список файлов (для архитектуры проекта)
1. Block_diagram.drawio (блок-схема проекта)
2. REARME.md (описание основной задачи и подзадач, распределение зон ответсвенности , прочие тех_требования)
3. user_interface.py (пользовательский интерфейс)
4. Main.py (button)
5. Controller.py
6. Log.py (функция записи логов)
7. Check.py (файл содержит проверки на корректное введение данных)
8. function.py (основные операции с файлами)
9. logs.csv (логи работы программы)
10. Telephone_base.txt (сам телефонный справочник в виде .txt)

