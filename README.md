# Machine Coding
- Design subscription-based sports website which can display scores, game status, history for any games.
- Design for online card game say like poker or any other game. 
- Design Truecaller.
- Design a geographically partitioned multi-player card game, that supports multiple players, multiple games at a time.
 Each game will have one contractor like ones we have in a bar, He can play a game or just watch it. Integrate payment systems.
 - design a system to fast lookup cars on the market according to the user's geo-position.
 - Design an airport service that will be used to allocate a free runway when the plane is about to land. Data structure for the same. What if the runway is not available? Message passing between control center and the plane. Focus on low-level design and code. Can the same runway be allocated to two different planes (locking)? Database storage needed?
 - Design a Ride Sharing Application where drivers can offer rides (origin, destination, no of seats), riders can request rides ( origin, destination, no of seats) and there is an algo to decide which driver should be given the trip in case of a collision ( maximum overlapping one).
 - Design a task planner. Different types of tasks are present – bug, feature and story. And their attributes are given. Also a Sprint which is a collection of tasks.
- Implement a finite state machine.
– The machine should have one start state and can have multiple end states.
   - It should be extensible (I should be able to add any number of states or transitions at any time)
   - I should be able to set notifications on or off for any state or for the whole state machine
- Design a system like Jira. It should have the following functionalities :
  - User should be able to create Task of type Story, Feature, Bugs. Each can have their own status.
  - Stories can further have subtracts.
  - Should be able to change the status of any task.
  - User should be able to create any sprint. Should be able to add any task to sprint and remove from it.
    - User should be able to print
    - Delayed task
    - Sprint details
    - Tasks assigned to the user
- Design a stock exchange system. There is a list of stocks given with following attributes 
  - order_id
  - time
  - stock name
  - type(BUY/SELL)
  - quantity
  - price
  
  You need to output list of stocks in the following format sell_id, buy_id, quantity, price which will get executed. 
- code a TextPad with following functionality:
  - display() – to display the entire content
  - display(n, m) – to display from line n to m
  - insert(n, text) – to insert text at line n
  - delete(n) – delete line n
  - delete(n, m) – delete from line n to m
  - copy(n, m) – copy contents from line n to m to clipboard
  - paste(n) – paste contents from clipboard to line n
  - undo() – undo last command
  - redo() – redo last command
  
   expected the textpad to be in memory(not as file) and also  expected to handle error gracefully and the program to be menu driven.
- Design Car Rental System like Zoomcar.
- Design a billing and auctioning system similar to EBay.
  Ebay is a multinational e-commerce corporation, facilitating online consumer-to-consumer and business-to-consumer sales. The website is free to use for buyers, but sellers are charged fees for listing items and again when those items are sold. The sellers aution their items and buyers bid on items.
- Design Q&A application as in Amazon,Walmart has it for each product.
- Design push notification :
  - Which sends the notification to the registered users
  - Which receives an event from promotions team
  - Sends notification to iOS, android or sends an email or all three
- Design a suggestion system
- Design and Implement a Simple Java GC (Java 7+)
  - A heap which represents JVM when a Java program starts.
  - At least three parts in the heap that represent Eden Space, Tenured Space and Perm Space.
  - Different rounds of garbage collecting in these above three spaces (checking all objects to see if they have any live references at all, if not, kill them, reclaim the allocated memory, otherwise, move them to later spaces..)
- Design LinkedIn.
- Design a video upload system for a user with low network bandwidth
  
  User has to upload video which is more than 1GB. Users network bandwidth is too low. Network get dropped after 50% upload. User tries again and same thing happens. Now to design an optimized efficient solution to address this issue.
- Design Learning Management System 
-  Design Survey similar to Google Forms / SurveyMonkey.
- Design Logging Framework
- Design a locker
  
  To monitor the process of how to put the package into a right locker. and one locker for one package. your package and locker have different size, you need to make sure the locker size > package.
- Design a calendar Application (similar like Google Calendar)
   -Ability to create, update, delete an Event
     - An event would typically consist of {start, end, location, Owner, user-list, title}.
     - Events can either be like meetings(with a dedicated location and appropriate guest-list) or as well be like holidays, birthdays, reminders etc.
     - An event once created, can be either accepted or rejected by the constituent users - if neither it should be in neutral state.
  - Get Calendar for a user Ui
  - Get Event details.
  - For a given set of users[U1, U2,....Un] identity a common free slot of time.

- Design Guitar Inventory System
- Desing Payment System
- Design a stock trading system
- Design Payment Gateway like Razorpay.
- Design a Json Parser from scratch
  - It is coming from untrusted source (meaning validation of json is required)
  - the key will always be string the value can be string or another key value pair.
  - Sample input {'abc':{'d':'ef','r':'er'}} -- map.get("abc").get("d") should return "ef".
  - No other type i.e. integer or boolean or array in the json
  - Validation and parsing must in done simultaneously
  - In case of invalid json string throw exception
- Design Chat Based application like whatsapp/wechat.
- Design a home automation sytem to remotely control all the switches, devices in a home. 
- Design Maps Navigator Client for different transportation types
   - Design a maps path-building navigator client.
   - User should be able to build path from point A to point B using your code.
   - design should support different transportation methods for example: walk, car, bus, bike.
 - Design Meeting Scheduler
    - Here there are n given meeting rooms. Book a meeting in any meeting room at given interval(starting time, end time). Also send notifications to all person who are invited for meeting.
    - You should use calender for tracking date and time. And also history of all the meetings which are booked and meeting room.
write an API for client who will give date and time and API should return meeting room with booked scheduled time. client should also query for history of last 20 booked meetings.
    - Is meeting room available? etc
 - Design and Implement a logger library that applications can use to log messages.
- Design a configuration management system
  - User should be able to add configuration
  - User should be able to delete configuration
  - User should be able to search for configuration
  - User should be able to subscribe to Configuration So that any updates in configuration will gets notfied to user
- Design Amazon comments filtering system
- Design a Vending Machine
  - Add items to the vending machine in fixed number of slots
  - Payment using card or cash
  - Select item to dispense
-  Design Splitwise.
- Design Mock Interview System like pramp.
- Design Application Tracking System (ATS) like greenhouse
- Design a Logistics System
- Design CSV parser
- Design message queueing system
  - Create your own queue that will hold messages in form of JSON. Standard library queues were not allowed.
  - There was one publisher that can generate messages.
  - There are mutiple suscribers that will listen messages satisfying a particular regex.
  - Suscribers should not be tighly coupled to system and can be added or removed at runtime.
  - When a suscriber is added to the system, it registers callback function along with it. And this callback function will be invoked in case some message arrives.
  - There can be dependency relationship among suscribers i.e if there are two suscribers say A and B and A knows that B has to listen and process first, then only A can listen and process. There was many to many dependency relationship among suscribers.
   - There must a retry mechanism for handling error cases when some exception occurs in listening/ processing messages, that must be retried.
- Design Employee Management Platform which includes payroll,IT,employee benefits and all other employee operations in one place.
- Design User Engagment platform.
- Design product experience platform like pendo.
- Design Chess Game.
- Design Live Auction platform for IPL / EPL.
- Design Unit Testing Application
- Design Browser testing Application like browserstack / sauce labs.
- Design Real time collaboration application for the teams.
- Design Visual workplace for remote teams.
- Design Online UML Diagram Tool like lucidchart.
- Design Parking Lot.
- Design online audio/video file downloader.
- Design Inventory System.
- Design Warehouse Management System.
- Design Game Streaming platform.
- Design Real-Time Translation platform.
- Design Community based discussion platform.
- Design application for restaurant / malls to efficiently handle waiting queue and optimizely assign the table.
- Design online assesment platform for exam's like gre / tofel.
- Design online customer verifaction platform for digital on-boarding(KYC) of the users for bank and others client's.
- Design Secure Content Management platform.
- Design Freelancing hiring platform.
- Design monitoring and alert system for the production as well and other enviroments.
- Design digital-video KYC (know your customer) verification system.
- Design online e-fiiling online income tax returns service.
- Design job posting system dedicated to blue and grey collar workers. (multiple langs / native lang)
- Design System Simiar to the Product-hunt (share and discover new products)
- Design service like Clipboard. (try to store the maximum clips)
- Design system for salary info,comparsion and other info similar to the glassdoor salary / salarry.level.
- Design pricing / product comparision system.
- Design Virtual Event Platform for Communities / Enterprise.
- Design system for short video/content sharing like Tiktok.
- Design Short Story Telling (Text/Images) platform like Terribly Tiny Tales.
- Design a user activity tracking system for user on mobile.
- Design in-memory (Questions like write to add,remove the table,etc).
- Design a login API which is secure even if SSL certification is compromised.
- How to design an API whose response will have the response from 3 other different microservices.
- Design system which exposes two APIs: 
    1) Save Numbers : which takes N integers and saves in backend 
    2) GetMedian: Returns median of the numbers stored so far. [Most Frequent Op]
- Design a torrent service, end to end.
- Design system like Bigbasket (local retailer's).
- Design a limit order book for trading system.
- Design a Cache Mechanism.
- Design a personal stock / investment protfolio system.
- Design a electronic signature system like DocuSign / EasySign.
- Design a generic coupon/promocode system.
  - Coupon can give minimum Z% off upto X amount  (with or without min cart size)
  - Coupon can give flat discount of X (with or without min cart size)
  - Coupon can be applicable for one/few/all customers
  - Coupon can be applicable on one/few/all merchants
  - Coupon can be used only one time/few time/everytime. 

- Design of a quizzing app. 
- Design a system (initially one node/server) that could handle requests on the scale of millions. It should return a unique id for each request (The id   should be unique in sense that there would be only one such id ever generated).
- Order-Management-System-or-System-Design.
- Implementation of Kafka.
- Design and Implement Rocksdb.
- Design and Develop the Zookeeper using Rocksdb and Google's BigTable.
- Developing a message queueing system.
  - Create your own queue that will hold messages in the form of JSON(Standard library with queue implementation were not allowed).
  - There can be more than one queue at any given point of time.
  - There will be one publisher that can generate messages to a queue.
  - There are multiple subscribers that will listen to queues for messages.
  - Subscribers should not be tightly coupled to the system and can be added or removed at runtime.
  - When a subscriber is added to the system, It registers a callback function which makes an API call to the given end point with the json payload, this       callback function will be invoked in case some message arrives.
  - Subscriber can consume the messages in batches if the queue has more than one message and it should be configurable.
  - There must be a retry mechanism for handling error cases when some exception occurs in listening/processing a message, that must be retried.
- Design a service to view/add/remove viewers of a document (like the feature in google doc).
- Design an Online Auction.
  - An auction is initiated by a seller and consists of a single product. It starts from 0$ and buyers can keep bidding(always at least current_winner + a      predefined increment) until it expires.
  - The seller can define a reserve price. Its presence is visible, but the actual amount is not. If defined and the final bid is less than the reserve        price, the auction will fail with a separate status.
  - Bidders might also make use of an autobidding system. Given a maximum value, each time the user is outbid, the system will automatically try to bid on      behalf of the user with the smallest value possible(the predefined increment above will be used to reach this value; calculation must strictly follow      it), up until the maximum value has been reached.
  - The autobidding algorithm must be efficient time complexity wise.
  - Once an auction completes, an external system will be notified of the result together with the winner(if any).  
- Design for storing chemicals with their constituents in an efficiently retrievable format.
- Design and Architecture - Appointment booking for a hospital where each doctor can open slots independently of any time period.
- Design Online Exam Portal.
  - On exam completion total score and subject wise score calculation (make sure u consider negative marking).
  - On exam completion Rank calculation.
  - Provision for MOCK tests (users should get hypothetical ranks by comparing previous year results)
  - A pre-exam (with limited users ~10k) to mimic actual exam and then give generalised ranks for more users(in millions).
- Build the Google Stock Wizard. 
- Design the Food Ordering System like Swiggy/Zomato.
- Design the Bill Summary Feature.
- Design Learning app (Design system where teachers can upload the content and stuedents can view that content.)
  - Teachers should be notified once their content is uploaded.
  - Upload should continue even if browser is closed in case it is a browser upload. 
- Design Navigation Alerts System. (Similar like Google Map Functionality.)
-  Design a system which improves the quality of the data. 
   - A system which takes a large amount of data, cleans it, adds specified properties to it and sends the results so that the other services can filter the data with the newly added properties.  

- Design a Plagiarism checker.
- Design a distributed Cache.
- Design a business rule based engine.
- Design Authentication/Authorization Service which supports(otp,OAuth, etc.).
- Design a SMS validator system.
- Design(HLD) Zipkin - A request tracing system for distributed applications. Example - A request is flowing through multiple microservices, system   should be able to trace the time spent by the request and sequence followed by it. 
- Design Ads system for a website.
- Design an online code judge.
- Design Splunk like log manager system supporting queries with filters on last min, hr, day, week etc.
- Design Linkedin Suggest connections feature.
- Implement a wide column store like Cassandra (bonus : support secondary indexes).
- Create an online music recommendation system which suggests songs according to user taste.
   - Application has two major things :
         - The songs, which are cataloged in the app’s data store. Songs can be described by attributes such as genre, tempo, singer.
         - The people : Each person has a playlist of songs that they can choose to play from.

          - Design a system that recommends a set of songs from our music library to the user based on his preferences (matching genre / singer/ tempo)             taking into account his current playlist.
          - Pick a song based on the following order:
          - One which matches with maximum matching attributes.
          - When only one attribute is matching, pick one in the following order : genre > singer > tempo.
          - To decide priority between two genres\singer\tempo, consider the number of songs in each category in the user's playlist to decide which               song gets more priority. One with a higher number of songs gets high priority. If the number of songs are the same, show in any order. 
          - 
- Design a test taking website type service where user can register/login,
  - give the test and can see their past test score and rankings. 
  - Test can be of multiple types and questions in test can be of multiple type (mcq, yes/no, fill in the blanks, multiple correct options) with the questions can being both image and direct string. 
  - Questions should be unique to every user in a particular test and in case of user being dropped from the test (bad internet or anything) he can resume the test from where he left provided he came before his test timer was off.
- Design a service for showing HeatMap of Swiggy / Zomato agents at a time.
- Design Webhook Dispatcher.
- Implement service to Find the recently viewed listings on the website by the user. Example a user looked for hotels in Bangalore. Design a system responsible to return the recent listings for a user.
- Design a Jackpot Machine.
- Designing a ID card system which employees use to access any zone/premises.
- Design a Bar Graph Library.
- Notification Service design. 
  - Design a notification service for swiggy which takes in a list of users and message and notifies them . Users could be of different types like         delivery men , swiggy employees, end user of App.
- Gym Managment System.
  - Design a backend system for a new enterprise application that Flipkart is launching, FlipFit.
    Flipkart is partnering up with gyms across Bangalore to enter into the fitness space. For the Beta launch the requirements are as follows:
      - There are only 2 centers for now - Koramangala and Bellandur. We might expand to multiple others if we get traction.
        Each center has 6 slots. 3 in the morning of an hour each from 6am to 9am and similarly 3 in the evening from 6pm to 9pm. The centers are open.         7 days a week.
      - Each slot at a center can have only 2 possible workout variations for now - Weights and Cardio.
      - The number of people that can attend each workout at each slot for a given station is fixed. Assume default slot capacity as 3(for every               workout type across centers).
      - Same User cannot book at the same center at the same slot and the same workout type twice.
      - User can perform the following operations:
      - Register onto the platform
      - View the workouts for a particular day
      - Book a workout for a user if seats are available in that time slot at that center
      - View his/her plan based on day as input
      - For simplicity’s sake you can assume that the workout info will be entered by the Admin only once.

      - Bonus : Build an Admin view as well to modify the workout info at a center/slot level.
-  Design an concurrent History tracking system where we can store and track history of registered entities. We should be able to onboard service and      their entities to our system and start tracking changes being made to them.
-  Design a scheduler, that takes in 10 scheduling requests at a time and can execute 100 jobs at a time.(The scheduler executes http requests.)
-  Design a system which keeps track of leaders for some contest. Like referrals leader.
-  Design a key value store and an Index. 
-  Design an analytics to display machines which have valid certificates,Design the system with valid dashboard with all the machines with good/bad        certificates.
-  Design a service that calls any passed endpoint at a fixed interval.
-  Design System where User can create alerts on StockOptions.
   - Raise an Alert When "APPL" stock transaction happens for more than $100.
   - Raise an Alert When "GOOGL" stock transaction happens for less than $40.
   - ou have one black-box Api say market-api

   - you can call for particular stockoption and data will keep on flowing for that stockoption in form of say json , and will keep on flowing ; like below json

				{
					string company;// Apple
					double price; // 134.22
					int nb_shares;//100
					long timestamp;//24542212
				},...
    
- Design a UUID generator.
  - Design a system that is incrementally scallable upto 1000 unique ID requests per second each by 1000 devices per person, for every human on the earth for 100 years.
  - Consider:

          10^10 - number of people on the planet
          10^10 - number of second in 100 years
          10^7 - max requests per second per server serviceable.
- Design a scalable weather service that pulls data from an API.
- You are required to implement an in-memory cache module/library which you will embed in your application to improve the application performance, by holding heavily accessed (read/written) application specific objects. To start, we would begin with following minimal requirements.
   - Your cache module should be generic, re-usable and easy to integrate across various modules within your production/organization.

   - The cache will be bounded by a fixed capacity (number of items) for holding the objects, which will be mentioned during early initialization of the p        program.

   - Upon hitting the capacity, the cache module can invoke one of various cache eviction strategies to make room for newer objects. You are required to          incorporate cache eviction in your code to handle aforementioned condition.

   - You could choose to implement various cache eviction strategies such as 'Least recently used', 'Least frequently used', 'time based expiration'et.al

   - In one of our unique use cases, we would like to change the eviction policy of the cache during runtime and the cache should start evicting keys based on the new eviction policy set.

- Design library management system. 
  - Any library member should be able to search books by their title, author, subject category as well by the publication date.

  - Each book will have a unique identification number and other details including a rack number which will help to physically locate the book.

  - There could be more than one copy of a book, and library members should be able to check-out and reserve any copy. We will call each copy of a book, a book item.

 - The system should be able to retrieve information like who took a particular book or what are the books checked-out by a specific library member.

 - There should be a maximum limit (5) on how many books a member can check-out.

 - There should be a maximum limit (10) on how many days a member can keep a book.

 - The system should be able to collect fines for books returned after the due date.

 - Members should be able to reserve books that are not currently available.

 - The system should be able to send notifications whenever the reserved books become available, as well as when the book is not returned within the due date.

 - Each book and member card will have a unique barcode. The system will be able to read barcodes from books and members’ library cards.

-  Design an API rate limiter.

# Solutions

Question | Solutions | Videos 
| :---:   | :-: | :-: 
|Design True caller |[Solution-1](https://github.com/gopalbala/truecaller) | [Video-1](https://www.youtube.com/watch?v=3KSLh_hvwtQ)  | 
|Design Snake and Ladder Game| [Solution-1](https://github.com/gopalbala/snake-and-ladder) [Soluton-2](https://workat.tech/machine-coding/article/how-to-design-snake-and-ladder-machine-coding-ehskk9c40x2w#:~:text=%2D%20The%20board%20will%20have%20100,random%20number%20on%20rolling%20it.&text=%2D%20After%20the%20dice%20roll%2C%20if,contains%20some%20snakes%20and%20ladders.) [Solution-3](https://www.geeksforgeeks.org/design-snake-and-ladder-game-using-python-oops/) | [Video-1](https://www.youtube.com/watch?v=5LDfqzXwxxU&t=2041s) [Video-2](https://www.youtube.com/watch?v=OutDY_ICb80)|  | 
|Design Bill Sharing/Expense Sharing like Splitwise| [Solution-1](https://github.com/gopalbala/billsharing)  [Solution-2](https://workat.tech/machine-coding/article/how-to-design-splitwise-machine-coding-ayvnfo1tfst6)| [Video-1](https://www.youtube.com/watch?v=2Fz_LQJuq7s) 
| Design Amazon Locker Service | [Solution-1](https://github.com/gopalbala/amazonlocker) [Solution-2](https://leetcode.com/discuss/interview-question/object-oriented-design/260467/Amazon-or-Design-a-locker)| [Video-1](https://www.youtube.com/watch?v=hsx562pXWS8&t=209s) 
| Design Vehicle / Car Rental Application like Zoomcar | [Solution-1](https://github.com/gopalbala/carrental)| [Video-1](https://www.youtube.com/watch?v=kQ8MwyESL_k&t=4542s) 
| Design Distributed Id Generation like Twitter Snowflake id | [Solution-1](https://github.com/gopalbala/distributed-idgen)| [Video-1](https://www.youtube.com/watch?v=ubxRZx-T2Bc)
| Design In-memory data streaming service| [Solution-1](https://medium.com/@tg6897/design-in-memory-streams-e47e49068028)
| Implement a logger | [Solution-1](https://github.com/coding-parrot/projects/blob/master/java-projects/src/main/java/logger/LogClient.java) | [Video-1](https://www.youtube.com/watch?v=FKA2KgkkcqY)
| Cab Booking like Uber, Ola | [Solution-1](https://github.com/anomaly2104/lld-cab-booking-ola-uber-grab-lyft) | [Video-1](https://www.youtube.com/watch?v=Yn7C0x5ozx4&t=3s)
| Design Parking lot system | [Solution-1](https://github.com/anomaly2104/lld-parking-lot) [Solution-2](https://github.com/gopalbala/parkinglot) | [Video-1](https://www.youtube.com/watch?v=7IX84K9g23U) [Video-2](https://www.youtube.com/watch?v=nnpT0WXifLk) 
| Design Chess Game | [Solution-1](https://github.com/anomaly2104/chess-low-level-system-design) [Solution-2](https://www.geeksforgeeks.org/design-a-chess-game/)  | [Video-1](https://www.youtube.com/watch?v=RVHNcng0oF0) [Video-2](https://www.youtube.com/watch?v=yBsWza2039o)
| Design Cache system | [Solution-1](https://github.com/anomaly2104/cache-low-level-system-design) | [Video-1](https://www.youtube.com/watch?v=B7iCXl_KSoM)
| In-Memory DB with indexing| [Solution-1](https://medium.com/@tg6897/design-in-memory-db-with-indexing-52d33adceb91)
|Design an online book reader system | [Solution-1](https://www.geeksforgeeks.org/design-an-online-book-reader-system/) [Solution-2](https://leetcode.com/discuss/interview-question/object-oriented-design/124750/Design-an-online-book-reader-system) | - 
| Design an online hotel booking system | [Solution-1](https://www.gohired.in/2020/02/03/system-design-designing-a-lld-for-hotel-booking/) [Solution-2](https://www.geeksforgeeks.org/design-online-hotel-booking-system-like-oyo-rooms/)| [Video-1](https://www.youtube.com/watch?v=u0W2ckqmb_U&feature=emb_title) 
| Design a Logistics System | [Solution-1](https://www.geeksforgeeks.org/design-a-logistics-system/) | - | - | -
| Design Tic Tac Toe | [Solution-1](https://www.geeksforgeeks.org/implementation-of-tic-tac-toe-game/) [Solution-2](https://medium.com/@pelensky/java-tic-tac-toe-command-vs-factory-pattern-3fb141046145) | [Video-1](https://www.youtube.com/watch?v=gktZsX9Z8Kw&t=280s) [Video-2](https://www.youtube.com/watch?v=yBsWza2039o)
|Design a configuration management system | [Solution-1](https://leetcode.com/discuss/interview-question/object-oriented-design/373887/Amazon-or-System-Design-or-A-configuration-management-system) | - 
 | Design a Vending Machine | [Solution-1](https://leetcode.com/discuss/interview-question/object-oriented-design/313579/Amazon-or-Onsite-or-Design-a-Vending-Machine) | - 
 | Design Maps Navigator Client for different transportation types (OOD)| [Solution-1](https://leetcode.com/discuss/interview-question/object-oriented-design/508056/OOD-Design-Maps-Navigator-Client-for-different-transportation-types)| -
 | Design a Json Parser from scratch | [Solution-1](https://abhinavsarkar.net/posts/json-parsing-from-scratch-in-haskell/) [Solution-2](https://www.infoq.com/articles/HIgh-Performance-Parsers-in-Java-V2/)[Solution-3](https://notes.eatonphil.com/writing-a-simple-json-parser.html) | -
 |Design Elevator | [Solution-1](https://medium.com/system-designing-interviews/design-a-elevator-system-fc5832ca0b8b) [Solution-2](https://leetcode.com/discuss/interview-question/object-oriented-design/124660/ood-design-elevator) [Solution-3](https://massivetechinterview.blogspot.com/2015/07/thought-works-object-oriented-design.html)
| CricInfo/Cricbuzz |[Solution-1](https://github.com/naval41/Low-Level-Design/tree/master/CricketPortal/src/com/codemate/cric) [Solution-2](https://github.com/gopalbala/cric-score)| [Video-1](https://www.youtube.com/watch?v=VDqwCo6lhkY&list=PLAC2AM9O1C5KioUMeH9qIjbAV_RMmX8rd&index=6) [Video-2](https://youtu.be/ZTZaUYFqLNw) 
| TikTok| - | [Video-1](https://www.youtube.com/watch?v=vpa2vQdF-AI&t=2031s)
| Pinterest | - | [Video-1](https://www.youtube.com/watch?v=TlkTbkM69ns)
| Movie Ticket Booking | [Solution-1](https://github.com/anomaly2104/ticket-booking-low-level-system-design) | [Video-1](https://www.youtube.com/playlist?list=PL564gOx0bCLpAL7yMJqOuK3_hBuLkyRhn)|
| Uber Eats/ Door dash/ Swiggy| [Solution-1](https://github.com/mayankbansal93/lld-food-delivery-zomato-swiggy) | [Video-1](https://www.youtube.com/watch?v=LePt0PUKIjE&list=PLHNJ91XSF3wzT6BaLVi4WbnuHcfZSXMek&index=5)
| e-Commerce Review System| [Solution-1](https://github.com/gopalbala/reviews) | [Video-1](https://www.youtube.com/watch?v=bKiCkExbe-Y)

### Flipkart Machine Coding Round: FLIPMED

##### Description:
We are required to build an app that lets patients connect to doctors and book appointments. The day is divided into time slots of 60 mins each, starting from 9 am to 9 pm. Doctors can login to the portal and declare their availability for the given day in terms of slots.  Patients can book appointments/ cancel existing appointments. For simplicity you can assume that the doctors’ availability is declared for that particular day only. 

##### Features:
A new doctor should be able to register, and mention his/her speciality among (Cardiologist, Dermatologist, Orthopedic, General Physician)
A doctor should be able to declare his/her availability in each slot for the day. For example, the slots will be of 60 mins like 9am-10am, 11am-12pm..
Patients should be able to register. Patients should be able to search available slots based on speciality. Any order of slots is okay for viewing to patients. 
Patients should be able to book appointments with a doctor for an available slot.A patient can book multiple appointments in a day.  A patient cannot book two appointments with two different doctors in the same time slot.
A patient/doctor should be able to view his/her booked appointments for the day.  

##### Bonus requirements:
Patients can also cancel an appointment, in which case that slot becomes available for someone else to book.
Different ranking strategy - use rating of doctor as a strategy to display a list of available doctors for a given specialization.
The slots should be displayed in a ranked fashion. Default ranking strategy should be to rank by start time. But we should be able to plugin more strategies like Doctor’s rating etc in future.

##### Other Notes:
Do not use any database or NoSQL store, use in-memory data-structure for now. 
You are free to use any language of your choice.
Do not create any UI for the application.
For demo purposes, write a driver class which will execute all the commands at one place in the code and have test cases to test multiple users.
Work on the expected output first and then add good-to-have features of your own.
Please prioritize code compilation, execution and completion.

##### Expectations:
Make sure that you have working and demonstrable code.
Make sure that code is functionally correct.
Code should be modular and readable.
Separation of concern should be addressed.
Code should easily accommodate new requirements with minimal changes.
Code should be easily testable.
Code should have proper error handling
