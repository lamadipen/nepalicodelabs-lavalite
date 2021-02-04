# nepalicodelabs-lavalite
This is CMS for nepalicodelabs

Installation 
Follow the guide line provided in the Lavalite documentation 
with additional step mentioned below to avoid errors.

https://www.lavalite.org/

After successful installation
1. Update the .env file
    update the database username and password manually (if there is sql error)
    if still there is error remove the port number 
2. If there is file not found error 
   copy the default theme from public/themes  
   Then paste in same themes folder
   rename the copied folder to admin, public, user
   this should solve the issue
   test the app by running atrisan serve and navigation to admin, public and user url


