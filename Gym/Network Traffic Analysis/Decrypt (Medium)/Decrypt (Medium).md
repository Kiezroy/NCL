![image](https://github.com/Kiezroy/NCL/assets/67439231/d83a5b0c-e09d-4b03-b69c-f83910be4a42)

- Decrypt the HTTPS packet by loading in the given SSL key log
  
- 1. Open preferences
  2. Expand protocols and select TLS (or SSL for older Wireshark version)
  3. Select the SSL key log file for the (Pre)-Master-Secret log filename
  4. View plaintext data by rightclicking packet and selecting Follow -> TLS Stream

Q1:

![image](https://github.com/Kiezroy/NCL/assets/67439231/60088575-c6a1-469f-a2bd-dcf2ebf98a81)


TLS_ECDHE_RSA_WITH_AES_128_GCM_SHA256

Q2:

- Select packet 6 and look at TLS details

![image](https://github.com/Kiezroy/NCL/assets/67439231/49989e0e-9fb1-4a47-a534-ca81c93b3a03)


tomsvacations.com

Q3:

- Find packet with flag.txt
- Right click to follow TLS stream and find flag

![image](https://github.com/Kiezroy/NCL/assets/67439231/96d0b9a6-17b4-469d-948b-3e7fccb5f9e9)

SKY-LADN-1435
