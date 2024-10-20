Let's Check Description.

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

-Now let's go to page three, so if we see here picture number 00001, 0010 was old images which gave the half of flag, so lets try steghide with 0011 as password of prev data i.e. "1t".

![image](https://github.com/user-attachments/assets/5d191e5e-64f3-4ee7-8f67-2851a7465b02)

-It wrote "part-3-flag.txt" which had pastebin link and not much info.

![image](https://github.com/user-attachments/assets/aa078482-2ca3-4440-84c4-8da6d8e4ee7f)

-Cool lets visit pastebin site via , there we got **"__1int0__"** , ok this would be pass for next part of stego. Now our flag looks like **"CM{Break_1t_1int0_"**

-Let's go to next page by clicking emoji. 

-Here word "Image" has underline means that would be the link.

![image](https://github.com/user-attachments/assets/17920a83-74da-4337-a9fc-52209bbc717d)
 
-Let's Download and deocde this with steghide and pass as last decode which was  "1int0_"

![image](https://github.com/user-attachments/assets/8124d7fe-06dc-4b42-95a5-2e546f8fba07)

-As expected got the answer, after opening file "part-4-flag.txt", hmm this now looks bit tricky.

![image](https://github.com/user-attachments/assets/6a969665-020e-46bf-95db-ca1f189c1981)

-So we got string format "CM{xxxxx_#x_#xxx#_#_x##xxx}" okay so if we compare this with our builded flag "CM{Break_1t_1int0" it looks alike alphabets are coded as X and numbers as #.

-Lets all four images that we got till now, it looks like last part of the flag "p13ces}", cool but whats that in between number?

![image](https://github.com/user-attachments/assets/e77f5539-04b7-4e02-bd42-ea2abaf113a6)

-Let's check flag4.txt output again it says about square and it has 4 sides, let's give a try for **"CM{Break_1t_1int0_4_p13ces}"**

-Bingo it worked!!!!
