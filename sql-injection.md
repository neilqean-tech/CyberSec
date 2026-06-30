This method required you to use google dork, nmap and sql injection functioanlity

## Step-by-step:
1. Use google-dork method to seach vulnerable website.
2. once u find it, copy the website name
3. open terminal (win + R)
4. Run "ping <targeted website>", 
5. copy the website ip address then try to run nmap command
6. "nmap -sS <targeted ip address>"
7. "nmap -O <targeted ip address>"
8. "nmap -sV <targeted ip address>"
9. //
10. if some ports are open, try to lookup for website database version e.g, apache 2.16
11. check for its vulnerabilities
12. exploit it
13. //
14. Do the sql injection by putting " ' " or " '1 " in the url
15. Successful sql injection should be like this:
<img width="917" height="240" alt="image" src="https://github.com/user-attachments/assets/f82fa65b-62b6-4f7f-8060-1184812b70b3" />

## Thats it for now, more updates upcoming
