# Adminless Docker in Windows 11 Home
This is what I understand is the Windows equivalent of rootless docker.

Using this [this stackoverflow answer:](https://stackoverflow.com/a/67831886)

Running cmd or powershell as admin, run:

`net localgroup "docker-users" "<user_name>" /add`
