# JSON
JSON
 4. Создать внешний репозиторий c названием JSON. - на Гитхабе жмем New, ставим галочку Public и жмем Create repository
 5. Клонировать репозиторий JSON на локальный компьютер. - git clone
 6. Внутри локального JSON создать файл “new.json”. - cd JSON => touch new.json
 7. Добавить файл под гит. - git add new.json
 8. Закоммитить файл. - git commit -m "create new.json"
 9. Отправить файл на внешний GitHub репозиторий. - git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON. - vim new.json
 11. Отправить изменения на внешний репозиторий. - git add new.json => git commit -m "modify new.json" => git push
 12. Создать файл preferences.json - touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. - vim preferences.json
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON - vim skills.json
 15. Отправить сразу 2 файла на внешний репозиторий. - git add . => git commit -m "add preferences.json and skills.json" => git push 
 16. На веб интерфейсе создать файл bug_report.json. - Add file => Create new file
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - Commit new file
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. - Edit this file
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - Commit changes
 20. Синхронизировать внешний и локальный репозиторий JSON - git pull
