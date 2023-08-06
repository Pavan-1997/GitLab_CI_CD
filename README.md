# For GitLab Runner Installation follow the below commands

Recommended to perform below commands as a ROOT user
----------------------------------------------------------------------------------------------

```
curl -L https://packages.gitlab.com/install/repositories/runner/gitlab-runner/script.deb.sh > script.deb.sh
```
```
sudo bash script.deb.sh
```
```
sudo apt install gitlab-runner
```
```
systemctl status gitlab-runner

For REGISTRATION_TOKEN go to Project settings -> CICD -> Runners -> Copy the token and paste in below command

sudo gitlab-runner register --url https://gitlab.com/ --registration-token $REGISTRATION_TOKEN
![image](https://github.com/Pavan-1997/GitLab_CICD/assets/32020205/575cd389-0404-4f2f-a8ee-c975443a531a)
