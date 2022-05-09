# Lab Report 3

## Streamlining ssh Configuration

![Image](lab-report-3-ssh.PNG)
- Added a config file to automatically enter in my long username when ieng6 is inputted. Used notepad to edit the file.

![Image](lab5_part1.PNG)

- Adding a file with scp using ieng6
![Image](lab-report-3-scp.PNG)

## Set up Github access from ieng6

- Copy of Public key is stored in github account
![Image](lab-report-3-gitkeys.PNG)

- Private key is stored in ieng6 .ssh folder in id_ed25519
![Image](lab-report-3-privkey.PNG)

- Pushing from ieng6 still does not work after adding public key to github
![Image](lab-report-3-giterror.PNG)

## Copy from whole directories using scp -r

- Copying markdown-parse with scp -r
![Image](lab-report-3-scpr.PNG)
![Image](lab-report-3-scpr2.PNG)

- Running junit tests after copying into remote ieng6
![Image](lab-report-3-test.PNG)

- Copying directory over to remote using scp and also running test in one line
