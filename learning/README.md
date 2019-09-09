---
layout: LearningLayout
description: Kubernetes 免费教程
---

# Kubernetes 免费教程

本教程的主要依据是：Kubernetes 官网文档，以及使用 Kubernetes 落地 Spring Cloud 微服务并投产的实战经验。适用人群：
* Kubernetes 初学者
* 学习过 Kubernetes，但未能将其投产的技术爱好者

## **Kubernetes 体验**
  * [安装 Kubernetes 单Master节点](/install/install-k8s.html) （30分钟，初学者也许需要更多）
    * 参照经过众多网友验证，不断优化的安装文档，迅速完成 Kubernetes 安装，拥有属于自己的 Kubernetes 集群。
  * [安装微服务管理界面](/install/install-dashboard.html) （5分钟）
    * 使用 Kuboard，无需编写复杂冗长的 YAML 文件，就可以轻松管理 Kubernetes 集群。
  * [创建 busybox](/guide/example/busybox.html) （10分钟）
    * 快速在 Kubernetes 集群中安装一个部署，并与当中的容器组交互。
  * [导入 example 微服务应用](/guide/example/import.html) （15分钟）
    * 导入一个完整的 example 微服务应用，体验 Spring Cloud 在 Kubernetes 上的部署过程。

## **Kubernetes 入门**
  * [0. 学习Kubernetes基础知识](/learning/k8s-basics/kubernetes-basics.html) (10分钟)
    * [1. 部署第一个应用程序](/learning/k8s-basics/deploy-app.html) (5分钟)
    * [2. 查看 Pods / Nodes](/learning/k8s-basics/explore.html) (10分钟)
    * [3. 公布应用程序](/learning/k8s-basics/expose.html) (10分钟)
    * [4. 伸缩应用程序](/learning/k8s-basics/scale.html) (10分钟)
    * [5. 执行滚动更新](/learning/k8s-basics/update.html) (10分钟)
  * [6. 复习Kubernetes核心概念](/learning/k8s-basics/k8s-core-concepts.html) (10分钟)

## **Kubernetes 进阶**
  * [使用私有 registry 中的 docker 镜像](/learning/k8s-intermediate/private-registry.html)
  * 工作负载
    * [容器组 - 概述](/learning/k8s-intermediate/workload/pod.html)
    * [容器组 - 生命周期](/learning/k8s-intermediate/workload/pod-lifecycle.html)
    * [容器组 - 初始化容器](/learning/k8s-intermediate/workload/init-container.html)
    * [控制器 - 概述](/learning/k8s-intermediate/workload/workload.html)
    * [控制器 - Deployment](/learning/k8s-intermediate/workload/wl-deployment.html)
    * [控制器 - StatefulSet](/learning/k8s-intermediate/workload/wl-statefulset.html) <Badge text="正在撰写" type="warn"/>
    * [控制器 - DaemonSet](/learning/k8s-intermediate/workload/wl-daemonset.html) <Badge text="正在撰写" type="warn"/>
    * [控制器 - Job](/learning/k8s-intermediate/workload/wl-job.html) <Badge text="正在撰写" type="warn"/>
    * [控制器 - CronJob](/learning/k8s-intermediate/workload/wl-cronjob.html) <Badge text="正在撰写" type="warn"/>
  * 服务发现、负载均衡、网络
    * [Service](/learning/k8s-intermediate/service/service.html) <Badge text="正在撰写" type="warn"/>
    * [Service/Pod 的 DNS](/learning/k8s-intermediate/service/dns.html) <Badge text="正在撰写" type="warn"/>
    * [Service 连接应用程序](/learning/k8s-intermediate/service/connecting.html) <Badge text="正在撰写" type="warn"/>
    * [Ingress 通过互联网访问您的应用](/learning/k8s-intermediate/service/ingress.html)
    * [如何选择网络插件](/learning/k8s-intermediate/service/cni.html)
  * 存储
    * [数据卷 Volume](/learning/k8s-intermediate/persistent/volume.html)
    * [存储卷 PV 和存储卷声明 PVC](/learning/k8s-intermediate/persistent/pv.html)
    * [存储类 StorageClass](/learning/k8s-intermediate/persistent/storage-class.html)
    * [自建 NFS 服务](/learning/k8s-intermediate/persistent/nfs.html) <Badge text="正在撰写" type="warn"/>
  * 配置
    * [使用 ConfigMap 配置您的应用程序](/learning/k8s-intermediate/config/config-map.html)
    * [管理容器的计算资源](/learning/k8s-intermediate/config/computing-resource.html)
    * [将容器调度到指定的节点](/learning/k8s-intermediate/config/assign-pod-node.html)
    * [污点和容忍 taints and toleration](/learning/k8s-intermediate/config/taints-and-toleration.html) <Badge text="正在撰写" type="warn"/>
    * [Secrets](/learning/k8s-intermediate/config/secret.html) <Badge text="正在撰写" type="warn"/>


## **Kubernetes 实战**

在 Kubernetes 上部署 Spring Cloud 微服务：

* [概述](/micro-service/spring-cloud/index.html)
* [部署服务注册中心]
* [部署数据库]
* [部署微服务]
* [部署服务网关]
* [部署Web前端]
* [管理多环境]