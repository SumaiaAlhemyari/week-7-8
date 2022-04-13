# week-7-8
It took me seven hours on total
I could not finish it on time because vagrant gave me issues and I had to fix the erroes.

Attack 1: CSRF

<img width="1280" alt="xss" src="https://user-images.githubusercontent.com/90657763/163084366-e52f3735-640e-4291-a18b-3b532d264011.png">

Attack 2: Directory Traversal and Informaiton Exposure

A directory listing is inappropriately exposed, yielding potentially sensitive information to attackers. using this paths on the URL can be acces the follow directories. vulnerablewordpress/wp-admin/js/ vulnerablewordpress/wp-admin/css/ the attacker can acces

<img width="1280" alt="Directory Traversal and Informaiton Exposure 1" src="https://user-images.githubusercontent.com/90657763/163084476-c7e96763-67cf-48ac-a291-0ce6539bd073.png">
<img width="1280" alt="Directory Traversal and Informaiton Exposure 2" src="https://user-images.githubusercontent.com/90657763/163084487-d21c93f3-43eb-4f8d-b68c-5556eb53714c.png">

Attack 3: Vulnerability Name or ID: Password Brute Force Attack

source: wpscan --url wpdistillery.vm --enumerate u wpscan --url wpdistillery.vm --usernames '' --passwords /usr/share/wordlists/rockyou.txt

<img width="1280" alt="Screen Shot 2022-04-12 at 11 12 24 PM" src="https://user-images.githubusercontent.com/90657763/163092692-a966b708-b7b9-466a-82cb-103bc0bb39b1.png">
