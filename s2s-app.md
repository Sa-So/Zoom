# s2s app steps
Link Zoom Account to Organisation 
 

Login to zoom marketplace using a user which has admin/owner/developer privileges for the zoom account 

Click on Build App on top right 
![image](https://github.com/Sa-So/Zoom/assets/60461699/d53debdd-6e44-45db-b1eb-4088fc6f669b)

Select Server to Server OAuth Application  
![image](https://github.com/Sa-So/Zoom/assets/60461699/e7cbd403-b5ae-4d3f-82c3-10814e9f2dd0)

Fill in the required fields 

Select scopes: 
- meeting:read:meeting:admin , meeting:write:meeting:admin , user:write:user:admin , user:read:user:admin 
 
If you don’t see a particular scope the user might not have access to that scope in this account/tenant, ask admin for access. 
 

We might need additional scopes later for getting attendee duration / transcript / report of a zoom meeting. 

Activate the app 

Go to app credentials copy them and share them with Admin. 
![image](https://github.com/Sa-So/Zoom/assets/60461699/d5df96e4-d16b-4ef3-961e-fded42426224)

Admin 

Login to Admin Portal 

Go to organization and search for the organization to link to zoom account 

Edit the org – check the zoom checkbox in video suppliers 

Paste the credentials : account id , client id , client secret there , click save  

Save 
