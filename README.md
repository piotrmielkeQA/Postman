## Introduction
This project has basic API tests, written in Postman.


To tests using JSON Server
[JSON Server]([http://automationpractice.com/index.php](https://github.com/typicode/json-server))

## Technologies/Tools:
- (Nodejs)(https://nodejs.org/en)
- (Newman)(https://learning.postman.com/docs/collections/using-newman-cli/installing-running-newman/)
- (Postman)(https://www.postman.com/)

## Installation of required applications :
1. Install [Node JS](https://nodejs.org/en/download/)
2. Install Postman
3. Install Newmann by command: 
```
npm install -g newman

```
## Preperation and running JSON Server before run tests

1. Install JSON Server by command: 
```
Install JSON Server

```
2. Start JSON Server and creating database

```
json-server --watch db.json

``` 

3. After runed JSON Servers is available by address:: http://localhost:3000/posts/1


## How to running tests

1. Start JSON Server (API)
```
json-server --watch db.json

``` 

2. Clone this repository.

```


```

3. Open this collection is Postman or running collection by newman in command prompt using command: 

```
newman run mycollection.json

```





