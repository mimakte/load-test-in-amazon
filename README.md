# load-test-in-amazon
A load testing tool:
Java Development Kit (JDK) if using JMeter. 

Installation:
Install the load testing tool of your choice following the official installation guide.
If using JMeter, download the latest version from https://jmeter.apache.org/ and extract the archive to a directory of your choice. 

Configuration:
Configure the load testing tool to point to the correct URL of the application or service.
Set up the test scenarios, including the number of users, ramp-up period, and test duration.
Define the requests and expected responses in your test script.

 Testing:
 1.Home page. https://www.amazon.com/
 2.Login page. https://www.amazon.com/ap/signin?openid.pape.max_auth_age=0&openid.return_to=https%3A%2F%2Fwww.amazon.com%2Fgp%2Fcart%2Fview.html%3Fref_%3Dnav_ya_signin&openid.identity=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.assoc_handle=usflex&openid.mode=checkid_setup&openid.claimed_id=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.ns=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0 
 3.Order page. https://www.amazon.com/ap/signin?openid.pape.max_auth_age=0&openid.return_to=https%3A%2F%2Fwww.amazon.com%2Fyour-orders%2Forders%3F_encoding%3DUTF8%26ref_%3Dnav_orders_first&openid.identity=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.assoc_handle=amzn_retail_yourorders_us&openid.mode=checkid_setup&language=en_US&openid.claimed_id=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.ns=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0 

 Test result Analysis:
 1.10 users cannot enter home page in 1 second.
 2.10 users cannot login in 1 second.
 3.10 users cannot order in 1 second.
 
   
  
