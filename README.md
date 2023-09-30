# security
Created a simple authentication API to understand the flow of this process and test on Postman.
This App would have been named Authentication API rather tahn security.

The image below shows an attempt to use the authenticate endpoint of our endpoint with a non existing user,
notice the 403 code.
![Auth-Failed](https://github.com/yourisev/security/assets/69630866/f162a65c-4562-42b5-8fc0-4f62f189e19b)
Just to show the previous image is right we can see that our Postgres DB is empty on the image below.
![image](https://github.com/yourisev/security/assets/69630866/698f328d-29d7-4db4-8435-7997feb308b3)
The image below shows that the user with credentials in the body of the request is successfullly registered,
notice the 200 code.
![image](https://github.com/yourisev/security/assets/69630866/c2de43ca-dc63-420a-b2f6-7bfdceda38b4)
The image below shows how the DB is populated after we sent the above request to registration endpoint.
![image](https://github.com/yourisev/security/assets/69630866/3891f691-f66e-438c-8fa5-80a4bbb0c9cc)

![image](https://github.com/yourisev/security/assets/69630866/47282c5f-19f7-40cb-b966-76da2de2bd86)

![Bad-token-test](https://github.com/yourisev/security/assets/69630866/f17d9ff7-585e-413b-819f-769184217567)

![image](https://github.com/yourisev/security/assets/69630866/6a287327-d297-4e59-8e6d-5ea323b7d271)
