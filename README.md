Окружение MAC OC

1. Создать внешний репозиторий c названием XML.
В GitHub кликаю справа на кнопку New --> в Repository name прописываю XML -->
оставляю репозиторий публичным --> ставлю галочку рядом с Add a README file (чтоб репозиторий был непустой) --> Кликаю внизу на кнопку Creat repository
2. Клонировать репозиторий XML на локальный компьютер.
```bash
git clone <ссылка на репозиторий> #  в необходимом внешнем репозитории кликнуть справа на кнопку Code и скопировать HTTPS
```
3. Внутри локального XML создать файл “new.xml”. 
```bash
touch new.xml
```
4. Добавить файл под гит.
```bash
git add new.xml
```
5. Закоммитить файл.
```bash
git commit -m "first xml"
```
6. Отправить файл на внешний GitHub репозиторий.
```bash
git push
```
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, 
 будущая желаемая зарплата). Всё написать в формате XML.
 ```bash
 vim new.xml #  режим редактирования (I) - прописываю 
 ```
 ```xml
 <Person>
     <Name>Tatiana</Name>
     <Surname>Koneva</Surname>
     <Age>33</Age>
     <Pets>
         <Pet>Cat</Pet>
     </Pets>
     <Salary>150000RUR</Salary>
 </Person>    
 <!-- Жму ESC - :wq) -->
```
8. Отправить изменения на внешний репозиторий.
```bash
git add new.xml 
git commit -m "first xml_1" 
git push
```
9. Создать файл preferences.xml
```bash
touch preferences.xml
```
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, 
страна которую хотели бы посетить) в формате XML.
```bash
vim preferences.xml #  режим редактирования (I) - прописываю 
```
```xml
 <FORM>
    <Film>1+1</Film>
    <Series>Scrubs</Series>
    <Food>Khinkali</Food>
    <Season>Winter</Season>
    <Country>Japan</Country>
 </FORM>   
 <!-- Жму ESC - :wq) -->
```
11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```bash
touch sklls.xml 
vim skills.xml #  режим редактирования (I) - прописываю 
```
```xml
 <Courses>
	<Skills>
		<Skill>GIT</Skill>
		<Skill>Terminal</Skill>
		<Skill>Testing</Skill>
	</Skills>
 </Courses>
<!-- Жму ESC - :wq) -->
```
12. Сделать коммит в одну строку.
 ```bash
 git add .  
 git commit -m "first xml_1"
 ```
13. Отправить сразу 2 файла на внешний репозиторий.
```bash
git push
```
14. На веб интерфейсе создать файл bug_report.xml.
В репозитории XML кликаю справа на кнопку *ADD FILE* --> creat new file --> в *NAME YOUR FILE* прописываю bug_report.xml --> кликаю внизу на кнопку
*Commit new file*
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Какие изменения? они только в 36 пункте
16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
В репозитории XML находим нужный файл и кликаем по его названию --> справа кликаем на значок карандаша (редактирование) --> прописываем
```xml
 <XML>
    <Bugs>My whole life is a bag</Bug>
    </Bugs>
 </XML>
```
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 Кликаю внизу на кнопку Commit changes (сохранить)
 38. Синхронизировать внешний и локальный репозиторий XML
 ```bash
 git pull #  в терминале
 ```
