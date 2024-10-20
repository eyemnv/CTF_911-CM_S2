-Let's start with reading Description of the Flag.

![image](https://github.com/user-attachments/assets/7720ab27-3f8b-47cc-bf36-a7146af15f06)

-So we have Encrypted Text and Decrypted Text we need to Find the right Configuration. Also we have hint from disord.

![image](https://github.com/user-attachments/assets/5d5044ac-29be-43a2-b2be-05c8b5dffb6e)

-I am Using https://cryptii.com/pipes/enigma-decoder to get right configuration.

-As from we can extract plug board settings as A(pple) - T(ree) and B(anana) - L(emon)

-Using common Rotor setting as "I-II-III"

-Using Common Ring Setting as "A-A-A"

-Using common Refelctor setting - "B"

-Now we need to find Position setting - "A-A-A", "B-B-B", "C-C-C", etc.

![image](https://github.com/user-attachments/assets/ab438fd6-918f-41de-b62e-4e00c1853a6f)

-Not a good hit, lets try "A-D-F" ,"B-C-A" etc.

![image](https://github.com/user-attachments/assets/cfdae265-5667-4edf-92c1-43e366f005c6)

-Gotcha, Finally CipherText and Decoded text matched to the flag description.

-Let's craft the flag as per description **CM{Rotor_I-II-III_Pos_A-D-F_Reflector_B_Plug_A-T_B-L_Ring_A-A-A}** 
