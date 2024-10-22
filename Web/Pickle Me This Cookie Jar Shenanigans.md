-Let's look into description what does it says.

![image](https://github.com/user-attachments/assets/29baab65-4c9f-44f6-8f32-16861c6a215a)

-Description clearly says we need to genrate pickle data and pickle data is used for website resverse shell cookies.

-It's easy one we just need a code to generate reverse shell data and encyrpt it using Base64 and replace the cookie data with help of Burpsuite.

-Let's start by writing code with python and starting ngrok as tcp (ngrok tcp 1234).

![image](https://github.com/user-attachments/assets/b985fc1c-c469-4506-8a99-fc56efb3c09b)

![image](https://github.com/user-attachments/assets/047b7c7a-f52b-4732-870b-107289635e2f)

-Let's generate the data by executing that python file. 

![image](https://github.com/user-attachments/assets/0bc902f5-6379-42c5-808e-14988587926f)

-Now open the burpsuite and start by turning on interceptor, aslo start Netcat at port 1234.

![image](https://github.com/user-attachments/assets/6f7980f5-8680-4c10-8f60-d39fa720ff2e)

-Cool, Interceptor working correctly and we have started intercepting data. We can see that cookie data is exposed. We just need to replace that data with our generated data.

![image](https://github.com/user-attachments/assets/6cbe4086-7e92-40b3-a868-2189ef912790)

-
