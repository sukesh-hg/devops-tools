# Skaffold

Skaffold is a command line tool that brings automation to the deployment workflow of Kubernetes applications. This tool is tailored to provide developers with an experience of iteration and deployment which closely mirrors production. Skaffold helps to automate CI/CD workflow (building, pushing and deploying) by providing rapid feedback to developers, i.e. the ability to promptly see the result of code changes in the form of an updated application running in Kubernetes.

Skaffold’s central command, skaffold dev, watches local source code for changes, and rebuilds and redeploys applications to your cluster in real time. This makes a marked change in developer velocity and productivity.

PREREQUISITES: Docker Engine, Kubernetes Engine

INSTALLATION: Connect to your Kubernetes or Minikube, install skaffold using below commands
sudo wget https://storage.googleapis.com/skaffold/releases/latest/skaffold-linux-amd64  -O /usr/local/bin/skaffold 
chmod +x  /usr/local/bin/skaffold

RUNNING SKAFFOLD: Use 'skaffold run' in CLI. 'skaffold dev' to enter into developement mode.
