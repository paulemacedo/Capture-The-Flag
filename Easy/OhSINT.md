# OhSINT

## What information can you possible get with just one photo? 🖼️ <br>

![WindowsXP_1551719014755](https://github.com/paulemacedo/CTF-OhSINT/assets/59907505/587a9433-ba5e-44ff-8057-905c90fc84bc)

> [!NOTE]
> This challenge was updated on 2024-02-01. If you are following any older walkthroughs, expect a small change.

## Answer the questions below:

### 1. What is this user's avatar of?

- First I needed to use exiftools to extract the metadata from the photo provided from the chalenge
- On the file I could find the user behind the photo and search on google to see what I would find
- The first result was his Twitter where i finded his profile pic to answer the question<br>

 __🚩 Flag: Cat__

### 2. What city is this person in?
- At his github repo  called "people_finder" I was able to find his city

 __🚩 Flag: london__

### 3. What is the SSID of the WAP he connected to? 
- With the BSSID provided on his twitter and his City I could Find his public wifi SSID using Wigle.net

 __🚩 Flag: lUnileverwifi__

### 4. What is his personal email address?
- at his twitter I was able to find his email

 __🚩 Flag: OWoodflint @gmail.com__

### 5. What site did you find his email address on?
- Even tho his email was found by me on his twitter, the challenge was hopping for me to find it on his github

 __🚩 Flag: github__

### 6. Where has he gone on holiday?
- At his Github he mentions his Wordpress
- Then at his blog I could find this flag

 __🚩 Flag: new york__

### 7. What is the person's password?
- The Most challenging Osint was finding his password
- With the hint help I searched on the HTML Source code until I found something out of the box
- At line 273 of his source code you can find the flag

 __🚩 Flag: pennYDr0pper.!__

## Badge Owned
[<img src="https://assets.tryhackme.com/img/badges/ohsint.svg" height="170" alt="python logo"/>](https://tryhackme.com/paulemacedo/badges/ohsint)

## Conclusion
> [!CAUTION]
> be carefull with the things you share online

![OWoodflint](https://github.com/paulemacedo/CTF-OhSINT/assets/59907505/4ba750b8-2f78-4453-9e0d-c551f5b8b859)
