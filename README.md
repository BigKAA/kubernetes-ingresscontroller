# kubernetes-ingresscontroller
Файлы к видео:
* kubernetes, ingress controller 1 - теория https://youtu.be/-kUr-sExQtg
* Kubernetes, Ingress controller 2, установка и настройка, вариант с NodePort https://youtu.be/ac-7ZDGCcFA
* Kubernetes, ingress controller 3, установка второго контроллера, вариант HostNetwork https://youtu.be/k26hETfmRzc

Файлы, используемые в видео:

* my-ingress-controller.yaml - Деплой ingress controller в режиме NodePort на помеченные при помощи специальных lables поды.
* prom-ingress.yaml - Тестовый ingress для доступа к установленному Prometheus

Вышла новая версия nginx ingress controller - 0.34.0. В этой версии изменили харнилице образов контейнеров. В связи с этим в файле my-ingress-controller.yaml был изменен путь к хранилищу.
