# Solution
- Download the welcomeToThePark.zip file.
- Unzip the file.
```bash
unzip welcomeToThePark.zip
```
- Cat the conent of "welcomeToThePark" file and notice an obfuscated chunk of data.
```bash
cat welcomeToThePark
```

![Alt text](image.png)

- Base64 Decode the data chunk and save the output in a file called "decoded".
```bash
echo -n <DATA> | base64 -d > decoded
```

- There is a zsh script embedded in the XML file.

![Alt text](image-1.png)

- Copy the script and output the command.

![Alt text](image-2.png)

```bash
./zshScript
```

![Alt text](image-3.png)

- There is a link in the output: https://gist.github.com/stuartjash/a7d187c44f4327739b752d037be45f01. Download the image found at the link.

![Alt text](image-4.png)

- Cat the image content to get the flag.
```bash
cat JohnHammond.jpg
```

![Alt text](image-5.png)
