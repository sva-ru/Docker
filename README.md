## команды для запуска контейнера c backend-сервером
1) Создаем образ на основе проекта джанго, коммандой: 
    docker build -t my_django_project:v1 .

2) Затем запускаем образ:
     docker run -d -p 8000:8000 my_django_project:v1
