#!/bin/bash 

ns=($(kubectl get ns | awk '{print $1}' | sed '1d'))

if [ ! -z "$1" ]; then
kubectl config set-context --current --namespace=${ns[$1]}
else
        kubectl get ns | sed '1d' | awk 'BEGIN{x=0};{print x++") " $1}'
fi
