# notes day 2

### learning about CRUD 

  - `C` - create
  - `R` - read
  - `U` - update
  - `D` - delete
   
### learning about http verbs/methods

 - `GET` - used to read info. info in this case could be a list could be an item or a web page, full or partial.

 - `POST` - used to give info to a server. in API post is used to create resources. on webpages post is used to submit forms. 

 - `PUT` - used to give update info to a server. in APIs put updates in existing resources. on a webpage PUT is used to make edits to a form and then give them to the server.

 - `DELETE` - used to delete info.

 ### learning about http status codes

 301 this is a redirect.

 307

 200 it means okay, we understand your request.

 201 created

 404 not found

 400 bad request, cannot proceed.

 500 internal server error

 ### learning about Marvel API

 The Marvel Comics API’s base endpoint is http(s)://gateway.marvel.com/ 

 `ts` - a timestamp (or other long string which can change on a request-by-request basis)

 `hash` - a md5 digest of the ts parameter, your private key and your public key (e.g. md5(ts+privateKey+publicKey)
 
 ### learning how to install python and venv

 we set up a virtual environment in the venv directory.

 activated the virtual env by entering `source venv/bin/activate.fish`.

 installed jupyter and requests.

 we started `jupyter notebook`.
 
 played around with `python`.
 

