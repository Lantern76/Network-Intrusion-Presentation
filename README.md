### Network-Intrusion-Presentation

### Scenerio(Purely Fictional)
A recently hired website administrator maintains and manages multiple websites across the country. Their reputation is good, and they are relatively inexpensive. Mercury USA, the small company I work for, just hired them. Their contract states that they may only access the Windows system through RDP (Remote Desktop Protocol - 3389). I am their Forensic Analyst for Mercury USA. My IT specialist provided the website administrator with an account with administrative access so they can change and update their settings. The website administrator has many sites to maintain. As a shortcut, they added a hidden folder to the website. Within that folder there is a file where they stored their credentials so they can easily access the system. No one should be able to find this hidden folder and the file with the credentials, since it is not indexed. And, just as an extra precaution, the website administrator encoded the password with Base64 encoding on the off chance that someone with a lot of time on their hands would figure out the hidden URL. An attacker who regularly scans websites with directory buster, or dirb (a built in Kali Linux tool), finds the hidden URL and then decodes the base64 password.

### Purpose
This presentation below is designed to mimik a presentation submitted to the higher ups of the fictional company showcasing key evidence of the recent attack as well as showcase the potential dangers of the malicious individuals actions. 


### Presentation

[CST640_Project1_RyanSteggerda.pptx](https://github.com/Lantern76/Network-Intrusion-Presentation/files/14881072/CST640_Project1_RyanSteggerda.pptx)
