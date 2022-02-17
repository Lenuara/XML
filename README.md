# XML
36. Создать внешний репозиторий c названием XML.  
   * Войти в свой профиль на https://github.com/ 
    * Зайти в раздел Repositories
    * Нажать кнопку New 
    * Указать:
       * Repository name "XML"
       * Radiobutton "Private"
       * Checkbox "Add a README file"
    * Репозиторий [XML](https://github.com/Lenuara/XML) создан, его имя появилось в списке репозиториев
37. Клонировать репозиторий XML на локальный компьютер.  
   `cd ~/LearningQA/LearnGIT/`  
    `git clone https://github.com/Lenuara/XML.git`
38. Внутри локального XML создать файл “new.xml”.  
   `cd XML`  
    `touch new.xml`
39. Добавить файл под гит.  
    `git add new.xml`
40. Закоммитить файл.  
   `git commit -m "Add new.xml"`
41. Отправить файл на внешний GitHub репозиторий.  
   `git push`
42. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.  
   `vim new.xml`
43. Отправить изменения на внешний репозиторий.  
   `git add new.xml`  
   `git commit -m "Edited new.xml"`  
   `git push`
44. Создать файл preferences.xml  
   `touch preferences.xml`
45. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате XML.  
   `vim preferences.xml`
46. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
   `vim sklls.xml`
47. Сделать коммит в одну строку.  
  `git commit -am "Add preferences.xml and sklls.xml"` 
48. Отправить сразу 2 файла на внешний репозиторий.  
   `git push`
49. На веб интерфейсе создать файл bug_report.xml.  
   На вкладке репозитория нажать Add file -> Create new file -> Name your file... -> bug_report.xml
50. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
   Нажатием на кнопку Commit new file сохранить изменения
51. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
   Зайти в файл bug_report.xml  
   Нажать пиктограмму Edit this file
52. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
   Нажать Commit changes
53. Синхронизировать внешний и локальный репозиторий XML  
   `git pull`
