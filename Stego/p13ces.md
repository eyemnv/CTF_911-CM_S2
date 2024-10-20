![image](https://github.com/user-attachments/assets/ebd4627c-91f7-4103-93e9-a7d888289f8a)-Let's Check Description.

![image](https://github.com/user-attachments/assets/8fe6bae7-c6dc-48a3-a406-bd1766ca967e)

-From description its clear that we need to decrypt and craft the flag. Let's open the link and gather info.

-Nothing Much, but there is something written on middle image, also it says "this as the beginning"  SUSPICIOUS!!!.

![image](https://github.com/user-attachments/assets/dcb09e2d-9a7c-4687-8457-b64e3ba15268)

-Theres also emoji at the End. Let's Cick it. New Page Opens Up.

-Again the page has one photo which has some text, still not any hard clue. Again an emoji with link, let's open.

![image](https://github.com/user-attachments/assets/32bc7669-42eb-4d2d-8d80-52f54d8090cd)

-Big clue from the new page it says **" One and Two Make Three..."** ,is it serial stego?.

![image](https://github.com/user-attachments/assets/ba86cd14-0abf-4568-ab00-46a8cf2fd0fe)

-Let's select all text by **_CTRL+A_** .There's a catch, it says "What you need is hidden with steghide."

![image](https://github.com/user-attachments/assets/88d26687-02c4-4b8a-abc9-30c354e5da61)

-Lets get back to first page download that image, file name says **1.jpg** it means we are on a right track. Let's try to crack it steghide.  

-Excellent move it wrote **"part-1-flag.txt"**. It had **{Break_**, Which looks flag format.

![image](https://github.com/user-attachments/assets/275fcfcf-ec4e-4654-aab0-30189bf012af)

-Now get back to page 2 lets try same steghide with that image which had some written on it, on downloading it says 2.jpg. Hmm good track, without pass no values got exctracted, Now using 1st output as password for next which is **"{Break_"** 

-FAB!! got the second part, it says "1t". Now our flag is **"{Break_1t"**

![image](https://github.com/user-attachments/assets/2d24e61c-0bd5-49da-bd1f-e4078158dd0c)

-Now lets go to page three, so if we see here picture number 00001, 0010 was old images which gave the half of flag, so lets try steghide with 0011 as password of prev data i.e. "1t".

![image](https://github.com/user-attachments/assets/5d191e5e-64f3-4ee7-8f67-2851a7465b02)

-It wrote "part-3-flag.txt" which had pastebin link and not much info.

![image](https://github.com/user-attachments/assets/aa078482-2ca3-4440-84c4-8da6d8e4ee7f)

-Cool lets visit paste, there we got **"__1int0__"** , ok this would be pass for next part of stego. Now our flag looks like **"CM{Break_1t_1int0_"**
