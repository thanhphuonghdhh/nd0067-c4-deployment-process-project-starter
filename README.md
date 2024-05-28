# Hosting a Full-Stack Application

## Overview 
The project application, Udagram - an Image Filtering application, allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering service. It has two components:

    1. Frontend - Angular web application built with Ionic framework
    2. Backend RESTful API - Node-Typescript application

Screenshots of the working application in is `./screenshots`

## Link to hosted working frontend application
http://myawsbucket152001.s3-website.us-east-2.amazonaws.com

## Environment variables

```
export POSTGRES_USERNAME=postgres
export POSTGRES_PASSWORD=postgres
export POSTGRES_HOST=postgres.ckmnenicalgi.us-east-2.rds.amazonaws.com
export POSTGRES_DB=postgres
export AWS_BUCKET=arn:aws:s3:::myawsbucket152001
export AWS_REGION=us-east-2
export AWS_PROFILE=default
export JWT_SECRET=mysecretstring
```

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

# Changes after review

- Add a screenshot about the CircleCi secrets: Done
- Remove the hardcoded environmental variables (removed set_env.sh file): Done
- Fix deployed frontend: Done
