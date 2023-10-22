# Solution
- Browse the link from the challenge http://155.138.162.158/.

![Alt text](image.png)

- Run plain nmap on the IP:
```bash
nmap 155.138.162.158
```

![Alt text](image-1.png)

- Connect to port 8888 with netcat and get the flag (after getting rick rolled).
```bash
nc 155.138.162.158 8888
```

![Alt text](image-2.png)
