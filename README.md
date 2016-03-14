# vagrant-puppet-phantomjs-python
Vagrant file for a Debian 7 system able to run Robot Framework python tests with PhantomJS with Webdriver.

# History

13.Mar.2016 :: Fixed pip install failures due to Python.pp package installing before Server.pp packages (such as gcc!). Full info at http://tech.yipp.ca/vagrant/solved-fix-puppet-pip-install-failure/

10.Mar.2016 :: Created Virtualbox VM with 4096MB of RAM running Debian Wheezy 7 x64.
