# Kubernetes
 
  ## Kubernetes là gì?

  Kubernetes là một sản phẩm nằm trong hệ sinh thái container. Kubernetes là một mã nguồn mở dùng tự động triển khai, nhân rộng hệ thống và quản lý các container. Kubernetes được phát triển bởi Google, google sử dụng kubernetes để quản lý các docker container của họ. Người ta thường hay gọi Kubernetes là K8s (viết tắt chữ đầu và chữ cuối, 8 là số ký tự ở giữa )

  ## Những trường hợp cần thiết sử dụng k8s

   - với hệ thống máy chủ vật lý trên 3 đến 5 máy trở lên có sử dụng container hoặc hệ thống sử dụng nhiều container số lượng lớn.
   - ứng dụng cho kiến trúc microservice hay cloud native app
   - Các ứng dụng muốn scale số lượng lớn. 
   - Các sysadmin, developer .. hay các công ty muốn tự động hoá các việc cài đặt, triển khai các giải pháp CI/CD.
  
 ##  Các cách cài đặt k8s 
   - Sử dụng [Minikube](https://kubernetes.io/docs/setup/learning-environment/minikube/) để cài đặt 1 cluster test trên máy của chính mình.
   -  [Kubeadm]() là một cách để cài k8s trên hệ thống máy vật lý, máy ảo sử dụng ubuntu hay centos.
   - [Kargo]() là phần mềm dựa trên Ansible để cài trên rất nhiều nơi bao gồm cả máy vật lý/máy ảo/AWS/GCE.
   - cài đặt bằng tay trên [CoreOS Container Linux]()
Và còn nhiều cách cài đặt kháC 

 ## Các sản phẩm tương tự Kubernetes

   - [Docker Swarm](https://docs.docker.com/engine/swarm/)

   - [Apache Mesos](https://mesos.apache.org/)



 ## Các hệ thống cung cấp cài đặt sẵn K8s

- [Google container engine(GKE)](https://cloud.google.com/container-engine/)

- [CoreOS techtonic](https://coreos.com/tectonic/)

- [RedHat Openshift](https://www.openshift.com/)
  