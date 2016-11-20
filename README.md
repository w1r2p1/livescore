# livescore 
###### Soccer live results service on Flash Score offers scores from 1000+ soccer leagues*. 
 

### Installation
Clone or download this repo 
```
https://github.com/Edik89/livescore.git
```
Run a Command in console: 
```shell
cd livescore-master
npm install # install dependencies in the main folder
npm start # run the application on port 3000
``` 

Open your browser `http://localhost:3000/graphql` 
and copy **id** (Object Identification [facebook.github.io](https://facebook.github.io/relay/docs/graphql-object-identification.html) )
![alt text](https://pp.vk.me/c638826/v638826770/125fd/VQcC4fyv-GA.jpg)
this **id** inserted to (src/frontend/app/routes/Router.jsx)
 ```js
 static queries = {
    viewer: () => Relay.QL`query{
        node(id: "TGl2ZXJlc3VsdDo1ODFhYTY2NzFiODk3MDFiOGI0N2QyM2U=")
    }`
  };
```
and open your browser: `http://localhost:3000/`
