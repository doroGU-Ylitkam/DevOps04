# DevOps04
k8s pods
Для запуска манифеста необходимо ввести команду:
'''
kubectl apply -f https://raw.githubusercontent.com/doroGU-Ylitkam/DevOps04/refs/heads/main/app-pod.yaml
'''

Для проверки — следующая команда:
'''
kubectl get pods
'''
Примерный вывод:
'''
NAME                      READY   STATUS    RESTARTS   AGE
service-for-study01-pod   1/1     Running   0          4m37s
'''
