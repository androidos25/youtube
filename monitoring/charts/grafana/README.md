# grafana

Чарт "обёртка". Создан для удобства использования в ArgoCD.

Пришлось отказаться от ingress из стандартного чарта. Он не поддерживает генерацию ingressClassName, только
соответствующую аннотацию. 

Что бы не "лезть руками" в чарт grafana, добавил генерацию своего ingress. Это конечно костыли, но они работают. 