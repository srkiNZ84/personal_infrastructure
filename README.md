# Personal Infrastructure

## About

The idea behind this repository is to contain the configuration required to bring up a set of personal infrastructure
services, e.g. Website/Blog, Mail server, DNS servers etc...

It tries to use best practice methods for configuration management (current Ansible) in order to set these up, but
should be viewed as a work in progress as I'm really using it to learn and also as a test bed for trying out new ways of
working.

## How to use
The current plan is to make the code generic enough that you only need to specify an environment file and run the
`site.yml` playbook to bring up the infrastructure from scratch or alternatively modify the existing infrastructure to
match the new configuraiton. Details to come as the project grows.

## Contributions
If you would like to contribute, please submit a pull request or open an issue on the project.
