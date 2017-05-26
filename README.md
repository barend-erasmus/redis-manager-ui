# redis-manager-ui

## Getting Started

Clone the repository

`git clone https://github.com/barend-erasmus/redis-manager-ui.git`

Change to cloned directory

`cd ./redis-manager-ui`

Install node packages

`npm install`

Start project

`npm start`

Browse `http://localhost:4200`

## Docker Setup

`docker build --no-cache -t redis-manager-ui ./`

`docker run -d -p 8080:4200 --name redis-manager-ui -t redis-manager-ui`