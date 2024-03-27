
# Spring boot with Auth0
![image Auth0](https://github.com/HuyWibu/Spring-boot-with-Auth0/assets/90228123/cd6bd66b-f0af-403e-8987-033d14a58647)

Tạo user sử dụng api management của Auth0


## Configuration Auth0 API Management
Link driver xem ảnh: https://drive.google.com/drive/folders/15Lmxxm-yPGlmtAcvD0ur-Tv8YOWN7IMd?usp=sharing




Làm theo lần lượt các bước theo thứ tự từng ảnh trong driver

Các bước từ 1 - 5 -> Lấy access token



Link docs của Auth0 lấy các API:
https://auth0.com/docs/api/management/v2/users/post-users



## API get access token and create user

API có thể thay đổi tùy vào tài khoản Auth0 của mỗi người
### Get Access Token
```bash
  https://dev-aiy70kycups8tkjz.us.auth0.com/oauth/token
```
### Create User
```bash
  https://dev-aiy70kycups8tkjz.us.auth0.com/api/v2/users
```


# Payload in user metadata! 👋


## User Metadata
#### 
{ 
  ##### "email":"user@gmail.com",
  ##### "user_metadata":{},
  ##### "blocked":false,
  ##### "email_verified":false,
  ##### "app_metadata":{},
  ##### "given_name":"huy",
  ##### "family_name":"huy",
  ##### "name":"huy",
  ##### "nickname":"huy",
  ##### "picture":"https://i1.wp.com/cdn.auth0.com/avatars/te.png?ssl=1",
  ##### "user_id":"huy123",       
  ##### "connection":"Username-Password-Authentication", 
  ##### "password":"P@ssword1",
  ##### "verify_email":false
  
  }
