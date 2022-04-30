### Домашнее задание к занятию "12.1. Компоненты Kubernetes"

#### Задача 1: Установить Minikube

![Alt text](https://i.ibb.co/0hv1KMR/Screenshot-2.jpg)

```  kubectl get pods --namespace=kube-system```

![Alt text](https://i.ibb.co/JqfHYPw/Screenshot-1.jpg)


#### Задача 2: Запуск Hello World

развернуть через Minikube тестовое приложение по [туториалу](https://kubernetes.io/ru/docs/tutorials/hello-minikube/#%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BA%D0%BB%D0%B0%D1%81%D1%82%D0%B5%D1%80%D0%B0-minikube).

![Alt text](https://i.ibb.co/GTvbY5Z/Screenshot-5.jpg)

Посмотреть события кластера:

```kubectl get events```

Посмотреть kubectl конфигурацию:

```kubectl config view```

![Alt text](https://i.ibb.co/FxBdd2W/Screenshot-6.jpg)

Отобразить текущие поддерживаемые дополнения:
![Alt text](https://i.ibb.co/LpT8XWQ/Screenshot-9.jpg)

Посмотреть Pod и Service, которые только что создали:

![Alt text](https://i.ibb.co/dPWNRLg/Screenshot-10.jpg)

Скрин дашборда

![Alt text](https://i.ibb.co/bW5cfQf/Screenshot-11.jpg)


#### Задача 3: Установить kubectl

Установлен: статус сервиса 

![Alt text](https://i.ibb.co/FDLV0gS/Screenshot-12.jpg)



