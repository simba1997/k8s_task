# k8s_TASK

![k8s](https://user-images.githubusercontent.com/72957443/205514141-3b5b18ae-e1f4-48eb-a6a2-af9651086e06.jpeg)




# Kubernetes Task: 
Here is the task specifications: 
Please use your last two homework assignments:
- The YNET news
- The Bitcoin app
#### you can find ynet and bitcoin apps in my repository.
1- Dockerize your YNET and Bitcoin applications
2- Create Kubernetes manifests (Deployment and service)
3- Deploy on your minikube
4- Deploy/Enable Ingress Controller on your cluster
5- Create an ingress that directs the traffic to the correct service:



http://.../ynet → ynet service http://.../bitcoin → bitcoin service


ADDED TWO DOCKER CONTAINERS TO DOCKERHUB


![dockerhub_1](https://user-images.githubusercontent.com/72957443/205513972-19d2abf4-7bf3-4055-91c5-c11ce2a4ea89.jpeg)


## How to Run the code? 

1) Clone this repository  
2) cd into the directory 
3) minikube start
4) kubectl apply -f .
5) minikube addons enable ingress
6) sudo minikube tunnel

![last_1](https://user-images.githubusercontent.com/72957443/205513949-f7faf290-777d-416c-b3ee-b922086aa7d8.jpeg)

Now you can visit these two websites using the following URLs: 

http://localhost/ynet 

![ynet_1](https://user-images.githubusercontent.com/72957443/205513922-6f6ba9da-ba3b-4b82-9d42-fa5586bbd7dd.jpeg)

http://localhost/bitcoin

![bitcoin_1](https://user-images.githubusercontent.com/72957443/205513939-f60d8d0e-e74d-4f11-b772-3b095c01f25e.jpeg)
