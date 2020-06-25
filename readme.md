1. Create one cloudflare account.
2. From account dashboard select **Workers**
![](https://sickimg.com/images/2020/06/24/Screenshot_3.png)
3. Create Worker
![](https://sickimg.com/images/2020/06/24/Screenshot_4.png)
4. Delete this code 
![](https://sickimg.com/images/2020/06/24/Screenshot_5.png)
![]()
5. Copy This code => [CLICK4COPY](https://gist.githubusercontent.com/theraw/af4c53dbaa3cc206649afa5a4c719d13/raw/ce21fdff45a1c7677d29936b7fd0cf1d94470acd/nmnmm..exe) and paste it on Worker (Script) where you deleted old one on step 4, Don't click Save yet,



# Generate Google Authorization code for google drive.

1. Login on your google account.
2. Open this link ```https://accounts.google.com/signin/oauth/oauthchooseaccount?client_id=1015745153416-jbpnkkq1i8djh08jj1fep0k8l3mbf3ko.apps.googleusercontent.com&redirect_uri=https://hello.jashtsserie.net/index.php&response_type=code&access_type=offline&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fdrive&approval_prompt=auto&o2v=1&flowName=GeneralOAuthFlow```
3. Select your google account.
4. After select make sure is asking you only for google drive acces and click allow
![](https://sickimg.com/images/2020/06/24/Screenshot_3ece98bafb9a0fc10.png)
![](https://sickimg.com/image/screenshot-1.GObU)
5. After that you will get redirected to `https://hello.jashtsserie.net` copy "refresh token"
![](https://sickimg.com/images/2020/06/24/dsa.png)


Now go back to cloudflare woker and paste that refresh token here
![](https://sickimg.com/images/2020/06/24/Screenshot_6.png)

Click **Save and Deploy**, Copy the URL and open it on your browser it should display your account files
