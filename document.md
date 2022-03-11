## Get All Users (GET):
    > http://localhost:8000/api/auth/users
    > Register (POST)
    > {"name":"Shruti", "email":"patelshruti2312@gmail.com", "password":"12345678","role":"User"}
   
## Register (POST):
    > http://localhost:8000/api/auth/register
    > {"name":"Joe", "email":"joe@gmail.com", "password":"12345678", "role":"Admin"}
   
## Login (POST): 
    > http://localhost:8000/api/auth/login
    > (Body) => {"email":"joe@gmail.com", "password":"12345678"}
    > (response) => {"auth": true,"token": "token"}      

## UserInfo (GET): 
    > http://localhost:8000/api/auth/userinfo
    > (Header) => {'x-access-token':'token from login'}
