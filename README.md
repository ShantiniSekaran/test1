<h1 align ="center">Assignment2-Question1</h1>

## How to deploy files into git ?    
#### 1. We create a new file under our project/folder in VS Code and name the file.
#### 2. On the terminal, we push the file to git using the following command:
```sh
git add . 
git commit -m "added filename " 
git push
```

## Why SSH is used over HTTPs ?   
#### 1. SSH means "secured shell".
#### 2. SSH is prefered over HTTPs to reduce security threats for remote server login as SSH uses key passphrase and not password for authentification as with HTPPs.
#### 3. HTTPs requires repetitive authentification using password to perform any action which is tedious as compared SSH.Therefore, SSH which uses key passphrase is considered safer and convenient compared to HTTPs.

## How does one create an SSH key?
#### 1. To create SSH key, we need to ensure that we have Open SSH client installed in our computer. 
#### 2. Open up the Command Prompt as Administrator(For Windows) and Terminal (For Linux/Mac).
#### 3. Type in the following command:
```sh
ssh-keygen-t rsa
```
#### 4. Next, you will have to type in the location of the file where you would like to save the private key.
#### 5. The public key will be saved in the same location, under the same file name, but with the .pub extension.
#### 6. Type in nothing to use the default location, which is /home/ youruser ssh id_rsa .
#### 7. Finally, you will have to type in a password. This will be the password required to load the private key and use it to connect via SSH later on. 
