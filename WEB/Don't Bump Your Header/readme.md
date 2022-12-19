Category: Web 
Difficulty: Medium


- Don't Bump Your Head(er)


Description

Try to bypass my security measure on this site! http://165.227.106.113/header.php


Answer:

1. take the burpsuite tools to bypass the header

2. ![header before burp](/assets/ss%20header.PNG)

3. send to repeater and click send button u got the response

4. ![response](/assets/ss%20response.PNG) u got the interest comment " Sup3rS3cr3tAg3nt "

5. filled up user-agent with Sup3rS3cr3tAg3nt and send

6. ![after filled up](/assets/ss%20response-super-secret-agent.PNG)

7. add " referer : awesomesauce.com "

8. Gotcha u got the flag
![the flag](/assets/the%20flag.PNG)


Flag : flag{did_this_m3ss_with_y0ur_h34d
