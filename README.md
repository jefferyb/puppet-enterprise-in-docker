# Install Puppet Enterprise in Docker
Scripts to install Puppet Enterprise in Docker

# How to use it

[Check out this page for more information](https://jefferyb.github.io/puppet-enterprise-in-docker/)

In short:
* Download "puppet-enterprise-2016.4.0-ubuntu-14.04-amd64.tar.gz" from [PuppetLabs](https://puppet.com/download-puppet-enterprise).
* Clone my [Puppet Enterprise Scripts](https://github.com/jefferyb/puppet-enterprise-in-docker.git) repo
* Make sure that the `puppet-enterprise-2016.4.0-ubuntu-14.04-amd64.tar.gz` file is in the cloned repo, `puppet-enterprise-in-docker`, or that you have the download link variable, `PE_DOWNLOAD_LINK`, set in `install-puppet-in-docker` file
* Edit the variables section, such as `IMAGE_NAME`, `PUPPET_MASTER_HOSTNAME` and `ADMIN_PASSWORD` at the top of `create-a-puppet-enterprise-docker-image` and `install-puppet-in-docker` files to suite you
* Run the `create-a-puppet-enterprise-docker-image` script

#### Bash
```bash
$ git clone https://github.com/jefferyb/puppet-enterprise-in-docker.git
$ mv puppet-enterprise-2016.4.0-ubuntu-14.04-amd64.tar.gz puppet-enterprise-in-docker
$ cd puppet-enterprise-in-docker
$ ./create-a-puppet-enterprise-docker-image
```
