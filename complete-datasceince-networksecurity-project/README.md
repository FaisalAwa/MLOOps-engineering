### Network Security Projects For Phising Data

## Data Ingestion Pipeline
<img width="1037" height="770" alt="dataingestion" src="https://github.com/user-attachments/assets/0f5e0a39-abf2-492e-9365-3b1970883bd0" />

## Data Validation Pipeline
<img width="1223" height="870" alt="datavalidation" src="https://github.com/user-attachments/assets/f242c276-951e-45c8-80da-35cdf0bd336d" />

## Data Transformation Pipeline
<img width="817" height="788" alt="datatransformation" src="https://github.com/user-attachments/assets/a9011f3d-9b1f-458c-a2fa-f52414b559fb" />

## Model Training Pipeline
<img width="766" height="788" alt="modeltrainer" src="https://github.com/user-attachments/assets/258a9a87-daa9-4eb9-859d-63f016485701" />

Setup github secrets:
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 788614365622.dkr.ecr.us-east-1.amazonaws.com/networkssecurity
ECR_REPOSITORY_NAME = networkssecurity


Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
