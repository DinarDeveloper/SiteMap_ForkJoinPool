# SiteMap_ForkJoinPool
![ForkJoinPool](https://img.shields.io/badge/-ForkJoinPool-0a0a0a?style=for-the-badge&logo=ForkJoinPool)
![Java](https://img.shields.io/badge/-Java-0a0a0a?style=for-the-badge&logo=Java)
## Что использовалось
*`Java` - SDK 11\
*`Maven` - сборка проекта\
*`ForkJoinPool` - многопоточный обход ("Разделяй и властвуй")\
*`Jsoup` - легкий парсинг HTML-страниц\
*`FileWriter` - класс с удобными методами для записи информации в файл\
## Что умеет программа
- парсит сайт, извлекая только ссылки
- разделяет на потоки для быстрого обхода всех ссылок
- создает иерархию на дочерние ссылки относительно родительских
- записывает в файл полученные ссылки
## Пример результата записи в файл
![forkjoin](https://user-images.githubusercontent.com/83313585/179373848-7a7bc806-275e-4a70-a879-e29e527311a7.png)
