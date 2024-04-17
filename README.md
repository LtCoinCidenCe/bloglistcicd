# Bloglist application with CI/CD test
This repository is the frontend and backend of bloglist.  
The application was originally written in October 2021.  
There were pretty much legacy things that required handling...  
Almost 3 years have passed.

## Steps' pain
1. copy the backend and run everythings. mongoose dependency 6 and validator were uncompatible. Had to use --force installation
2. mixing package.json file for 2 projects. code level
3. force install in fly.toml and injecting ENV to flyctl
4. NODE_OPTIONS: --openssl-legacy-provider
