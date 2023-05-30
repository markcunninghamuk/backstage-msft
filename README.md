# Running Locally

Navigate to the backstage-app folder and run the following Command:

*cd .\capgemini-msft-uk*

*yarn dev*yarn 


# Production

*yarn build:backend --config app-config.yaml*

*docker image build . -f packages/backend/Dockerfile --tag msft-pace-0.0.0.1-alpha*

docker run -it -p 7007:7007  msft-pace-0.0.0.1-alpha