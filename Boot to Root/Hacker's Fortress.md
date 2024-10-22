-Let's look into description what does it says.

![image](https://github.com/user-attachments/assets/12b09a87-52b4-4e42-bdfe-cdb5b5522eab)

-Nothing Much Clue. Let's Go to link. Hmm, Basic PHP Login Form. Let's Start with register and Sign in.

![image](https://github.com/user-attachments/assets/e7d13fd9-ea2d-4097-be6c-f264d5560959)

-Upload File option, but only takes PDF and PNG.

![image](https://github.com/user-attachments/assets/9438037e-a1a8-489e-9e8e-903300a8d778)

-Let's Create PHP reverse shell with help of Pentest Monkey Framework (https://pentestmonkey.net/tools/web-shells/php-reverse-shell).

![image](https://github.com/user-attachments/assets/90f1768b-8b29-4862-b189-9558e4b50634)

-I am using ngrok for port forwarding. Command to ngrok is _ngrok tcp (port-number)_, I am using 1234.

![image](https://github.com/user-attachments/assets/9d986f3a-ba38-472f-8412-41e749342381)

-Replacing IP address and Port number with ngrok given data 

![image](https://github.com/user-attachments/assets/c356779f-0955-4ac9-a660-f4d7c60482c6)

-Starting NetCat at port 1234, port using to start ngrok.

![image](https://github.com/user-attachments/assets/779ee9a7-9edc-4fd2-b38c-024b343e77ae)

-Now let's upload the file to CTF server. Coincidentally File got uploaded and PDF, PNG filter didn't occurred any error.

![image](https://github.com/user-attachments/assets/e6b642dc-cd2c-4da0-8f69-d5d57c74a765)

-Genreally in these types of CTF uploads directory is exposed. Let's try uploads directy if it's open.

![image](https://github.com/user-attachments/assets/04985897-bab7-426c-a8fd-3f52f6ea1295)

-Let's Finds our file and try to execute it.

-Hmm we got the shell.

![image](https://github.com/user-attachments/assets/f80274ac-3a57-49ad-8b0f-3e3301547f16)

-Let's try to list of all the file using "ls -al"

![image](https://github.com/user-attachments/assets/1367dd80-d641-4231-859a-26707c229bf4)

-Boom we got .hidden_flag file. Which had flag CTF{3sc4l4t3d_t0_r00t}
