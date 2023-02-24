# Kube state metrics
Copied CRD's from the Kube State Metrics Github repo:
[https://github.com/kubernetes/kube-state-metrics/tree/main/examples/standard](https://github.com/kubernetes/kube-state-metrics/tree/main/examples/standard)
to have them in own control. 

KSM has similarities with [Metrics Server](https://github.com/kubernetes-sigs/metrics-server) in a way that they both collect metrics. 
Metrics Server collects less metrics than KSM and is only meant for k8s itself. 
KSM collects more metrics and they can be scraped by Prometheus.