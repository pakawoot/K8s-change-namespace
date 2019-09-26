# K8s-change-namespace

## Usage

Run without a parameter to get all namespaces

```
[ec2-user@EC2 ~]$./changeNS.sh
0) kube-system
1) kube-public
2) devops
3) default
4) ingress-nginx
```
Run with a parameter to select a namespace

```
[ec2-user@EC2 ~]$ ./changeNS.sh 2

Context "arn:aws:eks:ap-southeast-1:123456789012:cluster/foo-bar-1234567890" modified. 
```
