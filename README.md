# Ansible
My Ansible playbooks, which are useful to run my daily job and hope become also to you.

## Description
* Just a place where I put my own Ansible playbooks.
* They are written for Ubuntu 14 boxes.
* These playbooks are in a very early stage, so please be patient and let me improve them.
* Some files aren't uploaded due to security/privacy reasons ([.gitignore](.gitignore) rules). Anyway, I hope this code is pretty clear enough, although ...
* ... I'm starting to use Ansible Vault.

## Let's fly!
* Type something like `ansible-playbook -i production site.yml -K --ask-vault-pass`.

## To Do
* Add conditional statements in order to provide more compatibility.
* Add *useful* features to Apache and MySQL playbooks.

## Disclaimer
* Read [LICENSE](LICENSE) file.
* Although all this content is public and free (read [LICENSE](LICENSE) file), it was designed for the servers I manage, so you **should** modify it.
* Suggestions and improvements are welcome. Otherwise, crap content goes to `/dev/null`.

## Credits
* `ansible-examples` were essential to understand how powerful can be Ansible.
* Some tweaks implemented here are seen before in [François Marier blog](
http://feeding.cloud.geek.nz/posts/usual-server-setup).
* Other tips are found at [Ubuntu Hardening Guide](http://hardenubuntu.com/).
