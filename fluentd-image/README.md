# Collecting Docker Log Files with Fluentd and AWS CloudWatch
This directory contains the source files needed to make a Docker image
that collects Docker container log files using [Fluentd][fluentd]
and sends them to AWS CloudWatch.

# How to build
`docker build -t zerda/kube-fluentd-cloudwatch:v2.0.3 .`
