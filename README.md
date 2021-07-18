# vzaletny_platform
vzaletny Platform repository
<details>
<summary> # Выполнено ДЗ №2 </summary>

 - [ ] Основное ДЗ
 - [ ] Задание со *

## В процессе сделано:

Kubelet отслеживает состояние PODs и в случае отсутсвия от них heartbits (livenessProbe), запускает их заново;

 - Пункт 1:
    - Уcтановлен kubectl;
    - Установлен minikube;
    - Cоздан Dockerfile, в котором будет описан образ web сервера на nginx;
    - Cобран докер образ и размешен в Container Registry Docker Hub;
    - Создан манифест web-pod.yaml;
 - Пункт 2:
    - Собран и запушен образ Hipster Shop
    - Сгенерирован frontend-pod-healthy.yaml

## Как запустить проект:
 - Например, запустить команду X в директории Y

## Как проверить работоспособность:
 - Например, перейти по ссылке http://localhost:8080

## PR checklist:
 - [ ] Выставлен label с темой домашнего задания
</details>