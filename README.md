[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/vfarcic/copilot-demo)

# Create the secret `regcred`

```bash
kubectl create secret generic regcred \
    --from-file=.dockerconfigjson=/home/yann/tests-yann/docker_config.json \
    --type=kubernetes.io/dockerconfigjson
```

# Kaniko Demo

Created for the following videos in [The DevOps Toolkit Series YouTube channel](https://www.youtube.com/c/TheDevOpsToolkitSeries):

* [Kaniko - Building Container Images In Kubernetes Without Docker](https://youtu.be/EgwVQN6GNJg)
