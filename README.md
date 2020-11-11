# Event Simulator using Kubernetes

## Create thw Pod

kubectl create -f event-simulator-pod.yaml

## Start the event simulator

kubectl logs -f event-simulator event-simulator

** First "event-simulator" refers to the Pod (check metadata name in yaml file) and second "event-simulator" refers to the container running the image (there are two images, "event-simulator" or "image-processor").





