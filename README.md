# phusion-app-template
Docker template to containerize an application using [arturol76/phusion-baseimage](https://github.com/arturol76/phusion-baseimage) (i.e. phusion) as base image.

Why phusion and not ubuntu? Have a look to this:
https://blog.phusion.nl/2015/01/20/docker-and-the-pid-1-zombie-reaping-problem/

## Sample app
TBD

## Your app
TBD

## SSH Keys
Have a look to the [keys](./keys/README.md).

## Build
TBD

## Run
TBD

## VSCODE: sample config file for the SFTP extension
Assuming you use pageant to manage the key authentication:
```
{
    "name": "mydocker",
    "host": "192.168.2.96",
    "protocol": "sftp",
    "port": 7122,
    "username": "root",
    "remotePath": "/",
    "agent": "pageant",
    "passphrase": true,
    "uploadOnSave": true
}
```