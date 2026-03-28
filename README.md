## Решение задания 1

Создание Deployment приложения, состоящего из двух контейнеров и подключение веб-страницы через ConfigMap:   
https://github.com/cranberry511/kuber-homeworks_2.3/blob/main/deployment.yaml   
https://github.com/cranberry511/kuber-homeworks_2.3/blob/main/configmap-web.yaml   

Проверка доступности:
![nginx](img/nginx.jpg)


## Решение задания 2

Создание Secret:   
https://github.com/cranberry511/kuber-homeworks_2.3/blob/main/secret-tls.yaml
![Secret](img/secret.jpg)

Настройка Ingress и проверка HTTPS-доступа:   
https://github.com/cranberry511/kuber-homeworks_2.3/blob/main/ingress-tls.yaml
![Ingress](img/ingress.jpg)


## Решение задания 3

Создание SSL-сертификата для пользователя:   
![SSL1](img/cert1.jpg)

![SSL2](img/cert2.jpg)

Создание Role и RoleBinding:   
https://github.com/cranberry511/kuber-homeworks_2.3/blob/main/role-pod-reader.yaml
https://github.com/cranberry511/kuber-homeworks_2.3/blob/main/rolebinding-developer.yaml
![Role](img/role.jpg)

Проверка доступа:   
![Set credentials](img/set-credentials.jpg)

![Check](img/check.jpg)