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

 

   
 Source Video  : https://www.youtube.com/watch?v=GykDyG0ELms
 
 Source Link : https://github.com/Java-Techie-jt/spring-boot-paypal-example
 
 
