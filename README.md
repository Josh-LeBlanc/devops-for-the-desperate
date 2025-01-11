# DevOps for the Desperate
following along with the book DevOps for the Desperate by Bradley Smith to build a homelab and learn devops concepts

outline of material:
## ch1
installed virtualbox, vagrant, ansible, vagrant-vbguest plugin (didn't work, had to work around), went through simple Vagrantfile and Ansible playbook
## ch2
set up password requirements and new linux user and group with ansible modules
## ch3
disabled passwords over ssh, enabled public key authentication as well as 2fa with google authenticator
## ch4
deployed a flask webapp with a systemd service, and assigned capabilities in the sudoers file to allow the developers group to start, stop, edit the app
## ch5
configured the firewall to deny all ports except 22 and 5000 and rate limit 5000
## ch6
containerized an app with docker and learned to run and interact with it
## ch7
downloaded kubectl and got a deployment and two services up and running with our image of the telnet app and exposed it to the whole computer
## ch8
set up a CI/CD pipeline with skaffold and the google testing tool, and learned how to roll back a kubernetes deployment
## ch9
set up application monitoring dashboard using Prometheus, Alertmanager, and Grafana
