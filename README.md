# GossipGirl
**GossipGirl** is a product inventory API backend which real-time notifies of any changes at field level of MongoDB. 

## Install

#### [npm](https://www.npmjs.com)
```
npm install
```
```
node .
```

```
localhost:3000/
```


## Rest API Endpoints


The following are the Rest API Endpoints on which request can be sent using Postman or any otherways.

 - Create `localhost:3000/api/products` 
 - Update `localhost:3000/api/products/{id}`
 - Delete `localhost:3000/api/products/{id}`
 

## Quick Start
Observe the notifications on localhost:3000/


### JSON data for POST Request
```js
{
  "Name": "string",
  "category": "string",
  "price": 0,
  "Orderid": "string"
}

```
