安装组件
yum install -y kubelet kubeadm kubectl

k8s镜像拉取
kubeadm config images list

    k8s.gcr.io/kube-apiserver:v1.21.0
    k8s.gcr.io/kube-controller-manager:v1.21.0
    k8s.gcr.io/kube-scheduler:v1.21.0
    k8s.gcr.io/kube-proxy:v1.21.0
    k8s.gcr.io/pause:3.4.1
    k8s.gcr.io/etcd:3.4.13-0
    k8s.gcr.io/coredns/coredns:v1.8.0
