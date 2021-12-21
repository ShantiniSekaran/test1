<h1 align ="center">Assignment2</h1>

## How to deploy files into git ?    
#### 1. We create a new file under our project/folder in VS Code and name the file.
#### 2. On the terminal, we push the file to git using the following command:
```sh
git add . 
git commit -m "added filename " 
git push
```


## Why SSH is used over HTTPs ?   
#### SSH means "secured shell".
#### SSH is prefered over HTTPs to reduce security threats for remote server login as SSH uses key passphrase and not password for authentification as with HTPPs.
#### HTTPs requires repetitive authentification using password to perform any action which is tedious as compared SSH.Therefore, SSH which uses key passphrase is considered safer and convenient compared to HTTPs.

## How does one create an SSH key?
#### To create SSH key, we need to ensure that we have Open SSH client installed in our computer. 
#### Open up the Command Prompt as Administrator(For Windows) and Terminal (For Linux/Mac).
#### Type in the following command:
#### ```sh
#### ssh-keygen-t rsa
#### ```
#### Next, you will have to type in the location of the file where you would like to save the private key.
#### The public key will be saved in the same location, under the same file name, but with the .pub extension.
#### Type in nothing to use the default location, which is /home/ youruser ssh id_rsa .
#### Finally, you will have to type in a password. This will be the password required to load the private key and use it to connect via SSH later on. 
