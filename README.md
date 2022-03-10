# dps-intern-task
Google's VertexAI demo


Commands are provided in `commands.txt`. Scripts (train.py, Dockerfile, deploy.py, predict.py) are directly available here in this repo.

## Step-1: Create Project

![Create Project](images/create-proj.png)

## Step-2: Write the training script and build a docker around it

Look at mpg/trainer/train.py for reference.

__Build the Docker__

![Build Docker](images/docker-build.png)

__Push the Docker to container registry__

![Push the Docker to container registry](images/dockerpush.png)

## Step-3: Allocate a VM and start the training

![Start the training](images/training.png)

## Step-4: Create and deploy a model endpoint

![Create endpoint](images/model-deployed-cmdout.png)

![create-endpoint-ui](images/model-deployed-cmdout.png)

## Step-5: Predict

![predict](images/prediction.png)
