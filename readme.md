в application.yaml установить нужные сайты для поиска
например : 
indexing-settings:
sites:
- url: https://url.ru
name: url
- url 2
- name 2

У указать логин и пароль для доступа к БД    
username: root
password: root

После запуска на вкладке management нажать start index
![img.png](img.png)

Когда все сайты проиндексированы, это видно на вкладке dashboard
![img_1.png](img_1.png)

После можно проводить поиск по ключевым словам на вкладке 
search
![img_2.png](img_2.png)