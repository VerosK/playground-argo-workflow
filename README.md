# Argo playground

## How to deploy argo workflows

1. start minikube

       00-start-minikube

2. deploy argo workflows to minikube

       01-start-workflows

3. do port-forward 

4. download `argo` binary to laptop

5. Run workflow

## How to start workflow

1. Open http://localhost:2746/

2. Submit workflows from `workflow` dir

        argo submit 02-python.yml

## Deploy Argo events

1. deploy argo events

       01-start-events

2. Deploy event-source and  trigger

3. do port-forward  on webhook

4. run webhook
