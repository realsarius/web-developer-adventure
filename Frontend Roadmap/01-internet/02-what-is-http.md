# What is HTTP?

The Hypertext Transfer Protocol (HTTP) is an Session layer protocol for distributed, collaborative, hypermedia information systems.[1] HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access, for example by a mouse click or by tapping the screen in a web browser.

# In Short

Hyper Text Transfer Protocol. Communication between web servers & clients. HTTP Requests / Responses. Loading pages, form submit, Ajax calls

-> HTTP is stateless - Doesn't remember the previous page

### Hyper Text Transfer Protocol Secure

Data sent is encrypted with SSL(Secure Socket Layer) / TLS(Transport Security Layout)

We can do this by installing certificate on web host.

### HTTP Methods

#### GET

Retrieved data from the server -> Loading html page, assests, css, images, xml data or so on.

#### POST

Submit data to the server -> submiting a form. We are sending data to the server.

#### PUT  

Update data already on the server. -> Editing the blog post, change the image or text

#### DELETE

Deletes data from the server.

### HTTP Header Fields

| General | Response | Request |
| ----------- | ----------- | ----------- |
| Request URL | Server | Cookies |
| Request Method | Set-Cookie | Accept-xxx |
| Status Code | Content-Type | Content-Type |
| Remote Address | Content-Length | Content-Length |
| Referrer Policy | Date | Authorization |
| | | User-Agent |
| | | Referrer |

### HTTP Status Codes

#### 1xx : Informational

Request recieved / processing

#### 2xx : Success

Succesfully Recieved, understood and accepted

#### 3xx : Redirect

Further action must be taken / redirect

#### 4xx : Client Error

Request does not have what it needs - Server needs name field

#### 5xx : Server Error

Server failed to fulfil an apparent valid request

>200 - OK<br>201 - OK created<br>301 - Moved to new URL<br>304 - Not modified<br>400 - Bad Request<br>401 - Unauthorized<br>404 - Not foundation<br>500 - Internal server error
