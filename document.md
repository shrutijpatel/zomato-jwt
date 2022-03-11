## Get All Users (GET):
    > http://localhost:8000/api/auth/users
    > https://zomato-jwt.herokuapp.com/api/auth/users
   
## Register (POST):
    > http://localhost:8000/api/auth/register
    > https://zomato-jwt.herokuapp.com/api/auth/register
    > {"name":"Joe", "email":"joe@gmail.com", "password":"12345678", "role":"Admin"}
   
## Login (POST): 
    > http://localhost:8000/api/auth/login
    > https://zomato-jwt.herokuapp.com/api/auth/login
    > (Body) => {"email":"joe@gmail.com", "password":"12345678"}
    > (response) => {"auth": true,"token": "token"}      

## UserInfo (GET): 
    > http://localhost:8000/api/auth/userinfo
    > https://zomato-jwt.herokuapp.com/api/auth/userinfo
    > (Header) => {'x-access-token':'token from login'}
