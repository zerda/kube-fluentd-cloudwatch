# kube-fluentd-cloudwatch
Collecting Docker Log Files with Fluentd and AWS CloudWatch

# How to deploy
1. Edit [aws-secret.yaml](aws-secret.yaml) with real AWS credential.
2. Edit `log_group_name_key` and `log_stream_name_key` in [fluentd-configmap.yaml](fluentd-configmap.yaml) if necessary.
3. Deploy all of them to kubernetes, `kubectl apply -f .`

# Credits
- Most of them are copied from [Kubernetes](https://github.com/kubernetes/kubernetes/tree/master/cluster/addons/fluentd-elasticsearch).
