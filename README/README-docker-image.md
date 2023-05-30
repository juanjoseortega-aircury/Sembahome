# Setting the project
> docker build -t sembahome -f Dockerfile .

# Container creation
> docker run --name sembahome_website -it -d -v ./:/home/repository -p 4000:4000 sembahome

## Run the containers
> docker start sembahome_website

## Access containers
> docker exec -it sembahome_website bash

## First time executing 
The first time before executing the jekyll website you should use this commands:
> bundle config set --local path 'vendor/bundle'
> bundle install

## Executing jekyll website
> bundle exec jekyll serve

## Access to project
> http://localhost:4000/

## Stop the containers
> docker stop sembahome_website
