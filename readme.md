1. create Mysql DB: sso
2. run query: grant all privileges on sso.* to 'root'@'localhost' identified by '123456';
3. mvn clean package
4. run com.test.login.LoginApplication
5. run com.test.resource.ResourceApplication
6. run com.test.web1.Web1Application
7. run com.test.web2.Web2Application
8. http://localhost
9. login username and passwork: user