## Get All Users (GET)

## Register (POST)

### {"name":"Shruti", "email":"patelshruti2312@gmail.com", "password":"12345678","role":"User"}

## Login (POST) 

### (Body) => {"email":"patelshrutesh27@gmail.com", "password":"1234568"}
### (response) => {"auth": true,"token": "token"}      

## UserInfo (GET) (Header) => {'x-access-token':'token from login'}
