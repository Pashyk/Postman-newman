# Postman-newman
Automating with Newman

Install nodejs using the apt package manager:
```
apt install nodejs 
```
To be able to download npm packages, you also need to install npm, the Node.js package manager. To do so type:
```
apt install npm
```
Install newman to be able run collection:
```
npm install newman
```
Run collection:
``
newman run swapi.co_collection.json --environment swapi.co_environment.json
``
