Debian Vagrant Boxes
====================

The main goal of this repository is to provide ready to use Vagrant boxes.

They are based on Debian/amd64 netinst iso file and created using [this](https://github.com/kraksoft/vagrant-box/blob/master/build-debian.sh) script.

You can check:
- what parameters are used for unattended installation [here](https://github.com/kraksoft/vagrant-box/blob/master/preseed.cfg)
- what parameters are used to create VM Box [here](https://github.com/kraksoft/vagrant-box/blob/master/build.sh#L196)
- what is done after all [here](https://github.com/kraksoft/vagrant-box/blob/master/late_command.sh)

As you can see, this is very minimalistic version and you can use it as a base, for your future modification with e.i. [this](https://github.com/kraksoft/ansible-roles) Ansible roles.
