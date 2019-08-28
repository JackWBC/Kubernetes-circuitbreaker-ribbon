# Kubernetes-circuitbreaker-ribbon
Kubernetes-circuitbreaker-ribbon 演示Kubernetes环境下的Hystrix circuit breaker与Ribbon Load Balancing

记得给所在的namespace的对应的ServiceAccount开通以下权限
资源 "configmaps", "pods", "services", "endpoints", "secrets"  
操作 "get", "list", "watch"  
