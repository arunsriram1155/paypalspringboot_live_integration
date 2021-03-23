# paypalspringboot_live_integration

  Note : This code is for Complete Backend Integration and Sending Json Response Through Postman  - Post method  and  http://localhost:9090/pay
   Json Body 
  {
    "price":2,
     "currency":"INR",
     "method":"paypal",
    "intent":"sale",
    "description":"testing"
    }
      
![image](https://user-images.githubusercontent.com/54494367/112153565-67437300-8c09-11eb-8520-416489e58f41.png)

      
  Two Types of Modes in Paypal Integration 
    1) Sandbox (for Testing) 
    2) Live
    
   ---   Here I am Using Live mode   ----- 
    
 Application Properties : 
 
 server.port: 9090
 paypal.mode=live       // sandbox 
 paypal.client.id=    // Get the client Id and CLient Secret From paypal Developer Account 
 paypal.client.secret=  

 
   // Sandbox Mode 
   
  1) Get the client Id and client Secret from sandbox accounts of the business (seller account ) to whom you want to pay / send money
  2) for login sandbox - Sandbox (Fake) login email and password 
  https://developer.paypal.com/developer/accounts/
  
   ![image](https://user-images.githubusercontent.com/54494367/112149587-28132300-8c05-11eb-8491-99687e2f00b7.png)
  3)  For Credit Card Validation in Sandbox account 
  https://developer.paypal.com/developer/creditCardGenerator/
   Create Fake from Paypal and Update  the CVV and card Number in Your Paypal Sandbox account . 
   ![image](https://user-images.githubusercontent.com/54494367/112150209-d74ffa00-8c05-11eb-88b0-b5cc817f2d43.png)



 



 4) Now you can get The success reponse object from Paypal
   
Live Mode:
  In aplication Properties change to Live Mode 

    Create Order Database and here we are storing the each Orders in Db - Mysql
-------------------------
 
 Source Video  : https://www.youtube.com/watch?v=GykDyG0ELms
 
 Source Link : https://github.com/Java-Techie-jt/spring-boot-paypal-example
 
 
