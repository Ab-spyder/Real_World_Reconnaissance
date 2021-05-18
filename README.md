# Real_World_Reconnaissance (Spring 2020)
I Perform a Passive Reconnaissance on a real company and founds lots of juicy info! (Obsfuscated here of course!)

This coursework helped me replicate the **4ttack3r m1nds3t !**

I Performed a PASSIVE reconnaissance on a Healthcare service providing company using popular Open-Source Intelligence (OSINT) tools and techniques like:
- Google-fu
- Maltego 
- Metagoofil
- Spiderfoot
- Dmitry
- Netcraft
- Censys
- theHarvester

1. Google-fu yielded some results describing some hardware and software used in the organization like fax software, printers, load balancers and signature capture hardware
2. Using Maltego, different hosting providers in an organization along with their netblocks and their location could be identified. 
3. Spiderfoot’s scan comprised of some real interesting results which included **75+ compromised passwords** and **350+ compromised hashes**. The passwords found can be used for attacks like Credential Stuffing, and Password Spraying. The hashes found can be taken offline and cracked or used in other attacks like pass the hash.
4. Metadata like applications, usernames and email addresses were found using Metagoofil.
5. Dmitry and Netcraft provided us with some footprint of nameservers and analysis of web servers. 
6. With the help of Censys, we could find some of vulnerable nginx servers running in the organization.
7.  Finally, theHarvester provided us with names and job descriptions of employees using social media analysis.

In conclusion, I managed to find over 75 compromised passwords (clear text), 350+ compromised hashes, used applications, usernames, email addresses, footprint of nameservers and webservers, vulnerable nginx servers, employee names and their job roles on my target. 
