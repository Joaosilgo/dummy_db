# dummy_db
🧪 Dummy Data in Json


## Eg:


#### Request:

[Test](https://joaosilgo.github.io/dummy_db/posts.json)

````
https://joaosilgo.github.io/dummy_db/posts.json

````


#### Response:
````json
[
   {
      "userId":1,
      "id":1,
      "title":"sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
      "body":"quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
   },
   {
      "userId":1,
      "id":2,
      "title":"qui est esse",
      "body":"est rerum tempore vitae\nsequi sint nihil reprehenderit dolor beatae ea dolores neque\nfugiat blanditiis voluptate porro vel nihil molestiae ut reiciendis\nqui aperiam non debitis possimus qui neque nisi nulla"
   },
   {
      "userId":1,
      "id":3,
      "title":"ea molestias quasi exercitationem repellat qui ipsa sit aut",
      "body":"et iusto sed quo iure\nvoluptatem occaecati omnis eligendi aut ad\nvoluptatem doloribus vel accusantium quis pariatur\nmolestiae porro eius odio et labore et velit aut"
   },
   {
      "userId":1,
      "id":4,
      "title":"eum et est occaecati",
      "body":"ullam et saepe reiciendis voluptatem adipisci\nsit amet autem assumenda provident rerum culpa\nquis hic commodi nesciunt rem tenetur doloremque ipsam iure\nquis sunt voluptatem rerum illo velit"
   }
   
   
]


````





#### Request:

[Test](https://joaosilgo.github.io/dummy_db/users.json)

````
https://joaosilgo.github.io/dummy_db/users.json

````


#### Response:
````json

[
   {
      "id":1,
      "name":"Leanne Graham",
      "username":"Bret",
      "email":"Sincere@april.biz",
      "address":{
         "street":"Kulas Light",
         "suite":"Apt. 556",
         "city":"Gwenborough",
         "zipcode":"92998-3874",
         "geo":{
            "lat":"-37.3159",
            "lng":"81.1496"
         }
      },
      "phone":"1-770-736-8031 x56442",
      "website":"hildegard.org",
      "company":{
         "name":"Romaguera-Crona",
         "catchPhrase":"Multi-layered client-server neural-net",
         "bs":"harness real-time e-markets"
      }
   },
   {
      "id":2,
      "name":"Ervin Howell",
      "username":"Antonette",
      "email":"Shanna@melissa.tv",
      "address":{
         "street":"Victor Plains",
         "suite":"Suite 879",
         "city":"Wisokyburgh",
         "zipcode":"90566-7771",
         "geo":{
            "lat":"-43.9509",
            "lng":"-34.4618"
         }
      },
      "phone":"010-692-6593 x09125",
      "website":"anastasia.net",
      "company":{
         "name":"Deckow-Crist",
         "catchPhrase":"Proactive didactic contingency",
         "bs":"synergize scalable supply-chains"
      }
   }
   
]

````





#### Request:

[Test](https://joaosilgo.github.io/dummy_db/db.json)

````
https://joaosilgo.github.io/dummy_db/db.json

````


#### Response:
````json

{
   "posts":[
      {
         "id":1,
         "title":"Post Numero 1"
      },
      {
         "id":2,
         "title":"Post Numero 2"
      },
      {
         "id":3,
         "title":"Post Numero 3"
      }
   ],
   "comments":[
      {
         "id":1,
         "body":"some cool comment",
         "postId":1
      },
      {
         "id":2,
         "body":"some cool comment",
         "postId":1
      }
   ],
   "profile":{
      "name":"João Gomes"
   }
}
````


## Basic Usage

### Fetch API

The Fetch API provides an interface for fetching resources (including across the network). It will seem familiar to anyone who has used XMLHttpRequest, but the new API provides a more powerful and flexible feature set.


````javascript
// Replace  with your JSON feed
fetch('https://joaosilgo.github.io/dummy_db/posts.json')
  .then((response) => {
    return response.json()
  })
  .then((data) => {
    // Work with JSON data here
    console.log(data)
  })
  .catch((err) => {
    // Do something for an error here
  })
  
  ````
  


### XMLHttpRequest (XHR)

XMLHttpRequest (XHR) objects are used to interact with servers. You can retrieve data from a URL without having to do a full page refresh. This enables a Web page to update just part of a page without disrupting what the user is doing. XMLHttpRequest is used heavily in AJAX programming.

````javascript
var url ='https://joaosilgo.github.io/dummy_db/posts.json';
var req = new XMLHttpRequest();
req.responseType = 'json';
req.open('GET', url, true);
req.onload = function () {
    var jsonResponse = req.response;
    console.log(jsonResponse);
    // do something with jsonResponse
};
req.send(null);

  ````
  
  
  
  ## Mockup Images
  
  ### Banner
  
  ````
  https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/banner.svg
  
  ````
  <img src="https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/banner.svg">
 
  


