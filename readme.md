// What is server?
// Computer which is connected to internet and is proframmed to receive requests and give response back is called server


/*  https and http
  1.set of rules(protocols) 
  2.Data ka ana jana
  3.Data is encrypted
 */


// Request->client || Response->Server


/* ports are like gate
 we can connect to server through port
 open and closed port , Running port */


-->What is backend?
Backend developer wo banda hai jo ki server banata hai aur database program karta hai


-->Why backend?
To make websites more usable and purposefull for the users(more personalised) , to make websites dynamic


-->Why not frontend alone?
Frontend websites are static and they are not much use , frontend doesn't provide a sense of uncertainity which hooks users 

-->Install ka mtlb hota hai apke laptop/computer/tablet usmein files ko copy karna from internet 


-->What is node js
Nodejs hai khoob sara c++ ka code jo ki liya gaya hai chrome browser ke v8 engine ka code se aur is c++ code jisko liya gaya usey wrap kar diya gaya js code se and ye hume allow karta hai ke hum js code likhein aur ye js code accept karega and c++ ke basis par aapko ek server environment bana kar dega, par sirf tab tak jab tak ye code chalayega

-->What is npm?
ek jagah hai jaha pe khoob sare packages milte hai i.e like playstore


-->what is express js?
Express ka use case hai routing

-->What is routing?
routes banane ke process ko routing kehte hai
https://www.instagram.com/profile
                         /serach
                         /like

GET->url pe data dikhta hai 
POST->url pe data nhi dikhta hai

-->node vs express
node is the main thing but hum express se bhi server bana sakte hai and server kaise react karega vo bhi express ke help se likh sakte hai

-->Why express?
http is difficut to use, Express makes things easier

-->request and response
-request mai sara data hota hai aane wale user ki request ki taraf se, jaise ki location, device ki info, and other things
-res mai control hote hai jinke basis pe hum server se response bhej sakte hai

(node ke sath ek dikkat hai ki agar control ek bar bhi kisi middleware par gaya to control khud se agle route/middleware par nahi jayega,use agle par lejaane ke liye apko push karna padega)
-next is just a push so that our request moves to the next thing which should be executed

-->What is route parameters?
To make any route dynamic you can use : at he place where you want to make it dynamic, to access there value use req.params.username
eg-books/authors/robin sharma
                /Murakami
                /Whalt whitman
                /Shakespere

  books/authors/:username   

  -->Middleware
  Middleware ek aisa route hota hai jo har route se pehle chalta hai

  -->What is template engine?
  yeh ke style of mark se convert krke html deta hai
  ejs,pug,handlebars,jade
  ejs is very similar to html

  -->Steps to install ejs
  1. npm i ejs -> ejs install
  2. app.set("view engine","ejs");
  3. ek views folder banao usme ejs files banao
  4. send ki jagah render function karo => render ka 

  -->What is static files
  1. create a folder called public
  2. create 3 folders inside it, images, stylesheets, javascripts
  3. configure express static in script.js files
  4. understand the path











