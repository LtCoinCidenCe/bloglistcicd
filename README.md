# Bloglist application with CI/CD test
This repository is the frontend and backend of bloglist.  
The application was originally written in October 2021.  
There were pretty much legacy things that required handling...  
Almost 3 years have passed.

## Steps' pain list
1. copy the backend and run everythings. mongoose dependency 6 and validator were uncompatible. Had to use --force installation
2. mixing package.json file for 2 projects. code level
3. flyctl doesn't work because of pain no.1, managed to deceive it and passing ENV to flyctl
4. node 20 incompatible for building react with version 16
5. repeat pain no.1 in Dockerfile
6. repeat pain no.1 in cypress-io/github-action@v3 in workflow
7. weird findByIdAndUpdate problem in old mongoose 5
8. previous naive attempts
