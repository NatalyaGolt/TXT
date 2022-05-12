# TXT
### 1. Создать внешний публичный репозиторий c названием TXT
- Перейти в [профиль github](https://github.com/NatalyaGolt, "NatalyaGolt github profile")
  
- Перейти на вкладку репозиториев

  |Repositories|
  |------------|
  
- Создать новый репозиторий
  
  |New|
  |---|
  
- Ввести имя репозитория
  
 
  |TXT :white_check_mark:|
  |-----------------------|
  
- Добавить Readme.md файл

  |:ballot_box_with_check: Add README file|
  |---------------------------------------|

- Создать репозиторий
  
  |Create repository|
  |-----------------|

### 2. Клонировать репозиторий TXT на локальный компьютер
    git clone https://github.com/NatalyaGolt/TXT.git
### 3. Внутри локального TXT создать файл new.txt
    touch TXT/new.txt
### 4. Добавить файл под гит
    cd TXT && git add new.txt
### 5. Закоммитить файл
    git commit -m "add new.txt"
### 6. Отправить файл на внешний GitHub репозиторий
    git push
### 7. Отредактировать содержание файла new.txt - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT
    vim new.txt

_i - для редактирования файла_

    Name: Natalya
    Age: 30
    Pets: 0
    Salary: 2000$

_esc - выход из режима редактирования_

    :wq - возврат к командной строке
### 8. Отправить изменения на внешний репозиторий
    git add new.txt && git commit -m "update new.txt" && git push
### 9. Создать файл preferences.txt
    vim preferences.txt
### 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате TXT

_i - для редактирования файла_

    Movie: The prestige
    Series: Friends
    Food: Borsh
    Season: Summer
    Country: Iceland

_esc - выход из режима редактирования_

    :wq - возврат к командной строке
### 11. Создать файл skills.txt, добавить информацию о скиллах которые будут изучены на курсе в формате TXT
    vim skills.txt

_i - для редактирования файла_

    Skills:
    1) Linux terminal/Gitbash
    2) JavaScript
    3) Autotests in Postman

_esc - выход из режима редактирования_

    :wq - возврат к командной строке
### 12. Сделать коммит в одну строку
    git add . && git commit -m "add two files"
### 13. Отправить сразу 2 файла на внешний репозиторий
    git push
### 14. На веб интерфейсе создать файл bug_report.txt
Находясь во внешнем репозитории TXT
- Нажать на кнопку Добавить файл
  
  |Add file|
  |--------|

- Нажать Создать новый файл
  
  |Create new file|
  |---------------|

- Ввести имя и расширение файла
  
  |TXT/bug_report.txt|
  |--------------------|

### 15. Сделать Commit на веб интерфейсе
Нажать кнопку Закоммитить новый файл

  |Commit new file|
  |---------------|

### 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT
- На внешнем репозитории выбрать файл bug_report.txt 
  
  |bug_report.txt|
  |---------------|

- Нажать кнопку редактирования файла

  |:pencil2:|
  |---------|

- Написать баг репорт в формате txt
  
        id: 001

        summary: Can't send the email. Button 'send' is inactive

        environment: PC Windows 10, Google Chrom v 101.0.4951.41

        precondisions: autorisation in email

        steps:
        1) Push button 'write'
        2) Insert receiver email in 'whom' field
        3) Write the message
        4) Push button 'send'

        expected result: 
        1) Letter window is opened
        2) Can add an adress
        3) Can write the message
        4) The letter sent sucsessfully. Window shows the message 'sent'

        actual result
        1) Letter window is opened
        2) Can add an adress
        3) Can write the message
        4) Can't send the email. Button 'send' is inactive

        priority: P1

        severity: S1

        assign: Email developer


### 17.  Сделать Commit changes (сохранить) изменения на веб интерфейсе
Нажать кнопку Закоммитить изменения

|Commit changes|
|--------------|

### 18. Синхронизировать внешний и локальный репозиторий TXT
    git pull
