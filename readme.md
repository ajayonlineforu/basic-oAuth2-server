Testing
==========

1. Get the token

POST
    http://localhost:8282/oauth/token

authorization : client/web and secret/webpass

form-data = 
    grant_type = password
    username = username/ajay
    password = password/ajaypass
    
    
2. Check the token

    http://localhost:8282/oauth/check_token?token=2f5f9cbf-5591-435d-9822-bace9861588c