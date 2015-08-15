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

## License
This code is released under the GPL
    Copyright (C) 2015  Srđan (Serge) Đukić
    
    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
