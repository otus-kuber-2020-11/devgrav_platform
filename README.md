# devgrav_platform
devgrav Platform repository

Homework #1
Реализовано:
* Установлен minikube, kubectl, dashboard, k9s
* Написан Docker образ для запуска nginx в контейнере и выложен на Docker Hub 
* Написан манифест для запуска пода, разработанного ранее, под в кластере minikube
* Добавлен init контейнер
* Собран и запущен образ с frontend приложением Hipster Shop
* Исправлена ошибка в автоматически сгенерированном манифесте для запуска frontend приложения. Добавлены переменные окружения с адресами других приложений

Запуск:

`kubectl apply -f web-pod.yaml`
`kubectl port-forward --address localhost pod/web 8000:8000`

