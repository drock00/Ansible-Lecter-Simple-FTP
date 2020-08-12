# Ansible-Lecter-FTP-Install-Uninstall-Simple

### Simple way to install, enable, open the firewall for vsftpd service and undo all

For RedHat systems only folks, yum yum. But it can easily be modified for other distros. Anyway there are two files, install.yml installs, enables, and opens the firewall for vsftpd/ftp while uninstall undos all three of those steps. This one comes with a plot twist! Jinja2 template to enable anonymous enable so that users can read the README.md file being served.

# Example Run 1
```sh
$ ansible-playbook install_vsftpd.yml 
```
# Example Run 2
```sh
$ ansible-playbook uninstall_vsftpd.yml 
```

### Tech and Running the file

These are very simple plays Boo, they're not Shakespeare. 