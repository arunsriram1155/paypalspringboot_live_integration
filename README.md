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
      
     ![image](https://user-images.githubusercontent.com/54494367/112147993-55f76800-8c03-11eb-9c5f-376d33e869c1.png)
      
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
   Create Fake from Paypal and enter the CVV and card Number 
   4) Now you can get The success reponse object from Paypal
  

   
 Source Video  : https://www.youtube.com/watch?v=GykDyG0ELms
 
 Source Link : https://github.com/Java-Techie-jt/spring-boot-paypal-example
 
 
