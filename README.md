# TXT
### GIT   HW#1_TXT
 1. Создать внешний репозиторий c названием TXT 
 
 <b>GitHub</b> <code> <b>+ New repository</b> </code>

 - [X] Public
 - [X] Add a README file

 <code> <b>Create repository</b> </code>

 2. Клонировать репозиторий TXT на локальный компьютер 
 
 <code> <b>git clone git@github.com:VictoriaK-QA/TXT.git</b> </code>

 3. Внутри локального TXT создать файл “new.txt” 
 
 <code> <b>cd TXT/</b> </code>  
 
 <code> <b>touch new.txt</b> </code>

 4. Добавить файл под гит 
 
 <code> <b>git add .</b> </code>

 5. Закоммитить файл 
 
 <code> <b>git commit -m "new file"</b> </code>
 
 6. Отправить файл на внешний GitHub репозиторий 
 
 <code> <b>git push</b> </code>

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT

 <code> <b>vim new.txt</b> </code>

 <b>Нажать</b> <code> <b>i</b> </code>
 ```
 name - Victoria
 age - 28
 pet - 1 
 salary - 300000
 ```
 <b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>

 8. Отправить изменения на внешний репозиторий 
 
 <code> <b>git commit -am "info about me"</b> </code> 
 
 <code> <b>git push</b> </code>

 9. Создать файл preferences.txt 
 
 <code> <b>touch preferences.txt</b> </code>

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT

 <code> <b>vim preferences.txt</b> </code>

 <b>Нажать</b> <code> <b>i</b> </code>
 ```
 favorite movie: The Godfather,
 favorite sitcom: Friends,
 favorite food: pasta,
 favorite season: autumn,
 country to travel: Italy	
  ```
 <b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>
 
 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT 
 
  <code> <b>touch skills.txt</b> </code>

  <code> <b>vim skills.txt</b> </code>

 <b>Нажать</b> <code> <b>i</b> </code>
 ```
 SKILLS: 
 Testing Theory, 
 Client server, 
 SQL, 
 Postman, 
 Charles Fiddler Sniffing, 
 Web Services, 
 Git Linux Terminal, 
 DevTools, 
 Mobile Testing, 
 Web Testing, 
 Load testing 
 ```

 <b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>
 
 12. Сделать коммит в одну строку 
 
 <code> <b>git add .</b> </code>
 
 <code> <b>git commit -m "info about skills and preferences"</b> </code>

 13. Отправить сразу 2 файла на внешний репозиторий 
 
 <code> <b>git push</b> </code>

 14. На веб интерфейсе создать файл bug_report.txt 
 
 <b>Нажать</b> <code> <b>Add file</b> </code> + <code> <b>Create new file</b> </code> 

 <b>Имя файла bug_report.txt</b>

  15. Сделать Commit changes (сохранить) изменения на веб интерфейсе 
  
 <b>Нажать</b> <code> <b>Commit new file</b> </code> 

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT 
 
 <b>Нажать</b> <code> <b>Edit this file</b> </code>
 
```
ID: BR-14,
Title: What? Where? When?,
Severity: Minor,
Priority: Medium,
Precondition: Preparation steps,
Environment: Devices,
STR: Steps to restore,
ER: Expected result,
AR: Actual Result,
Attachment: link
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе 
 
 <b>Нажать</b> <code> <b>Commit changes</b> </code>

 18. Синхронизировать внешний и локальный репозиторий TXT 
 
 <code> <b>git pull</b> </code>