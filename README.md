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

````json
{
   "restaurants":[
      {
         "id":1,
         "name":"Mission Chinese Food",
         "neighborhood":"Manhattan",
         "photograph":"https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/banner.svg",
         "address":"171 E Broadway, New York, NY 10002",
         "latlng":{
            "lat":40.713829,
            "lng":-73.989667
         },
         "cuisine_type":"Asian",
         "operating_hours":{
            "Monday":"5:30 pm - 11:00 pm",
            "Tuesday":"5:30 pm - 12:00 am",
            "Wednesday":"5:30 pm - 12:00 am",
            "Thursday":"5:30 pm - 12:00 am",
            "Friday":"5:30 pm - 12:00 am",
            "Saturday":"12:00 pm - 4:00 pm, 5:30 pm - 12:00 am",
            "Sunday":"12:00 pm - 4:00 pm, 5:30 pm - 11:00 pm"
         },
         "reviews":[
            {
               "name":"Steve",
               "date":"October 26, 2016",
               "rating":4,
               "comments":"Mission Chinese Food has grown up from its scrappy Orchard Street days into a big, two story restaurant equipped with a pizza oven, a prime rib       cart,and a much broader menu. Yes, it still has all the hits — the kung pao pastrami, the thrice cooked bacon —but chef/proprietor Danny Bowien and executive chef Angela Dimayuga have also added a raw bar, two generous family-style set menus, and showstoppers like duck baked in clay. And you can still get a lot of food without breaking the bank."
            },
            {
               "name":"Morgan",
               "date":"October 26, 2016",
               "rating":4,
               "comments":"This place is a blast. Must orders: GREEN TEA NOODS, sounds gross (to me at least) but these were incredible!, Kung pao pastrami (but you already knew that), beef tartare was a fun appetizer that we decided to try, the spicy ma po tofu SUPER spicy but delicous, egg rolls and scallion pancake i could have passed on... I wish we would have gone with a larger group, so much more I would have liked to try!"
            },
            {
               "name":"Jason",
               "date":"October 26, 2016",
               "rating":3,
               "comments":"I was VERY excited to come here after seeing and hearing so many good things about this place. Having read much, I knew going into it that it was not going to be authentic Chinese. The place was edgy, had a punk rock throwback attitude, and generally delivered the desired atmosphere. Things went downhill from there though. The food was okay at best and the best qualities were easily overshadowed by what I believe to be poor decisions by the kitchen staff."
            }
         ]
      }
   ]
}

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

#### 1600 x 1200
  
  
  ````
  https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/banner.svg
  
  ````
  <img src="https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/banner.svg">
 
  
  
#### 1600 x 1200
  
  
  ````
  https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/_banner.svg
  
  ````
  <img src="https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/_banner.svg">
  
  
### Portrait

#### 640 x 480
  
  
  ````
  https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/portrait.svg
  
  ````
  <img src="https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/portrait.svg">
  
  
#### 640 x 480
  
  
  ````
  https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/_portrait.svg
  
  ````
  <img src="https://raw.githubusercontent.com/Joaosilgo/dummy_db/main/svg/_portrait.svg">
 
  



