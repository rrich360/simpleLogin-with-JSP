# simpleLogin-with-JSP


This is a simple JSP servlet Login example using Tomcat Server and Eclipse EE. 





A Simple Jsp Servlet Login Example using Tomcat server and Eclipse. This Example contains a Jsp login form, which 
when submitted goes to a Servlet. In the servlet the login credentials are checked, and then the user is redirected
to a member page on successful login else redirected to the error page.


The following code is an example of the POST method used in JSP, which represents the CREATE operations. Essentially, 
it’s used to request that the origin server accept the entity enclosed in the request as a new subordinate of the resource. 
In other words, it allows the user to go to another servlet referenced by “action=” when clicking the submit button on the form.




![1 0- doPOST()](https://user-images.githubusercontent.com/20470279/60327611-54c7d700-995a-11e9-9192-e8891a8a86da.JPG)



You have to create a class that extends HttpServlet so you can utilize the doPost ( ). This method checks the validation of the
username and password while sending a response to either receive access to the “member” page or be redirected to the “error” page.


![2 0](https://user-images.githubusercontent.com/20470279/60327680-85a80c00-995a-11e9-8285-35f60d1edb71.JPG)


The following is the output of when a user enters the right credentials and when the user enters the incorrect credentials : 

![3 0-simpleLogin](https://user-images.githubusercontent.com/20470279/60327743-acfed900-995a-11e9-8377-db495991a725.JPG)
![3 1-usernameAndPassword](https://user-images.githubusercontent.com/20470279/60327748-af613300-995a-11e9-898c-736eef3ca86d.JPG)

The following is the output of when the user enters the correct username and password :

![3 2-successful login](https://user-images.githubusercontent.com/20470279/60327750-b12af680-995a-11e9-9523-a5207d168d5b.JPG)

The following is an example of when the user enters the wrong username and password : 

![3 3-incorrect login](https://user-images.githubusercontent.com/20470279/60327753-b38d5080-995a-11e9-8589-6e9d5c63fc1b.JPG)


