## AllureReportsTests

### Описание 
В проекте реализовано использование Allure отчета  

### 1. Подключение Allure
1. Подключить в pom.xml плагин Allure
2. Подключить в pom.xml библиотеку Allure
3. Настроить allure.properties в папке resources

### 2. Формирование отчета
- Удалить папку target
- Запустить тесты
- В вкладке Maven перейти в Plugins -> allure
- Allure:report - сформировать отчет
- Allure:serve - отобразить отчет