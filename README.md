k8s部署常用Yaml合集
===

以下为常用的开源软件Kubernetes部署的Yaml 及 常用资源创建的Yaml, 列出的大部分都是我工作中验证过、总结的， 也欢迎大家补充！

官方： 标识来源于官方网站或官方开源代码仓


[TOC]

# 开源软件


## Ingress （官方）

- nginx ingress controller

- ingress rule(以jaeger ingress 为例) 

更新日期： 2020/06/26

参考文档： https://github.com/kubernetes/ingress-nginx

## Grafana

更新日期： 2020/06/26

## Jaeger（官方）

- all-in-one

- ingress rules

更新日期： 2020/06/26

参考文档： https://github.com/jaegertracing/jaeger-kubernetes/blob/master/all-in-one/jaeger-all-in-one-template.yml

PS： Jaeger 作为使用比较广泛的开源软件， 官方现在更推荐使用Operator创建

## Consul (未验证)

更新日期： 2020/06/26

官方文档： https://www.consul.io/docs/k8s/installation/overview


## Prometheus

- Prometheus ingress


## BusyBox-curl

带有curl命令的,busybox

更新日期： 2020/06/26

---

# 其他常用资源创建

## Namespace (官方)

更新日期：2020/06/26

参考文档： https://kubernetes.io/docs/tasks/administer-cluster/manage-resources/memory-default-namespace/ 

## Deployment

以常用Demo部署Yaml 为例

更新日期：2020/06/26

## Service

更新日期：2020/06/26













