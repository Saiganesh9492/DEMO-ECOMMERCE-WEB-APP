# Creating a Demo Ecommerce RESTful API with Node.js and express

## Usage


### Tech Stack Used :
- Back-End
  - Node.js
  - Express.js (With JWT)
  - MongoDB (mongoose ORM)

---

## Steps to run it locally :-

1. Fork the repo and clone it or Download the ZIP.
2. Make sure `npm & node` installed in your local machine, if Yes then Open a cmd/terminal tab.
3. (In Root) Run `npm install`, again Run `cd client && npm install` to install packages in both server and client.
4. (In Root) Run `npm start` It will start at server at default `PORT 3000` or Run `npm run server` to use nodemon.
5. Open another cmd/terminal tab, (In Root) Run `cd client && npm start` to start server on `PORT 3000`.
6. Use graphical user interface application like Postman for App testing 
7. Make sure to also add your Mongo Atlas Admin Username to a nodemon.json file (which you have to create).

```
{
    "env": {
        "MONGO_ATLAS_PW": "YOUR_MONGO_USER_PW"
    }
}
```

