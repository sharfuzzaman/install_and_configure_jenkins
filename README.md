# install_and_configure_jenkins
## macOS M1 chip
- Perform how to install jenkins and configure it

## Install jenkins with cmd
```bash
    $ brew install jenkins
```
To start it from cmd
```bash
    $ jenkins
```
After this visit IP:8080 (localhost or your local ip or your public ip). If you are using your vm in any cloud environment then allow the port 8080 or set proxy thorugh nginx or apache web server that your can can listen on port 80.

After opening jenkins server on your browser you will get initialPassword prompt which you will get from the cmd

![App Screenshot](https://github.com/sharfuzzaman/install_and_configure_jenkins/blob/main/initialPassword.png)

After that go to the browser and put the initialPassword. It will navigate you through the next page and for installing plugin you can choose which plugin is important for you.

Now after installing plugin you will gate a page where you can Input your name and other details.

![App Screenshot](https://github.com/sharfuzzaman/install_and_configure_jenkins/blob/main/input_file.png)

After filling up the details it will navigate you in the jenkins home page/ Dashboard.

