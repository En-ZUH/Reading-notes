# Express REST API
![img](https://bs-uploads.toptal.io/blackfish-uploads/blog/post/seo/og_image_file/og_image/15921/secure-rest-api-in-nodejs-18f43b3033c239da5d2525cfd9fdc98f.png)

## 1. Name 3 real world use cases where you’d want to change the request with custom middleware.
  * Handeling Authenticatoin, Autherization
  * Data Manegment 
  * parameteres validation

## 2. True or false: The route handler is middleware?
  false, Route handler is a peice of code, that's make HTTP methods: Get(), Put(), Post() and Delete(). 

##  3. In what ways can a middleware function end the process and send data to the browser?
    * res.send()
    * res.render()
    * res.json()
    *res.end()


## 4. At what point in the request lifecycle can you “inject” middleware?
  #### after creating the requests, and before sending the response, and at any point causes an error.


## 5. What can cause express to error with “Request headers sent twice, cannot start a second response”.
 #### in the finished state, while some functions tries to set statusCode.
