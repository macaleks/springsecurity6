GET http://localhost:8080/oauth2/authorize?response_type=code&client_id=client-id&redirect_uri=http://localhost:8080/login/oauth2/code/client-id&scope=read






curl -X POST \
http://localhost:8090/oauth2/token \
-H "Content-Type: application/x-www-form-urlencoded" \
-d "grant_type=password&username=user&password=password&client_id=my-client-id&client_secret=my-client-secret"



curl -H "Authorization: Bearer <your-access-token>" http://localhost:8081/api/hello





curl -X POST \
http://localhost:8090/oauth2/token \
-H "Content-Type: application/x-www-form-urlencoded" \
-d "grant_type=password&username=user&password=password&client_id=client-id&client_secret=client-secret&scope=read"




Error 403 No valid crumb was included in the request
.


curl -X GET http://localhost:8090/oauth2/authorize?response_type=code&client_id=client-id&user=user&password=password


http://localhost:8080/login/oauth2/code/client-id?code=SplxlOBeZQQYbYS6WxSbIA


http://localhost:8080/login/oauth2/code/client-id?code=SplxlOBeZQQYbYS6WxSbIA


curl -X POST \
http://localhost:8080/oauth2/token \
-H "Content-Type: application/x-www-form-urlencoded" \
-d "grant_type=authorization_code&code=SplxlOBeZQQYbYS6WxSbIA&redirect_uri=http://localhost:8080/login/oauth2/code/client-id&client_id=client-id&client_secret=client-secret"
