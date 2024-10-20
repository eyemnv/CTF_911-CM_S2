-Let's Start by reading Description.

![image](https://github.com/user-attachments/assets/a4c917b7-a338-4538-bde1-a79336ece745)

-So we have two Major clues from description that is **"Something reversing and Lets Rock"**, bascially it means to reverse something but what??.

-Hmmm, "Let's Rock", is it rockyou.txt?. Let's Try reversing **rockyou.txt**, **_rev rockyou.txt rv_rockyou.txt_** . Meanwhile Hint spawned in Discord.

![image](https://github.com/user-attachments/assets/55647ee4-84c5-4a0e-be40-5e8450fa3879)

-Ok, so password contains **"amos"**. Let's grep, **_grep "amos" rv_rockyou.txt > stg.txt_**

-We still got bunch of passwords, let's try one by one with steghide, **"_steghide extract -sf (Image_path) -p (Password)_"**.

![image](https://github.com/user-attachments/assets/07765b0f-93a5-4ff5-b234-3765418ba9f1)

-Jackpot!!!, Steghide wrote flag.txt which contains **CM{Bru73_f0rc3_i5_b35t}**
