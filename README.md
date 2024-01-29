# Домашнее задание к занятию "2.Базовые объекты K8S" - Баранков Антон"

### Задание 1.
1. Создать манифест (yaml-конфигурацию) Pod.  
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.  
3. Подключиться локально к Pod с помощью kubectl port-forward и вывести значение (curl или в браузере).  

[Файл pods_hello.yaml](img/pods_hello.yaml)

![Скриншот](img/1.JPG)

### Задание 2
1. Создать Pod с именем netology-web.  
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.  
3. Создать Service с именем netology-svc и подключить к netology-web.  
4. Подключиться локально к Service с помощью kubectl port-forward и вывести значение (curl или в браузере).  

[Файл pods_netology.yaml](img/pods_netology.yaml)

![Скриншот](img/2.JPG)
