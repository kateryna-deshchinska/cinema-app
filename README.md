# CINEMA-APP
![alt text](https://business.time.com/wp-content/uploads/sites/2/2012/07/200429986-001-e13427097726641.jpg?w=1500&h=1000&crop=1)
#### It's a simple web app that shows logic managing for picture theatre. In this app, depending on user's role, you can have access to pages:
#### For User role:
- GET: /orders
- GET: /shopping-carts/by-user
- POST: /orders/complete
- PUT: /shopping-carts/movie-sessions
#### For Admin role:
- POST: /movies
- POST: /movie-sessions
- POST: /cinema-halls
- GET: /users/by-email
- PUT: /movie-sessions/{id}
- DELETE: /movie-sessions/{id}}
#### For both Admin and Users role:
- GET: /cinema-halls
- GET: /movies
- GET: /movie-sessions/available
#### For all users:
- /register
- /login

#### _The project is based on N-architecture and SOLID principles. There are 3 layers: CONTROLLERS, SERVICE, and DAO._

## TECHNOLOGIES:
- Apache Tomcat
- MySQL
- Spring (MVC, Security, Core)
- Hibernate ORM
- Maven
- Maven Checkstyle Plugin

## SETUP
1. Configure Apache Tomcat ->
2. Install MySQL and MySQL Workbench ->
3. Create a schema in MySQL Workbench ->
4. In the db.properties change the YOUR_URL, YOUR_USERNAME and YOUR_PASSWORD values to the ones you specified when installing MySQL, also change JDBC_DRIVER (for example "com.mysql.cj.jdbc.Driver")->
5. Run application ->
6. You can test app with credentials of this admin : login - admin@i.ua, password - admin123. This user is already injected to our app✨