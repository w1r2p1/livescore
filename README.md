# livescore

- Installation
 + Clone this repo
 + Run: ```npm install``` and ```npm start``` 
 + Open in Browser ```http://localhost:3000/graphql``` 
 and copy id
 ![alt text](https://pp.vk.me/c638826/v638826770/125fd/VQcC4fyv-GA.jpg)
 + this id inserted to (frontend/app/routes/TestRouter.jsx)
 ```js
 static queries = {
    viewer: () => Relay.QL`query{
        node(id: "TGl2ZXJlc3VsdDo1ODFhYTY2NzFiODk3MDFiOGI0N2QyM2U=")
    }`
  };
```
 + and watch ```http://localhost:3000/```
